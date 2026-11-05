# FRS — First Recommendation Share: who is named first among Russian GEO specialists in 110 AI responses?

<p align="left"><a href="https://indexresearch.ru/en/geo-experts-frs-russia-2026.html" title="FRS — First Recommendation Share: who is named first among Russian GEO specialists in 110 AI responses?"><img src="https://raw.githubusercontent.com/IndexResearch-ru/IndexResearch-ru.github.io/main/assets/indexresearch-logo-horizontal-safe.svg" width="240" alt="IndexResearch"></a></p>

**What does FRS mean?** *First Recommendation Share* is the metric’s expanded name. In this study, it means the **share of answers in which a specialist is the first named person**, including quotations of third-party rankings. It measures first-name exposure, **not independent endorsement by the AI**.

**Languages:** [Русский](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026) · [English](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026-en) · [中文](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026-cn)

**Publication:** version 1.0.0, 30 October 2026, authorized directly by Alexey Yakovlev as IndexResearch co-founder and ranked participant. No independent scientific peer review or separate disinterested editor approval is claimed.

**FRS (First Recommendation Share)** is used here as the **share of responses in which a person is the first individually named specialist**. The historical acronym is retained for continuity, but its operational meaning is *first name exposure in the answer text*, **not proof that the AI independently endorsed, assessed or recommended that person's services**.

The first recognized full personal name counts, **including quotations of third-party rankings, summaries of articles, criticism, and names of agency leaders**. A skimming reader can encounter names before reading the argument. This is the rationale for the exposure metric, not a claim that real eye movements or reading behavior were measured.

In 110 responses from 11 AI interfaces, **Алексей Яковлев** is the earliest named person in **58 responses (52.7%)**, **Василий Жарков** in **17 (15.5%)**, and **Владимир Назаров** in **5 (4.5%)**. Nine responses contain no dictionary-recognized full personal name; 21 of the 74 recognized individuals appear first at least once.

**Conflict of interest:** GAEO selected the prompts and paid BrandFound for the collection. Alexey Yakovlev co-founded IndexResearch, owns GAEO.ru, and is a ranked participant. IndexResearch is not organizationally independent of him. Previously published rankings and case studies related to the parties may have influenced the AI answers. These findings measure name order, **not the quality of services, market-wide leadership, factual accuracy of quoted rankings, or independent endorsements**.

## Study passport

| Measure | Result |
|---|---:|
| Snapshot date | 2026-10-30 |
| AI interfaces | 11 |
| Prompts per interface | 10 |
| Valid responses | 110 |
| Recognized named people | 74 |
| People with positive FRS | 21 |
| People with FRS = 0 | 53 |
| Responses with a first named person | 101 |
| Responses without a recognized personal name | 9 |
| Method | first-visible-person-2026-10-30 |
| Publication approval | PUBLISH — authorized by the interested publisher; no disinterested editor sign-off |

## FRS compared with BMR

**BMR (Brand Mention Rate)** counts responses in which a person's name appears **anywhere**. **FRS** counts responses in which that person is **the earliest recognizable full name**. Alexey Yakovlev has BMR 75/110 (68.2%) and FRS 58/110 (52.7%); Vasily Zharkov has BMR 45/110 (40.9%) and FRS 17/110 (15.5%). Both metrics use **the same 110 empirical responses**, not two independent samples.

## Formula and decision rule

**FRS(p) = 100 × N_first(p) / 110**, where `N_first(p)` counts the distinct responses in which person `p` is named before any other person recognized by the locked 74-person dictionary. Within each AI interface, the denominator is 10.

The algorithm scans the **complete archived `answer_text` from beginning to end**. It finds the earliest match against the exact person-specific patterns in the locked BMR dictionary, regardless of source attribution, evaluative tone, or role within an agency. Company names alone do not earn personal FRS; the earliest person appearing after them can still be counted. If no recognizable full personal name appears, the response is labeled `NO_PERSON_FIRST` and remains in the denominator. Each response contributes 0 or 1 first person, never more.

