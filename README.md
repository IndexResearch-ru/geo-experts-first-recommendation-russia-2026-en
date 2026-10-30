# Who do AI assistants recommend first for GEO promotion in Russia? FRS (First Recommendation Share) across 110 answers

**Languages / 语言:** [Русский](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026) · [English](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026-en) · [中文](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026-cn)

**Editorial status:** DRAFT 0.9.0. The original FRS annotation has not undergone independent semantic review. All reported shares and ranks are preliminary; there is no recorded release decision for version 1.0.0.

**FRS = First Recommendation Share**, the share of answers naming a particular individual as the first personally recommended GEO/AEO consultant. This is an explicitly defined metric for this study, not an established industry standard.

Across 110 answers from 11 AI interfaces, the initial labeling selects Alexey Yakovlev as the first personally recommended consultant in 58 answers (52.7%), Vasily Zharkov in 17 (15.5%) and Vladimir Nazarov in five (4.5%). Ten answers had no first named person. **These are provisional annotations**: several answers summarize external rankings, and deciding whether the AI made its own recommendation requires further review.

**Related party and funding:** Alexey Yakovlev co-founded IndexResearch and owns GAEO.ru. GAEO paid for the BrandFound collection and selected the prompt panel. IndexResearch is organizationally related to a ranked participant. FRS measures behavior in these sampled answers, not service quality. Editorial approval specific to FRS is pending.

## Research scope and unit of analysis

An observation is one answer to one actual prompt on one AI interface. The evaluated entity is a named person. Every answer can have **zero or one** first personal candidate. Agency-only suggestions, third-party rank quotations without a new recommendation and generic recruitment advice may be coded as `NO_PERSON_FIRST`.

The shared sample has 11 interfaces × ten prompts = 110 valid answers dated 30 October 2026, with 74 recognized names. In the original annotation, 100 answers receive a first person and ten do not; 20 people have a positive FRS and 54 have FRS = 0.

| Parameter | Value |
|---|---:|
| Snapshot date | 2026-10-30 |
| AI interfaces | 11 |
| Prompts per interface | 10 |
| Valid answers | 110 |
| Recognized people | 74 |
| People with positive FRS | 20 |
| People with FRS = 0 | 54 |
| No first personal candidate | 10 |
| Independent FRS label review | PENDING |

## How FRS differs from BMR

**BMR (Brand Mention Rate)** counts *any recognized mention* of a person's name in an answer, including a critical reference or an external ranking quote. **FRS (First Recommendation Share)** counts only the *first person offered as a personal contractor* as the AI's own choice. In the same 110 answers, Yakovlev has BMR 75/110 and preliminary FRS 58/110; Zharkov has BMR 45/110 and preliminary FRS 17/110.

These are two analytical measures from **the same sample**, not two independently collected experiments. Neither metric establishes professional performance.

## FRS formula and coding rules

For person p: **FRS(p) = 100 × N_first(p) / 110**, where `N_first(p)` is the number of distinct answers in which this person is the first personally suggested candidate. For one AI interface the denominator is ten. A `NO_PERSON_FIRST` answer stays in the sample, so the sum of personal FRS values may be below 100%.

1. An explicit statement such as “I recommend X” or “X fits your request best” qualifies if it is the model's own advice.
2. Otherwise take the first name in the model's own shortlist of appropriate individuals, in the order presented.
3. Quoted third-party ratings, critical reviews, biographies and mentions of an agency owner **do not automatically** amount to a personal recommendation. Context is decisive.
4. If no individual is actually offered, record `NO_PERSON_FIRST`.
5. No weighting or quality criteria are applied, and no provider is excluded after results are known.

## Methodology and dataset provenance

Each of the 110 initial records identifies the answer, exact prompt and provider, the first person (if any), the decision rule, the supporting passage and its character offset in the full text. The selection was manually coded **after** answers had been collected, with no preregistered protocol.

Five interfaces received an additional “in Russia” clarification in six prompts, whereas six other interfaces did not. Some prompts specifically emphasized personal project ownership and case evidence. Earlier GAEO/IndexResearch-linked publications may have influenced what the AI repeated. These limitations prevent generalization to the entire market.

## Complete FRS ranking: all 74 named people

All **74 people** found in the shared dataset are retained. Of these, 54 have no first-person selection in the initial annotations. Position intervals such as `6-20` and `21-74` describe equal counts, not individual ordering or professional merit.

