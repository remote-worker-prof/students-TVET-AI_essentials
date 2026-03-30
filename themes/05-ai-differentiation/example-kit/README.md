# 📦 Пакет блока A: полный маршрут и пример отчёта

> Начинайте с [01_quick_start_A.md](01_quick_start_A.md).

---

## 🎯 Цель пакета
Вы получаете самодостаточный набор материалов для выполнения **обязательной части A (A-core)**: от входной проверки подготовки (diagnostic level check) до сравнения двух контуров моделей и итогового решения по качеству.

Логика пакета опирается на прозрачную постановку задачи и проверяемый результат: цель, действия, критерии, артефакты [1], [3]. Для устойчивой доступности используются разные формы представления и проверки материала [2].

---

## 🧭 Маршрут работы
1. Пройдите быстрый запуск в [01_quick_start_A.md](01_quick_start_A.md).
2. Выполните входную проверку и назначьте стартовый уровень по [02_inputs_and_level_assignment.md](02_inputs_and_level_assignment.md).
3. Возьмите чистовые шаблоны Таблиц 1–5 из [03_templates_tables_1_5.md](03_templates_tables_1_5.md).
4. Проведите генерацию и доработку материалов по протоколу из [04_prompt_and_evaluation_protocol.md](04_prompt_and_evaluation_protocol.md).
5. Проверьте комплект через критерии качества и состав сдачи в [05_submission_and_quality_gate.md](05_submission_and_quality_gate.md).
6. Сверьтесь с полностью заполненным сквозным примером в [06_example_report_A_complete.md](06_example_report_A_complete.md).

---

## 🧱 Что входит в полный комплект каждого уровня
Для каждого уровня `basic`, `standard`, `advanced` вы создаете:
1. Теорию: объяснение, пример, опорные понятия.
2. Практику: 3 задания, ожидаемые ответы, критерии проверки.
3. Тест: 6 вопросов.
4. Правильные ответы теста.
5. Проходной балл (минимум правильных ответов).
6. Ошибку для разбора (в учебном примере) и образец корректного исправления.

`Ошибка для разбора` - элемент учебного содержания, а не статистика ошибок группы.

---

## 🧪 Два порядка проверки
- **Базовый порядок проверки в чате (Manual Chat Workflow)**: обязателен и достаточен.
- **Расширенный автоматизированный порядок проверки (Automation Workflow)**: `Yandex Forms -> Albato -> GigaChat -> Google Sheets`, опционален.

Разделение на минимум и расширение снижает лишнюю нагрузку и помогает удерживать фокус на качестве материалов [4], [5].

---

## 📑 Что должно получиться на выходе
1. Таблица 1: входная проверка + матрица уровней.
2. Таблицы 3–5: полный комплект `basic`, `standard`, `advanced`.
3. Таблица 2: сравнение локального и российского облачного контуров + итоговое решение `принять / доработать / не принимать`.
4. Единый финальный комплект материалов для применения на занятии.

Дополнительное чтение по практикам LLM в образовании доступно в обзорном GitHub-репозитории [12].

---

## 🔎 Источники, на которые опирается пакет
[1] ASCD, Key Elements of Differentiated Instruction (PDF): https://pdo.ascd.org/LMSCourses/PD11OC115M/media/DI-Intro_M4_Reading_Key_Elements.pdf

[2] CAST UDL Guidelines 3.0: https://udlguidelines.cast.org/

[3] Transparent Assignment Design (TILT): https://www.uvm.edu/ctl/transparent-assignment-design-tilt

[4] Cognitive Load, Memory, and Instruction (RIT): https://www.rit.edu/teaching/cognitive-load-memory-and-instruction

[5] Formative assessment technique (BMC, 2024): https://link.springer.com/article/10.1186/s12909-024-06347-5

[6] Ollama API introduction: https://docs.ollama.com/api/introduction

[7] LM Studio REST quickstart: https://lmstudio.ai/docs/developer/rest/quickstart

[8] GigaChat API overview: https://developers.sber.ru/docs/ru/gigachat/api/overview

[9] Yandex Forms create form: https://yandex.ru/support/forms/ru/new-form

[10] Albato integration GigaChat -> Google Sheets: https://albato.com/connect/gigachat-with-googlesheets

[11] Google Sheets API writing samples: https://developers.google.com/workspace/sheets/api/samples/writing

[12] GitHub overview (optional): https://github.com/GeminiLight/awesome-ai-llm4education