This is a **text-order proxy**. It does not model visual presentation, positive sentiment, attention, clicks or purchase intent. The method was revised **after** the answers had already been collected. The complete [Russian methodology](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/METHODOLOGY.md) and its source code document the calculation.

## Complete FRS ranking of all 74 individuals

The 53 people with zero first appearances remain included. Equal integer counts share an inclusive rank interval: `6-21` for 16 people with one answer, `22-74` for 53 people with none.

| Position | Person (source spelling) | First appearances | FRS | BMR mentions |
|---:|---|---:|---:|---:|
| 1 | Алексей Яковлев | 58/110 | 52.7% | 75/110 |
| 2 | Василий Жарков | 17/110 | 15.5% | 45/110 |
| 3 | Владимир Назаров | 5/110 | 4.5% | 32/110 |
| 4 | Дмитрий Севальнев | 3/110 | 2.7% | 27/110 |
| 5 | Сергей Сивков | 2/110 | 1.8% | 9/110 |
| 6-21 | Александр Ожгибесов | 1/110 | 0.9% | 1/110 |
| 6-21 | Александр Ознобишин | 1/110 | 0.9% | 13/110 |
| 6-21 | Александр Тригуб | 1/110 | 0.9% | 25/110 |
| 6-21 | Артем Фирсов | 1/110 | 0.9% | 1/110 |
| 6-21 | Вячеслав Савицкий | 1/110 | 0.9% | 14/110 |
| 6-21 | Денис Шубенок | 1/110 | 0.9% | 1/110 |
| 6-21 | Дмитрий Дамарнацкий | 1/110 | 0.9% | 4/110 |
| 6-21 | Дмитрий Иглин | 1/110 | 0.9% | 1/110 |
| 6-21 | Евгений Ванжула | 1/110 | 0.9% | 2/110 |
| 6-21 | Евгений Ебаев | 1/110 | 0.9% | 1/110 |
| 6-21 | Евгений Казанцев | 1/110 | 0.9% | 1/110 |
| 6-21 | Максим Фомин | 1/110 | 0.9% | 16/110 |
| 6-21 | Михаил Шакин | 1/110 | 0.9% | 1/110 |
| 6-21 | Роман Михальчук | 1/110 | 0.9% | 1/110 |
| 6-21 | Сергей Купряшкин | 1/110 | 0.9% | 1/110 |
| 6-21 | Сергей Посконный | 1/110 | 0.9% | 9/110 |
| 22-74 | Александр Бахарев | 0/110 | 0.0% | 1/110 |
| 22-74 | Александр Лушников | 0/110 | 0.0% | 1/110 |
| 22-74 | Александр Сергеев | 0/110 | 0.0% | 6/110 |
| 22-74 | Александр Сивков | 0/110 | 0.0% | 1/110 |
| 22-74 | Александр Шерстов | 0/110 | 0.0% | 1/110 |
| 22-74 | Алексей Малков | 0/110 | 0.0% | 1/110 |
| 22-74 | Алексей Чекушин | 0/110 | 0.0% | 1/110 |
| 22-74 | Анастасия Акст | 0/110 | 0.0% | 7/110 |
| 22-74 | Андрей Бакленев | 0/110 | 0.0% | 2/110 |
| 22-74 | Андрей Кружков | 0/110 | 0.0% | 1/110 |
| 22-74 | Анна Платова | 0/110 | 0.0% | 1/110 |
| 22-74 | Артем Маркелов | 0/110 | 0.0% | 2/110 |
| 22-74 | Валентин Пахомов | 0/110 | 0.0% | 1/110 |
| 22-74 | Виталий Исаков | 0/110 | 0.0% | 3/110 |
| 22-74 | Владимир Малюгин | 0/110 | 0.0% | 12/110 |
| 22-74 | Владимир Синицын | 0/110 | 0.0% | 1/110 |
| 22-74 | Владислав Пучков | 0/110 | 0.0% | 2/110 |
| 22-74 | Глафира Дорохина | 0/110 | 0.0% | 1/110 |
| 22-74 | Глеб Андриишин | 0/110 | 0.0% | 1/110 |
| 22-74 | Глеб Остроумов | 0/110 | 0.0% | 2/110 |
| 22-74 | Денис Ковалев | 0/110 | 0.0% | 1/110 |
| 22-74 | Дмитрий Шеховцев | 0/110 | 0.0% | 4/110 |
| 22-74 | Егор Федоров | 0/110 | 0.0% | 1/110 |
| 22-74 | Игорь Ашманов | 0/110 | 0.0% | 1/110 |
| 22-74 | Илья Карбышев | 0/110 | 0.0% | 3/110 |
| 22-74 | Илья Кочнев | 0/110 | 0.0% | 1/110 |
| 22-74 | Илья Ливенцев | 0/110 | 0.0% | 4/110 |
| 22-74 | Кирилл Власов | 0/110 | 0.0% | 1/110 |
| 22-74 | Максим Валецкий | 0/110 | 0.0% | 2/110 |
| 22-74 | Максим Котенков | 0/110 | 0.0% | 2/110 |
| 22-74 | Максим Мельников | 0/110 | 0.0% | 19/110 |
| 22-74 | Максим Сафьянов | 0/110 | 0.0% | 2/110 |
| 22-74 | Маргарита Перова | 0/110 | 0.0% | 1/110 |
| 22-74 | Михаил Мятов | 0/110 | 0.0% | 3/110 |
| 22-74 | Надежда Угленко | 0/110 | 0.0% | 1/110 |
| 22-74 | Наталья Натарова | 0/110 | 0.0% | 1/110 |
| 22-74 | Никита Долгих | 0/110 | 0.0% | 1/110 |
| 22-74 | Николай Львович | 0/110 | 0.0% | 5/110 |
| 22-74 | Николай Романцов | 0/110 | 0.0% | 1/110 |
| 22-74 | Олег Черников | 0/110 | 0.0% | 1/110 |
| 22-74 | Павел Талакин | 0/110 | 0.0% | 1/110 |
| 22-74 | Роман Киреев | 0/110 | 0.0% | 1/110 |
| 22-74 | Роман Ковалев | 0/110 | 0.0% | 2/110 |
| 22-74 | Роман Шалунов | 0/110 | 0.0% | 1/110 |
| 22-74 | Семен Сафронов | 0/110 | 0.0% | 1/110 |
| 22-74 | Сергей Ерофеев | 0/110 | 0.0% | 1/110 |
| 22-74 | Сергей Погодаев | 0/110 | 0.0% | 3/110 |
| 22-74 | Сергей Проcветов | 0/110 | 0.0% | 1/110 |
| 22-74 | Сергей Язовский | 0/110 | 0.0% | 10/110 |
| 22-74 | Станислав Татьянченко | 0/110 | 0.0% | 1/110 |
| 22-74 | Станислав Щербаков | 0/110 | 0.0% | 1/110 |
| 22-74 | Эмиль Халимов | 0/110 | 0.0% | 1/110 |
| 22-74 | Юрий Русинов | 0/110 | 0.0% | 4/110 |