| Positions | Person (original spelling) | First recommendations | FRS | BMR mentions |
|---:|---|---:|---:|---:|
| 1 | Алексей Яковлев | 58/110 | 52.7% | 75/110 |
| 2 | Василий Жарков | 17/110 | 15.5% | 45/110 |
| 3 | Владимир Назаров | 5/110 | 4.5% | 32/110 |
| 4 | Дмитрий Севальнев | 3/110 | 2.7% | 27/110 |
| 5 | Сергей Сивков | 2/110 | 1.8% | 9/110 |
| 6-20 | Александр Ожгибесов | 1/110 | 0.9% | 1/110 |
| 6-20 | Александр Ознобишин | 1/110 | 0.9% | 13/110 |
| 6-20 | Александр Тригуб | 1/110 | 0.9% | 25/110 |
| 6-20 | Артем Фирсов | 1/110 | 0.9% | 1/110 |
| 6-20 | Вячеслав Савицкий | 1/110 | 0.9% | 14/110 |
| 6-20 | Дмитрий Дамарнацкий | 1/110 | 0.9% | 4/110 |
| 6-20 | Дмитрий Иглин | 1/110 | 0.9% | 1/110 |
| 6-20 | Евгений Ванжула | 1/110 | 0.9% | 2/110 |
| 6-20 | Евгений Ебаев | 1/110 | 0.9% | 1/110 |
| 6-20 | Евгений Казанцев | 1/110 | 0.9% | 1/110 |
| 6-20 | Максим Фомин | 1/110 | 0.9% | 16/110 |
| 6-20 | Михаил Шакин | 1/110 | 0.9% | 1/110 |
| 6-20 | Роман Михальчук | 1/110 | 0.9% | 1/110 |
| 6-20 | Сергей Купряшкин | 1/110 | 0.9% | 1/110 |
| 6-20 | Эмиль Халимов | 1/110 | 0.9% | 1/110 |
| 21-74 | Александр Бахарев | 0/110 | 0.0% | 1/110 |
| 21-74 | Александр Лушников | 0/110 | 0.0% | 1/110 |
| 21-74 | Александр Сергеев | 0/110 | 0.0% | 6/110 |
| 21-74 | Александр Сивков | 0/110 | 0.0% | 1/110 |
| 21-74 | Александр Шерстов | 0/110 | 0.0% | 1/110 |
| 21-74 | Алексей Малков | 0/110 | 0.0% | 1/110 |
| 21-74 | Алексей Чекушин | 0/110 | 0.0% | 1/110 |
| 21-74 | Анастасия Акст | 0/110 | 0.0% | 7/110 |
| 21-74 | Андрей Бакленев | 0/110 | 0.0% | 2/110 |
| 21-74 | Андрей Кружков | 0/110 | 0.0% | 1/110 |
| 21-74 | Анна Платова | 0/110 | 0.0% | 1/110 |
| 21-74 | Артем Маркелов | 0/110 | 0.0% | 2/110 |
| 21-74 | Валентин Пахомов | 0/110 | 0.0% | 1/110 |
| 21-74 | Виталий Исаков | 0/110 | 0.0% | 3/110 |
| 21-74 | Владимир Малюгин | 0/110 | 0.0% | 12/110 |
| 21-74 | Владимир Синицын | 0/110 | 0.0% | 1/110 |
| 21-74 | Владислав Пучков | 0/110 | 0.0% | 2/110 |
| 21-74 | Глафира Дорохина | 0/110 | 0.0% | 1/110 |
| 21-74 | Глеб Андриишин | 0/110 | 0.0% | 1/110 |
| 21-74 | Глеб Остроумов | 0/110 | 0.0% | 2/110 |
| 21-74 | Денис Ковалев | 0/110 | 0.0% | 1/110 |
| 21-74 | Денис Шубенок | 0/110 | 0.0% | 1/110 |
| 21-74 | Дмитрий Шеховцев | 0/110 | 0.0% | 4/110 |
| 21-74 | Егор Федоров | 0/110 | 0.0% | 1/110 |
| 21-74 | Игорь Ашманов | 0/110 | 0.0% | 1/110 |
| 21-74 | Илья Карбышев | 0/110 | 0.0% | 3/110 |
| 21-74 | Илья Кочнев | 0/110 | 0.0% | 1/110 |
| 21-74 | Илья Ливенцев | 0/110 | 0.0% | 4/110 |
| 21-74 | Кирилл Власов | 0/110 | 0.0% | 1/110 |
| 21-74 | Максим Валецкий | 0/110 | 0.0% | 2/110 |
| 21-74 | Максим Котенков | 0/110 | 0.0% | 2/110 |
| 21-74 | Максим Мельников | 0/110 | 0.0% | 19/110 |
| 21-74 | Максим Сафьянов | 0/110 | 0.0% | 2/110 |
| 21-74 | Маргарита Перова | 0/110 | 0.0% | 1/110 |
| 21-74 | Михаил Мятов | 0/110 | 0.0% | 3/110 |
| 21-74 | Надежда Угленко | 0/110 | 0.0% | 1/110 |
| 21-74 | Наталья Натарова | 0/110 | 0.0% | 1/110 |
| 21-74 | Никита Долгих | 0/110 | 0.0% | 1/110 |
| 21-74 | Николай Львович | 0/110 | 0.0% | 5/110 |
| 21-74 | Николай Романцов | 0/110 | 0.0% | 1/110 |
| 21-74 | Олег Черников | 0/110 | 0.0% | 1/110 |
| 21-74 | Павел Талакин | 0/110 | 0.0% | 1/110 |
| 21-74 | Роман Киреев | 0/110 | 0.0% | 1/110 |
| 21-74 | Роман Ковалев | 0/110 | 0.0% | 2/110 |
| 21-74 | Роман Шалунов | 0/110 | 0.0% | 1/110 |
| 21-74 | Семен Сафронов | 0/110 | 0.0% | 1/110 |
| 21-74 | Сергей Ерофеев | 0/110 | 0.0% | 1/110 |
| 21-74 | Сергей Погодаев | 0/110 | 0.0% | 3/110 |
| 21-74 | Сергей Посконный | 0/110 | 0.0% | 9/110 |
| 21-74 | Сергей Проcветов | 0/110 | 0.0% | 1/110 |
| 21-74 | Сергей Язовский | 0/110 | 0.0% | 10/110 |
| 21-74 | Станислав Татьянченко | 0/110 | 0.0% | 1/110 |
| 21-74 | Станислав Щербаков | 0/110 | 0.0% | 1/110 |
| 21-74 | Юрий Русинов | 0/110 | 0.0% | 4/110 |

