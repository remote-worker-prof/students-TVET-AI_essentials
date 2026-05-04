# 03. Шаблоны A1/A2/A3 (обезличенные)

> Историческое имя файла сохранено для совместимости ссылок.

---

## Назначение файла
Файл содержит краткие унифицированные шаблоны артефактов.  
Единый формат необходим для сопоставимости версий и упрощения проверки.

---

## Переходная логика
`A1` задает входные параметры, `A2` разворачивает содержание, `A3` фиксирует маршрутизацию.  
Шаблоны ниже сохраняют эту логику без изменения структуры полей.

---

## A1

```text
discipline:
topic:
audience:
learning_goal:
pretest_6q:
answer_key:
score:
assigned_level:
```

---

## A2

```text
level: basic|standard|advanced
theory:
practice_block:
checkpoint_test:
checkpoint_key:
criteria:
teacher_notes:
```

---

## A3

```text
flow_steps:
field_mapping:
routing_rules(2/4/6):
run_evidence:
result_log:
```

---

## Минимальный состав `result_log`
`student_id`, `discipline`, `topic`, `score`, `assigned_level`, `material_link`, `timestamp`.