## FRS across all 11 AI interfaces

| AI interface | Answers | No person | Most frequent first person | Count |
|---|---:|---:|---|---:|
| ChatGPT | 10 | 0 | Алексей Яковлев | 9/10 |
| Perplexity | 10 | 0 | Алексей Яковлев | 9/10 |
| DeepSeek | 10 | 0 | Алексей Яковлев | 6/10 |
| Grok | 10 | 0 | Алексей Яковлев | 7/10 |
| Claude | 10 | 2 | Алексей Яковлев | 5/10 |
| Google Gemini | 10 | 1 | Алексей Яковлев | 5/10 |
| Google AI Mode | 10 | 2 | Алексей Яковлев | 4/10 |
| Google AI Overviews | 10 | 2 | Алексей Яковлев | 5/10 |
| GigaChat | 10 | 0 | Василий Жарков | 3/10 |
| Яндекс с Алисой (поиск) | 10 | 1 | Василий Жарков | 4/10 |
| Алиса AI (чат) | 10 | 1 | Василий Жарков | 4/10 |

### Full within-interface distributions

**ChatGPT:** 10 answers have a named person and 0 do not. 1: Алексей Яковлев, 9/10; 2: Артем Фирсов, 1/10.

**Perplexity:** 10 answers have a named person and 0 do not. 1: Алексей Яковлев, 9/10; 2: Василий Жарков, 1/10.