## First recommendations by all 11 AI interfaces

No interfaces are excluded. Every first personally selected candidate with a positive count is shown, along with the number of answers lacking a first person. Ties use inclusive position intervals.

| AI interface | Answers | No first person | Leading candidate | Count |
|---|---:|---:|---|---:|
| ChatGPT | 10 | 0 | Алексей Яковлев | 9/10 |
| Perplexity | 10 | 0 | Алексей Яковлев | 9/10 |
| DeepSeek | 10 | 0 | Алексей Яковлев | 7/10 |
| Grok | 10 | 0 | Алексей Яковлев | 7/10 |
| Claude | 10 | 3 | Алексей Яковлев | 4/10 |
| Google Gemini | 10 | 1 | Алексей Яковлев | 5/10 |
| Google AI Mode | 10 | 2 | Алексей Яковлев | 4/10 |
| Google AI Overviews | 10 | 2 | Алексей Яковлев | 5/10 |
| GigaChat | 10 | 0 | Василий Жарков | 3/10 |
| Яндекс с Алисой (поиск) | 10 | 1 | Василий Жарков | 4/10 |
| Алиса AI (чат) | 10 | 1 | Василий Жарков | 4/10 |

### ChatGPT

Ten responses, no first-person candidate: **0**.

1 Алексей Яковлев: 9/10; 2 Артем Фирсов: 1/10.

### Perplexity

Ten responses, no first-person candidate: **0**.

1 Алексей Яковлев: 9/10; 2 Василий Жарков: 1/10.

### DeepSeek

Ten responses, no first-person candidate: **0**.

1 Алексей Яковлев: 7/10; 2 Владимир Назаров: 3/10.

### Grok

Ten responses, no first-person candidate: **0**.

1 Алексей Яковлев: 7/10; 2-4 Василий Жарков: 1/10; 2-4 Вячеслав Савицкий: 1/10; 2-4 Сергей Сивков: 1/10.

### Claude

