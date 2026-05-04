# 06. Обезличенный пример полного результата A

---

## A1 (шаблон с примером значений)

```text
discipline: <дисциплина>
topic: <узкая тема>
audience: <курс/группа>
learning_goal: <измеримая цель>
pretest_6q: <6 вопросов>
answer_key: <ключ 1..6>
score: 4/6
assigned_level: standard
```

---

## A2 (краткий формат)

```text
level: basic
theory: ...
practice_block: ...
checkpoint_test: ...
checkpoint_key: ...
criteria: ...
teacher_notes: ...
```

```text
level: standard
theory: ...
practice_block: ...
checkpoint_test: ...
checkpoint_key: ...
criteria: ...
teacher_notes: ...
```

```text
level: advanced
theory: ...
practice_block: ...
checkpoint_test: ...
checkpoint_key: ...
criteria: ...
teacher_notes: ...
```

---

## A3 (краткий формат)

```text
flow_steps: Yandex Forms -> Albato -> Google Sheets
field_mapping: discipline/topic/score/assigned_level/material_link
routing_rules(2/4/6): 0-2 basic; 3-4 standard; 5-6 advanced
run_evidence: 3 подтверждения прогонов
result_log: минимум 3 строки
```

### Пример лог-строк

| student_id | discipline | topic | score | assigned_level | material_link | timestamp |
|---|---|---|---|---|---|---|
| st-101 | <disc> | <topic> | 2 | basic | /materials/basic | 2026-05-01T09:00:00 |
| st-102 | <disc> | <topic> | 4 | standard | /materials/standard | 2026-05-01T09:02:00 |
| st-103 | <disc> | <topic> | 6 | advanced | /materials/advanced | 2026-05-01T09:04:00 |