**DeepSeek:** 10 answers have a named person and 0 do not. 1: Алексей Яковлев, 6/10; 2: Владимир Назаров, 3/10; 3: Сергей Посконный, 1/10.

**Grok:** 10 answers have a named person and 0 do not. 1: Алексей Яковлев, 7/10; 2-4: Василий Жарков, 1/10; 2-4: Вячеслав Савицкий, 1/10; 2-4: Сергей Сивков, 1/10.

**Claude:** 8 answers have a named person and 2 do not. 1: Алексей Яковлев, 5/10; 2-4: Василий Жарков, 1/10; 2-4: Владимир Назаров, 1/10; 2-4: Дмитрий Севальнев, 1/10.

**Google Gemini:** 9 answers have a named person and 1 do not. 1: Алексей Яковлев, 5/10; 2: Василий Жарков, 2/10; 3-4: Денис Шубенок, 1/10; 3-4: Дмитрий Иглин, 1/10.

**Google AI Mode:** 8 answers have a named person and 2 do not. 1: Алексей Яковлев, 4/10; 2-5: Александр Ознобишин, 1/10; 2-5: Василий Жарков, 1/10; 2-5: Владимир Назаров, 1/10; 2-5: Михаил Шакин, 1/10.

**Google AI Overviews:** 8 answers have a named person and 2 do not. 1: Алексей Яковлев, 5/10; 2-4: Александр Тригуб, 1/10; 2-4: Евгений Ебаев, 1/10; 2-4: Сергей Купряшкин, 1/10.

**GigaChat:** 10 answers have a named person and 0 do not. 1: Василий Жарков, 3/10; 2-3: Алексей Яковлев, 2/10; 2-3: Дмитрий Севальнев, 2/10; 4-6: Евгений Ванжула, 1/10; 4-6: Евгений Казанцев, 1/10; 4-6: Максим Фомин, 1/10.

**Яндекс с Алисой (поиск):** 9 answers have a named person and 1 do not. 1: Василий Жарков, 4/10; 2: Алексей Яковлев, 3/10; 3-4: Дмитрий Дамарнацкий, 1/10; 3-4: Роман Михальчук, 1/10.

**Алиса AI (чат):** 9 answers have a named person and 1 do not. 1: Василий Жарков, 4/10; 2: Алексей Яковлев, 3/10; 3-4: Александр Ожгибесов, 1/10; 3-4: Сергей Сивков, 1/10.


## Individual evidence for all 74 people

Each entry includes first-name exposure, BMR comparison, per-interface distribution, and the exact response IDs. These are observations, not biographical profiles or endorsements.

### 1. Алексей Яковлев — 58/110 (52.7%)

**Алексей Яковлев** is the first recognized personal name in **58 of 110 answers** (52.7%). The name appears in 75 responses under BMR. 

**By interface:** ChatGPT 9/10; Perplexity 9/10; DeepSeek 6/10; Grok 7/10; Claude 5/10; Google Gemini 5/10; Google AI Mode 4/10; Google AI Overviews 5/10; GigaChat 2/10; Яндекс с Алисой (поиск) 3/10; Алиса AI (чат) 3/10.