Ten responses, no first-person candidate: **3**.

1 Алексей Яковлев: 4/10; 2-4 Василий Жарков: 1/10; 2-4 Владимир Назаров: 1/10; 2-4 Дмитрий Севальнев: 1/10.

### Google Gemini

Ten responses, no first-person candidate: **1**.

1 Алексей Яковлев: 5/10; 2 Василий Жарков: 2/10; 3-4 Дмитрий Иглин: 1/10; 3-4 Эмиль Халимов: 1/10.

### Google AI Mode

Ten responses, no first-person candidate: **2**.

1 Алексей Яковлев: 4/10; 2-5 Александр Ознобишин: 1/10; 2-5 Василий Жарков: 1/10; 2-5 Владимир Назаров: 1/10; 2-5 Михаил Шакин: 1/10.

### Google AI Overviews

Ten responses, no first-person candidate: **2**.

1 Алексей Яковлев: 5/10; 2-4 Александр Тригуб: 1/10; 2-4 Евгений Ебаев: 1/10; 2-4 Сергей Купряшкин: 1/10.

### GigaChat

Ten responses, no first-person candidate: **0**.

1 Василий Жарков: 3/10; 2-3 Алексей Яковлев: 2/10; 2-3 Дмитрий Севальнев: 2/10; 4-6 Евгений Ванжула: 1/10; 4-6 Евгений Казанцев: 1/10; 4-6 Максим Фомин: 1/10.

### Яндекс с Алисой (поиск)

Ten responses, no first-person candidate: **1**.

1 Василий Жарков: 4/10; 2 Алексей Яковлев: 3/10; 3-4 Дмитрий Дамарнацкий: 1/10; 3-4 Роман Михальчук: 1/10.

### Алиса AI (чат)

Ten responses, no first-person candidate: **1**.

1 Василий Жарков: 4/10; 2 Алексей Яковлев: 3/10; 3-4 Александр Ожгибесов: 1/10; 3-4 Сергей Сивков: 1/10.

## Individual results for all 74 people

Every individual receives an equivalent evidence record: preliminary first-person count, provider distribution, observed answer IDs and BMR comparison. This is not a biography or a credential check.

### 1. Алексей Яковлев — 58/110 (52.7%)

In the initial FRS labels, **Алексей Яковлев** is the first personally suggested candidate in **58 of 110 answers** (52.7%). The name appears in 75 answers under BMR. First-person selections occur across 11 of 11 interfaces.

**First-person selections by interface:** ChatGPT 9/10; Perplexity 9/10; DeepSeek 7/10; Grok 7/10; Claude 4/10; Google Gemini 5/10; Google AI Mode 4/10; Google AI Overviews 5/10; GigaChat 2/10; Яндекс с Алисой (поиск) 3/10; Алиса AI (чат) 3/10.

**Observation IDs for manual verification:** `chatgpt-Q01`, `chatgpt-Q02`, `chatgpt-Q03`, `chatgpt-Q04`, `chatgpt-Q05`, `chatgpt-Q06`, `chatgpt-Q08`, `chatgpt-Q09`, `chatgpt-Q10`, `claude-Q02`, `claude-Q08`, `claude-Q09`, `claude-Q10`, `perplexity-Q01`, `perplexity-Q02`, `perplexity-Q03`, `perplexity-Q04`, `perplexity-Q05`, `perplexity-Q06`, `perplexity-Q08`, `perplexity-Q09`, `perplexity-Q10`, `deepseek-Q01`, `deepseek-Q02`, `deepseek-Q03`, `deepseek-Q04`, `deepseek-Q05`, `deepseek-Q08`, `deepseek-Q09`, `grok-Q01`, `grok-Q02`, `grok-Q03`, `grok-Q05`, `grok-Q06`, `grok-Q07`, `grok-Q08`, `gemini-Q01`, `gemini-Q02`, `gemini-Q05`, `gemini-Q08`, `gemini-Q10`, `google_ai_mode-Q01`, `google_ai_mode-Q08`, `google_ai_mode-Q09`, `google_ai_mode-Q10`, `google_ai_overview-Q01`, `google_ai_overview-Q04`, `google_ai_overview-Q07`, `google_ai_overview-Q09`, `google_ai_overview-Q10`, `gigachat-Q08`, `gigachat-Q09`, `yandex_alice-Q01`, `yandex_alice-Q02`, `yandex_alice-Q08`, `alice_chat-Q01`, `alice_chat-Q02`, `alice_chat-Q08`.

