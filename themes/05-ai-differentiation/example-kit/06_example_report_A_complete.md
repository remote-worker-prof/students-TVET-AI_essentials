# 06. Пример полного отчета части A

---

## A1 (пример)

```text
discipline: биология
topic: дыхательная система человека (базовые функции)
audience: 1 курс СПО
learning_goal: студент объясняет путь воздуха и роль газообмена

pretest_6q:
1) Где происходит газообмен?
2) Какова роль альвеол?
3) Какая последовательность прохождения воздуха верна?
4) Почему при поверхностном дыхании снижается эффективность?
5) Укажите типичную ошибку в объяснении дыхания.
6) Как связаны частота дыхания и физическая нагрузка?

answer_key:
1) альвеолы
2) обмен O2/CO2
3) носовая полость -> гортань -> трахея -> бронхи -> легкие
4) уменьшается вентиляция альвеол
5) путаница между вдохом и газообменом
6) частота повышается

score: 4/6
assigned_level: standard
```

---

## A2 (фрагмент примера)

```text
level: basic
theory: краткое объяснение пути воздуха с опорной схемой.
practice_block: 2 задания по распознаванию органов + 1 задание по последовательности.
checkpoint_test: 3 коротких вопроса на понимание терминов.
checkpoint_key: 1B, 2A, 3C.
criteria: верность терминов, правильная последовательность.
teacher_notes: дать подсказку-схему перед практикой.
```

```text
level: standard
theory: объяснение механики вдоха/выдоха и роли диафрагмы.
practice_block: 2 задания на применение + 1 задание на объяснение причины ошибки.
checkpoint_test: 3 вопроса с коротким ответом.
checkpoint_key: эталонные ответы в 1-2 фразах.
criteria: корректность причинно-следственных связей.
teacher_notes: просить аргументацию, не только термин.
```

```text
level: advanced
theory: сравнение нормального и нарушенного дыхания на клиническом примере.
practice_block: анализ кейса, выявление ошибки в объяснении, перенос в новую ситуацию.
checkpoint_test: мини-кейс из 2 вопросов.
checkpoint_key: шаги анализа + эталон вывода.
criteria: перенос, точность терминов, обоснование.
teacher_notes: задавать уточняющие вопросы на причину ошибки.
```

---

## A3 (пример)

```text
flow_steps:
1) ответ из Yandex Forms
2) передача в Albato
3) подсчет score
4) назначение assigned_level
5) запись строки в Google Sheets
6) выдача material_link

field_mapping:
discipline -> discipline
topic -> topic
score -> score
assigned_level -> assigned_level
material_link -> material_link

routing_rules(2/4/6):
0-2 -> basic
3-4 -> standard
5-6 -> advanced
```

### run_evidence (пример)
1. Кейс `2/6`: запись в Sheets с `assigned_level=basic`.
2. Кейс `4/6`: запись в Sheets с `assigned_level=standard`.
3. Кейс `6/6`: запись в Sheets с `assigned_level=advanced`.

### result_log (пример)

| student_id | discipline | topic | score | assigned_level | material_link | timestamp |
|---|---|---|---|---|---|---|
| st-001 | биология | дыхательная система | 2 | basic | /materials/basic | 2026-05-01T09:10:00 |
| st-002 | биология | дыхательная система | 4 | standard | /materials/standard | 2026-05-01T09:12:00 |
| st-003 | биология | дыхательная система | 6 | advanced | /materials/advanced | 2026-05-01T09:14:00 |