**Verifiable observation IDs:** `chatgpt-Q01`, `chatgpt-Q02`, `chatgpt-Q03`, `chatgpt-Q04`, `chatgpt-Q05`, `chatgpt-Q06`, `chatgpt-Q08`, `chatgpt-Q09`, `chatgpt-Q10`, `claude-Q02`, `claude-Q05`, `claude-Q08`, `claude-Q09`, `claude-Q10`, `perplexity-Q01`, `perplexity-Q02`, `perplexity-Q03`, `perplexity-Q04`, `perplexity-Q05`, `perplexity-Q06`, `perplexity-Q08`, `perplexity-Q09`, `perplexity-Q10`, `deepseek-Q02`, `deepseek-Q03`, `deepseek-Q04`, `deepseek-Q05`, `deepseek-Q08`, `deepseek-Q09`, `grok-Q01`, `grok-Q02`, `grok-Q03`, `grok-Q05`, `grok-Q06`, `grok-Q07`, `grok-Q08`, `gemini-Q01`, `gemini-Q02`, `gemini-Q05`, `gemini-Q08`, `gemini-Q10`, `google_ai_mode-Q01`, `google_ai_mode-Q08`, `google_ai_mode-Q09`, `google_ai_mode-Q10`, `google_ai_overview-Q01`, `google_ai_overview-Q04`, `google_ai_overview-Q07`, `google_ai_overview-Q09`, `google_ai_overview-Q10`, `gigachat-Q08`, `gigachat-Q09`, `yandex_alice-Q01`, `yandex_alice-Q02`, `yandex_alice-Q08`, `alice_chat-Q01`, `alice_chat-Q02`, `alice_chat-Q08`.

### 2. Василий Жарков — 17/110 (15.5%)

**Василий Жарков** is the first recognized personal name in **17 of 110 answers** (15.5%). The name appears in 45 responses under BMR. 

**By interface:** Perplexity 1/10; Grok 1/10; Claude 1/10; Google Gemini 2/10; Google AI Mode 1/10; GigaChat 3/10; Яндекс с Алисой (поиск) 4/10; Алиса AI (чат) 4/10.

**Verifiable observation IDs:** `claude-Q04`, `perplexity-Q07`, `grok-Q04`, `gemini-Q03`, `gemini-Q04`, `google_ai_mode-Q04`, `gigachat-Q03`, `gigachat-Q04`, `gigachat-Q07`, `yandex_alice-Q03`, `yandex_alice-Q04`, `yandex_alice-Q05`, `yandex_alice-Q07`, `alice_chat-Q03`, `alice_chat-Q04`, `alice_chat-Q07`, `alice_chat-Q10`.

### 3. Владимир Назаров — 5/110 (4.5%)

**Владимир Назаров** is the first recognized personal name in **5 of 110 answers** (4.5%). The name appears in 32 responses under BMR. 

**By interface:** DeepSeek 3/10; Claude 1/10; Google AI Mode 1/10.

**Verifiable observation IDs:** `claude-Q07`, `deepseek-Q06`, `deepseek-Q07`, `deepseek-Q10`, `google_ai_mode-Q05`.

### 4. Дмитрий Севальнев — 3/110 (2.7%)

**Дмитрий Севальнев** is the first recognized personal name in **3 of 110 answers** (2.7%). The name appears in 27 responses under BMR. 

**By interface:** Claude 1/10; GigaChat 2/10.

**Verifiable observation IDs:** `claude-Q01`, `gigachat-Q01`, `gigachat-Q05`.

### 5. Сергей Сивков — 2/110 (1.8%)

**Сергей Сивков** is the first recognized personal name in **2 of 110 answers** (1.8%). The name appears in 9 responses under BMR. 

**By interface:** Grok 1/10; Алиса AI (чат) 1/10.

**Verifiable observation IDs:** `grok-Q09`, `alice_chat-Q05`.

### 6-21. Александр Ожгибесов — 1/110 (0.9%)

**Александр Ожгибесов** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 1 responses under BMR. 

**By interface:** Алиса AI (чат) 1/10.

**Verifiable observation IDs:** `alice_chat-Q09`.

### 6-21. Александр Ознобишин — 1/110 (0.9%)

**Александр Ознобишин** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 13 responses under BMR. 

**By interface:** Google AI Mode 1/10.

**Verifiable observation IDs:** `google_ai_mode-Q03`.

### 6-21. Александр Тригуб — 1/110 (0.9%)

**Александр Тригуб** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 25 responses under BMR. 

**By interface:** Google AI Overviews 1/10.

**Verifiable observation IDs:** `google_ai_overview-Q08`.

### 6-21. Артем Фирсов — 1/110 (0.9%)

**Артем Фирсов** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 1 responses under BMR. 