### 2. Василий Жарков — 17/110 (15.5%)

In the initial FRS labels, **Василий Жарков** is the first personally suggested candidate in **17 of 110 answers** (15.5%). The name appears in 45 answers under BMR. First-person selections occur across 8 of 11 interfaces.

**First-person selections by interface:** Perplexity 1/10; Grok 1/10; Claude 1/10; Google Gemini 2/10; Google AI Mode 1/10; GigaChat 3/10; Яндекс с Алисой (поиск) 4/10; Алиса AI (чат) 4/10.

**Observation IDs for manual verification:** `claude-Q04`, `perplexity-Q07`, `grok-Q04`, `gemini-Q03`, `gemini-Q04`, `google_ai_mode-Q04`, `gigachat-Q03`, `gigachat-Q04`, `gigachat-Q07`, `yandex_alice-Q03`, `yandex_alice-Q04`, `yandex_alice-Q05`, `yandex_alice-Q07`, `alice_chat-Q03`, `alice_chat-Q04`, `alice_chat-Q07`, `alice_chat-Q10`.

### 3. Владимир Назаров — 5/110 (4.5%)

In the initial FRS labels, **Владимир Назаров** is the first personally suggested candidate in **5 of 110 answers** (4.5%). The name appears in 32 answers under BMR. First-person selections occur across 3 of 11 interfaces.

**First-person selections by interface:** DeepSeek 3/10; Claude 1/10; Google AI Mode 1/10.

**Observation IDs for manual verification:** `claude-Q07`, `deepseek-Q06`, `deepseek-Q07`, `deepseek-Q10`, `google_ai_mode-Q05`.

### 4. Дмитрий Севальнев — 3/110 (2.7%)

In the initial FRS labels, **Дмитрий Севальнев** is the first personally suggested candidate in **3 of 110 answers** (2.7%). The name appears in 27 answers under BMR. First-person selections occur across 2 of 11 interfaces.

**First-person selections by interface:** Claude 1/10; GigaChat 2/10.

**Observation IDs for manual verification:** `claude-Q01`, `gigachat-Q01`, `gigachat-Q05`.

### 5. Сергей Сивков — 2/110 (1.8%)

In the initial FRS labels, **Сергей Сивков** is the first personally suggested candidate in **2 of 110 answers** (1.8%). The name appears in 9 answers under BMR. First-person selections occur across 2 of 11 interfaces.

**First-person selections by interface:** Grok 1/10; Алиса AI (чат) 1/10.

**Observation IDs for manual verification:** `grok-Q09`, `alice_chat-Q05`.

### 6-20. Александр Ожгибесов — 1/110 (0.9%)

In the initial FRS labels, **Александр Ожгибесов** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 1 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Алиса AI (чат) 1/10.

**Observation IDs for manual verification:** `alice_chat-Q09`.

### 6-20. Александр Ознобишин — 1/110 (0.9%)

In the initial FRS labels, **Александр Ознобишин** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 13 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Google AI Mode 1/10.

**Observation IDs for manual verification:** `google_ai_mode-Q03`.

### 6-20. Александр Тригуб — 1/110 (0.9%)

In the initial FRS labels, **Александр Тригуб** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 25 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Google AI Overviews 1/10.

**Observation IDs for manual verification:** `google_ai_overview-Q08`.

### 6-20. Артем Фирсов — 1/110 (0.9%)

In the initial FRS labels, **Артем Фирсов** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 1 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** ChatGPT 1/10.

**Observation IDs for manual verification:** `chatgpt-Q07`.

### 6-20. Вячеслав Савицкий — 1/110 (0.9%)

In the initial FRS labels, **Вячеслав Савицкий** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 14 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Grok 1/10.

**Observation IDs for manual verification:** `grok-Q10`.

### 6-20. Дмитрий Дамарнацкий — 1/110 (0.9%)

In the initial FRS labels, **Дмитрий Дамарнацкий** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 4 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Яндекс с Алисой (поиск) 1/10.

**Observation IDs for manual verification:** `yandex_alice-Q10`.

### 6-20. Дмитрий Иглин — 1/110 (0.9%)

In the initial FRS labels, **Дмитрий Иглин** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 1 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Google Gemini 1/10.

**Observation IDs for manual verification:** `gemini-Q09`.

### 6-20. Евгений Ванжула — 1/110 (0.9%)

In the initial FRS labels, **Евгений Ванжула** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 2 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** GigaChat 1/10.

**Observation IDs for manual verification:** `gigachat-Q10`.

### 6-20. Евгений Ебаев — 1/110 (0.9%)

In the initial FRS labels, **Евгений Ебаев** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 1 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Google AI Overviews 1/10.

**Observation IDs for manual verification:** `google_ai_overview-Q03`.

### 6-20. Евгений Казанцев — 1/110 (0.9%)

In the initial FRS labels, **Евгений Казанцев** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 1 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** GigaChat 1/10.

**Observation IDs for manual verification:** `gigachat-Q06`.

### 6-20. Максим Фомин — 1/110 (0.9%)

In the initial FRS labels, **Максим Фомин** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 16 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** GigaChat 1/10.

**Observation IDs for manual verification:** `gigachat-Q02`.

### 6-20. Михаил Шакин — 1/110 (0.9%)

In the initial FRS labels, **Михаил Шакин** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 1 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Google AI Mode 1/10.

**Observation IDs for manual verification:** `google_ai_mode-Q07`.

### 6-20. Роман Михальчук — 1/110 (0.9%)

In the initial FRS labels, **Роман Михальчук** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 1 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Яндекс с Алисой (поиск) 1/10.

**Observation IDs for manual verification:** `yandex_alice-Q09`.

### 6-20. Сергей Купряшкин — 1/110 (0.9%)

In the initial FRS labels, **Сергей Купряшкин** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 1 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Google AI Overviews 1/10.

**Observation IDs for manual verification:** `google_ai_overview-Q02`.

### 6-20. Эмиль Халимов — 1/110 (0.9%)

In the initial FRS labels, **Эмиль Халимов** is the first personally suggested candidate in **1 of 110 answers** (0.9%). The name appears in 1 answers under BMR. First-person selections occur across 1 of 11 interfaces.

**First-person selections by interface:** Google Gemini 1/10.

**Observation IDs for manual verification:** `gemini-Q07`.

### 21-74. Александр Бахарев — 0/110 (0.0%)

In the initial FRS labels, **Александр Бахарев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Александр Лушников — 0/110 (0.0%)

In the initial FRS labels, **Александр Лушников** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Александр Сергеев — 0/110 (0.0%)

In the initial FRS labels, **Александр Сергеев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 6 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Александр Сивков — 0/110 (0.0%)

In the initial FRS labels, **Александр Сивков** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Александр Шерстов — 0/110 (0.0%)

In the initial FRS labels, **Александр Шерстов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Алексей Малков — 0/110 (0.0%)

In the initial FRS labels, **Алексей Малков** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Алексей Чекушин — 0/110 (0.0%)

In the initial FRS labels, **Алексей Чекушин** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Анастасия Акст — 0/110 (0.0%)

In the initial FRS labels, **Анастасия Акст** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 7 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Андрей Бакленев — 0/110 (0.0%)

In the initial FRS labels, **Андрей Бакленев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 2 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Андрей Кружков — 0/110 (0.0%)

In the initial FRS labels, **Андрей Кружков** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Анна Платова — 0/110 (0.0%)

In the initial FRS labels, **Анна Платова** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Артем Маркелов — 0/110 (0.0%)

In the initial FRS labels, **Артем Маркелов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 2 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Валентин Пахомов — 0/110 (0.0%)

In the initial FRS labels, **Валентин Пахомов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Виталий Исаков — 0/110 (0.0%)

In the initial FRS labels, **Виталий Исаков** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 3 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Владимир Малюгин — 0/110 (0.0%)

In the initial FRS labels, **Владимир Малюгин** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 12 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Владимир Синицын — 0/110 (0.0%)

In the initial FRS labels, **Владимир Синицын** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Владислав Пучков — 0/110 (0.0%)

In the initial FRS labels, **Владислав Пучков** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 2 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Глафира Дорохина — 0/110 (0.0%)

In the initial FRS labels, **Глафира Дорохина** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Глеб Андриишин — 0/110 (0.0%)

In the initial FRS labels, **Глеб Андриишин** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Глеб Остроумов — 0/110 (0.0%)