**By interface:** ChatGPT 1/10.

**Verifiable observation IDs:** `chatgpt-Q07`.

### 6-21. Вячеслав Савицкий — 1/110 (0.9%)

**Вячеслав Савицкий** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 14 responses under BMR. 

**By interface:** Grok 1/10.

**Verifiable observation IDs:** `grok-Q10`.

### 6-21. Денис Шубенок — 1/110 (0.9%)

**Денис Шубенок** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 1 responses under BMR. 

**By interface:** Google Gemini 1/10.

**Verifiable observation IDs:** `gemini-Q07`.

### 6-21. Дмитрий Дамарнацкий — 1/110 (0.9%)

**Дмитрий Дамарнацкий** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 4 responses under BMR. 

**By interface:** Яндекс с Алисой (поиск) 1/10.

**Verifiable observation IDs:** `yandex_alice-Q10`.

### 6-21. Дмитрий Иглин — 1/110 (0.9%)

**Дмитрий Иглин** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 1 responses under BMR. 

**By interface:** Google Gemini 1/10.

**Verifiable observation IDs:** `gemini-Q09`.

### 6-21. Евгений Ванжула — 1/110 (0.9%)

**Евгений Ванжула** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 2 responses under BMR. 

**By interface:** GigaChat 1/10.

**Verifiable observation IDs:** `gigachat-Q10`.

### 6-21. Евгений Ебаев — 1/110 (0.9%)

**Евгений Ебаев** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 1 responses under BMR. 

**By interface:** Google AI Overviews 1/10.

**Verifiable observation IDs:** `google_ai_overview-Q03`.

### 6-21. Евгений Казанцев — 1/110 (0.9%)

**Евгений Казанцев** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 1 responses under BMR. 

**By interface:** GigaChat 1/10.

**Verifiable observation IDs:** `gigachat-Q06`.

### 6-21. Максим Фомин — 1/110 (0.9%)

**Максим Фомин** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 16 responses under BMR. 

**By interface:** GigaChat 1/10.

**Verifiable observation IDs:** `gigachat-Q02`.

### 6-21. Михаил Шакин — 1/110 (0.9%)

**Михаил Шакин** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 1 responses under BMR. 

**By interface:** Google AI Mode 1/10.

**Verifiable observation IDs:** `google_ai_mode-Q07`.

### 6-21. Роман Михальчук — 1/110 (0.9%)

**Роман Михальчук** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 1 responses under BMR. 

**By interface:** Яндекс с Алисой (поиск) 1/10.

**Verifiable observation IDs:** `yandex_alice-Q09`.

### 6-21. Сергей Купряшкин — 1/110 (0.9%)

**Сергей Купряшкин** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 1 responses under BMR. 

**By interface:** Google AI Overviews 1/10.

**Verifiable observation IDs:** `google_ai_overview-Q02`.

### 6-21. Сергей Посконный — 1/110 (0.9%)

**Сергей Посконный** is the first recognized personal name in **1 of 110 answers** (0.9%). The name appears in 9 responses under BMR. 

**By interface:** DeepSeek 1/10.

**Verifiable observation IDs:** `deepseek-Q01`.

### 22-74. Александр Бахарев — 0/110 (0.0%)

**Александр Бахарев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Александр Лушников — 0/110 (0.0%)

**Александр Лушников** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Александр Сергеев — 0/110 (0.0%)

**Александр Сергеев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 6 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Александр Сивков — 0/110 (0.0%)

**Александр Сивков** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Александр Шерстов — 0/110 (0.0%)

**Александр Шерстов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Алексей Малков — 0/110 (0.0%)

**Алексей Малков** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Алексей Чекушин — 0/110 (0.0%)

**Алексей Чекушин** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Анастасия Акст — 0/110 (0.0%)

**Анастасия Акст** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 7 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Андрей Бакленев — 0/110 (0.0%)

**Андрей Бакленев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 2 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Андрей Кружков — 0/110 (0.0%)

**Андрей Кружков** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Анна Платова — 0/110 (0.0%)

**Анна Платова** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Артем Маркелов — 0/110 (0.0%)