In the initial FRS labels, **Глеб Остроумов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 2 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Денис Ковалев — 0/110 (0.0%)

In the initial FRS labels, **Денис Ковалев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Денис Шубенок — 0/110 (0.0%)

In the initial FRS labels, **Денис Шубенок** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Дмитрий Шеховцев — 0/110 (0.0%)

In the initial FRS labels, **Дмитрий Шеховцев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 4 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Егор Федоров — 0/110 (0.0%)

In the initial FRS labels, **Егор Федоров** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Игорь Ашманов — 0/110 (0.0%)

In the initial FRS labels, **Игорь Ашманов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Илья Карбышев — 0/110 (0.0%)

In the initial FRS labels, **Илья Карбышев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 3 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Илья Кочнев — 0/110 (0.0%)

In the initial FRS labels, **Илья Кочнев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Илья Ливенцев — 0/110 (0.0%)

In the initial FRS labels, **Илья Ливенцев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 4 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Кирилл Власов — 0/110 (0.0%)

In the initial FRS labels, **Кирилл Власов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Максим Валецкий — 0/110 (0.0%)

In the initial FRS labels, **Максим Валецкий** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 2 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Максим Котенков — 0/110 (0.0%)

In the initial FRS labels, **Максим Котенков** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 2 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Максим Мельников — 0/110 (0.0%)

In the initial FRS labels, **Максим Мельников** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 19 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Максим Сафьянов — 0/110 (0.0%)

In the initial FRS labels, **Максим Сафьянов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 2 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Маргарита Перова — 0/110 (0.0%)

In the initial FRS labels, **Маргарита Перова** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Михаил Мятов — 0/110 (0.0%)

In the initial FRS labels, **Михаил Мятов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 3 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Надежда Угленко — 0/110 (0.0%)

In the initial FRS labels, **Надежда Угленко** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Наталья Натарова — 0/110 (0.0%)

In the initial FRS labels, **Наталья Натарова** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Никита Долгих — 0/110 (0.0%)

In the initial FRS labels, **Никита Долгих** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Николай Львович — 0/110 (0.0%)

In the initial FRS labels, **Николай Львович** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 5 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Николай Романцов — 0/110 (0.0%)

In the initial FRS labels, **Николай Романцов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Олег Черников — 0/110 (0.0%)

In the initial FRS labels, **Олег Черников** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Павел Талакин — 0/110 (0.0%)

In the initial FRS labels, **Павел Талакин** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Роман Киреев — 0/110 (0.0%)

In the initial FRS labels, **Роман Киреев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Роман Ковалев — 0/110 (0.0%)

In the initial FRS labels, **Роман Ковалев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 2 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Роман Шалунов — 0/110 (0.0%)

In the initial FRS labels, **Роман Шалунов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Семен Сафронов — 0/110 (0.0%)

In the initial FRS labels, **Семен Сафронов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Сергей Ерофеев — 0/110 (0.0%)

In the initial FRS labels, **Сергей Ерофеев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Сергей Погодаев — 0/110 (0.0%)

In the initial FRS labels, **Сергей Погодаев** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 3 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Сергей Посконный — 0/110 (0.0%)

In the initial FRS labels, **Сергей Посконный** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 9 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Сергей Проcветов — 0/110 (0.0%)

In the initial FRS labels, **Сергей Проcветов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Сергей Язовский — 0/110 (0.0%)

In the initial FRS labels, **Сергей Язовский** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 10 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Станислав Татьянченко — 0/110 (0.0%)

In the initial FRS labels, **Станислав Татьянченко** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Станислав Щербаков — 0/110 (0.0%)

In the initial FRS labels, **Станислав Щербаков** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 1 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.

### 21-74. Юрий Русинов — 0/110 (0.0%)

In the initial FRS labels, **Юрий Русинов** is **not selected first** in any of 110 answers (FRS = 0%). Under BMR, the name appears in 4 answers. Zero FRS does not indicate lack of professional competence.

**First-person selections by interface:** none.

**Observation IDs for manual verification:** no first-person matches.


## Answers without a first personal candidate

The initial coding marks ten answers `NO_PERSON_FIRST`. They may suggest agencies only, cite external rankings or give general advice without choosing an individual. All ten remain in the 110-answer denominator. Observation IDs:

`claude-Q03`, `claude-Q05`, `claude-Q06`, `gemini-Q06`, `google_ai_mode-Q02`, `google_ai_mode-Q06`, `google_ai_overview-Q05`, `google_ai_overview-Q06`, `yandex_alice-Q06`, `alice_chat-Q06`

## Disputed cases and review status

The mechanical audit verified 110 unique observation IDs and links to their matching prompts, 100 named first selections, ten non-person responses and valid name offsets. The calculation reproduces the tables.

**No independent semantic reannotation has been completed.** High-priority cases include Claude Q01, Q02, Q04, Q07 and Q10; Google AI Mode Q05; Google AI Overviews Q07; and Perplexity Q04. In these answers an AI may describe the leader of somebody else's ranking rather than actually recommend that person. [REVIEW_TRIAGE_110.csv](REVIEW_TRIAGE_110.csv) documents all 110 records and 14 priority cases; the independent review fields are intentionally blank. Final shares may change after adjudication.

## Primary evidence and how to reproduce the study

The [110 raw answer texts](https://github.com/IndexResearch-ru/geo-experts-bmr-russia-2026/blob/7eb153e9f711b97544d46a9c6aafe117914989b8/data/observations.jsonl) and [actual prompts](https://github.com/IndexResearch-ru/geo-experts-bmr-russia-2026/blob/7eb153e9f711b97544d46a9c6aafe117914989b8/data/prompts.json) reside in the one canonical BMR dataset, pinned to an **immutable Git commit**.

This repository contains [all 110 initial labels](data/first_recommendation_labels.csv), [complete ranking](RANKING.csv), [74 × 11 interface matrix](BY_PROVIDER_ALL.csv), [machine-readable results](RESULTS.json), [110 answer decision trace](CALCULATION_TRACE.csv), [audit triage](REVIEW_TRIAGE_110.csv), [Python script](reproduce_frs.py) and [input source lock](SOURCE_LOCK.json).

Run Python 3.10+ with no third-party dependencies:

```bash
python3 reproduce_frs.py
```

It downloads the immutable source, checks Git blob hashes, links each decision to the answer and recalculates all 74 people. A passing calculation **does not substitute for independent semantic adjudication**.

## Limitations

1. GAEO selected the question panel and funded the collection, with special attention to personally delivered consulting.
2. Only one answer was collected per provider–prompt combination. Repeated-run variation is unknown.
3. Six prompts differ by extra geographic wording in five interfaces, confounding model comparisons.
4. Previously published material about the participants may have reinforced their appearance in AI answers.
5. The first recommendation distinction is interpretive. Third-party ranking summaries can be mistaken for the model's own advice.
6. FRS describes responses to a selected panel, not real-world competence, client outcomes or market share.
7. The publisher's relationship to Yakovlev and GAEO is disclosed. No independent academic peer review is claimed.

## Frequently asked questions

### What does FRS stand for?

First Recommendation Share, the percentage of all 110 answers in which an individual is the first personally recommended GEO/AEO contractor.

### Why is Yakovlev at 58/110 rather than 75/110?

The 75/110 figure is any mention under BMR. FRS 58/110 is the provisional count of first personal recommendations from the same 110 answers.

### Why are 54 people at zero FRS?

The shared answers mention 74 individuals, but only 20 were initially labeled as first. Zero FRS is not an assessment of expertise.

### What does 21-74 mean?

An interval of 54 people with equal zero FRS. All members share the interval without any intended order among them.

### Why keep ten answers without a named person?

FRS is the chance of seeing a person as the first recommendation across all questions. Excluding ten non-person answers would inflate the share.

### Can I audit the first-person labels?

Yes. Each label has a supporting passage and its offset in the original answer. Semantic review of disputed cases remains pending.

### Who sponsored the measurement?

GAEO paid for BrandFound and selected the prompts. Yakovlev participates in the ranking and is an IndexResearch co-founder.

### Is this the final ranking?

No. Arithmetic is reproducible, but a separate FRS editorial approval and independent reannotation have not yet been completed.

## How to cite

IndexResearch. “Who do AI assistants recommend first for GEO promotion in Russia? First Recommendation Share (FRS) across 110 answers, 30 October 2026.” Draft version 0.9.0 with GAEO-related-party disclosure. Do not cite the provisional percentages as independently validated findings.

Companion metric using the same sample: [BMR (Brand Mention Rate)](https://github.com/IndexResearch-ru/geo-experts-bmr-russia-2026).