**Артем Маркелов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 2 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Валентин Пахомов — 0/110 (0.0%)

**Валентин Пахомов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Виталий Исаков — 0/110 (0.0%)

**Виталий Исаков** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 3 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Владимир Малюгин — 0/110 (0.0%)

**Владимир Малюгин** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 12 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Владимир Синицын — 0/110 (0.0%)

**Владимир Синицын** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Владислав Пучков — 0/110 (0.0%)

**Владислав Пучков** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 2 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Глафира Дорохина — 0/110 (0.0%)

**Глафира Дорохина** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Глеб Андриишин — 0/110 (0.0%)

**Глеб Андриишин** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Глеб Остроумов — 0/110 (0.0%)

**Глеб Остроумов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 2 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Денис Ковалев — 0/110 (0.0%)

**Денис Ковалев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Дмитрий Шеховцев — 0/110 (0.0%)

**Дмитрий Шеховцев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 4 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Егор Федоров — 0/110 (0.0%)

**Егор Федоров** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Игорь Ашманов — 0/110 (0.0%)

**Игорь Ашманов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Илья Карбышев — 0/110 (0.0%)

**Илья Карбышев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 3 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Илья Кочнев — 0/110 (0.0%)

**Илья Кочнев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Илья Ливенцев — 0/110 (0.0%)

**Илья Ливенцев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 4 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Кирилл Власов — 0/110 (0.0%)

**Кирилл Власов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Максим Валецкий — 0/110 (0.0%)

**Максим Валецкий** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 2 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Максим Котенков — 0/110 (0.0%)

**Максим Котенков** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 2 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Максим Мельников — 0/110 (0.0%)

**Максим Мельников** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 19 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Максим Сафьянов — 0/110 (0.0%)

**Максим Сафьянов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 2 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Маргарита Перова — 0/110 (0.0%)

**Маргарита Перова** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Михаил Мятов — 0/110 (0.0%)

**Михаил Мятов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 3 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Надежда Угленко — 0/110 (0.0%)

**Надежда Угленко** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Наталья Натарова — 0/110 (0.0%)

**Наталья Натарова** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Никита Долгих — 0/110 (0.0%)

**Никита Долгих** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Николай Львович — 0/110 (0.0%)

**Николай Львович** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 5 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Николай Романцов — 0/110 (0.0%)

**Николай Романцов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Олег Черников — 0/110 (0.0%)

**Олег Черников** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Павел Талакин — 0/110 (0.0%)

**Павел Талакин** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Роман Киреев — 0/110 (0.0%)

**Роман Киреев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Роман Ковалев — 0/110 (0.0%)

**Роман Ковалев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 2 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Роман Шалунов — 0/110 (0.0%)

**Роман Шалунов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Семен Сафронов — 0/110 (0.0%)

**Семен Сафронов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Сергей Ерофеев — 0/110 (0.0%)

**Сергей Ерофеев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Сергей Погодаев — 0/110 (0.0%)

**Сергей Погодаев** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 3 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Сергей Проcветов — 0/110 (0.0%)

**Сергей Проcветов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Сергей Язовский — 0/110 (0.0%)

**Сергей Язовский** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 10 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Станислав Татьянченко — 0/110 (0.0%)

**Станислав Татьянченко** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Станислав Щербаков — 0/110 (0.0%)

**Станислав Щербаков** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Эмиль Халимов — 0/110 (0.0%)

**Эмиль Халимов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 1 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.

### 22-74. Юрий Русинов — 0/110 (0.0%)

**Юрий Русинов** is the first recognized personal name in **0 of 110 answers** (0.0%). The name appears in 4 responses under BMR. A zero FRS does not indicate lack of expertise or absence from the source answers.

**By interface:** No first appearances.

**Verifiable observation IDs:** None.


## Method change and audit trail

The original v0.9.0 attempted to distinguish the AI's **own recommendation** from quoted third-party lists. That narrower requirement has been rejected: the reader encounters the name either way. A first name counts even when it appears in a quotation, a critical example, or an agency biography.

The uniform mechanical recoding of all 110 answers changed three observations:

| Response | v0.9.0 | First named person in v0.9.1 |
|---|---|---|
| `claude-Q05` | No first person | Алексей Яковлев |
| `deepseek-Q01` | Алексей Яковлев | Сергей Посконный |
| `gemini-Q07` | Эмиль Халимов | Денис Шубенок |

These changes were not hand-picked for the top-ranked person. Poskonny appears early in a critical remark before the recommendations; Shubenok appears earlier as an executive. Both qualify under the **same order-based rule**. The 110 source responses and 74-person dictionary are unchanged.

## Sources and reproducibility

The canonical corpus is [110 pinned full responses](https://github.com/IndexResearch-ru/geo-experts-bmr-russia-2026/blob/7eb153e9f711b97544d46a9c6aafe117914989b8/data/observations.jsonl), using the corresponding [locked recognition dictionary](https://github.com/IndexResearch-ru/geo-experts-bmr-russia-2026/blob/7eb153e9f711b97544d46a9c6aafe117914989b8/data/entity_dictionary.csv).

The [Russian data repository](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026) contains [all 110 labels](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/data/first_recommendation_labels.csv), [RANKING.csv](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/RANKING.csv), [provider matrix](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/BY_PROVIDER_ALL.csv), [RESULTS.json](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/RESULTS.json), [audit differences](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/REVIEW_TRIAGE_110.csv), [Python reproduction script](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/reproduce_frs.py), [methodology](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/METHODOLOGY.md), [QA report](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/QA_REPORT.md), [conflict disclosure](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/CONFLICT_OF_INTEREST.md), and [version history](https://github.com/IndexResearch-ru/geo-experts-first-recommendation-russia-2026/blob/main/CHANGELOG.md). The original v0.9.0 labels remain archived there.

Run `python3 reproduce_frs.py` in the Russian repository to verify locked-source checksums and reconstruct first-name assignments. Reproducibility is **not evidence of scientific peer review, independent model endorsement or real reader attention**.

## Limitations

The panel was selected by an interested party and includes prompts favoring personally managed GEO services. Five interfaces received an additional "in Russia" qualifier in some questions. Each interface/prompt pair has only one recorded answer. Earlier IndexResearch/GAEO material may be echoed in the AI output. The first recognized name is based on archived text order; it is not a professionally validated recommendation or an eye-tracking experiment. Methodology was revised after data collection, and the publisher's relationship with a ranked participant is disclosed.

## Frequently asked questions

### Does FRS mean that an AI independently recommends the person?

**No.** In this release it measures the first recognized name, including third-party rankings, unfavorable remarks and agency descriptions. The historical acronym remains for continuity.

### Why is Yakovlev's FRS 58/110 while his BMR is 75/110?

He appears anywhere in 75 responses (BMR), and before every other recognized person in 58 responses (FRS).

### Why do 53 people have zero FRS?

There are 74 recognized people but only 21 appear first at least once. Zero is not a score of their competence.

### What does 22-74 mean?

Fifty-three people have the same count of zero, so they share a rank interval with no ordering within the tie.

### Why do nine answers without recognized names remain in the denominator?

The denominator is always the full set of 110 recorded answers, preventing inflation of first-name shares.

### Why include third-party rankings?

First exposure is defined by position within the answer text. The model's source and whether it independently agrees do not change which personal name appears first.

### Can the assignments be audited?

Yes. For every response the Russian repository stores the selected name, its character offset, a supporting snippet and the observation ID.

### Is this an independently verified final publication?

**Yes, as version 1.0.0 with publisher authorization by an interested participant.** The calculation is reproducible. No independent academic peer review or separate non-participant editorial approval is claimed.

## Suggested citation

IndexResearch. *Who is named first among Russian GEO specialists across 110 AI answers? First Recommendation Share (FRS), operationalized as first-person name exposure, 30 October 2026.* Version 1.0.0, 30 October 2026. Publisher-authorized observational study; not an independent endorsement ranking.

Related BMR analysis: [Brand Mention Rate in the same 110 answers](https://github.com/IndexResearch-ru/geo-experts-bmr-russia-2026).
