# ID Conventions

## Рабочая страна первого playable slice

Страна: [[Данцигская Бобриная Автономия]]

Рабочий тег: `DZG`

## Основные правила

- Игровые ID пишутся только латиницей.
- Кириллица в игровых ID запрещена.
- Названия файлов, event namespace, idea ID, focus ID и decision ID должны быть стабильными.
- Каждый новый ID при переносе в `hoi4_mod/` должен иметь русскую локализацию.
- Лорные названия могут быть русскими, но технические ID — только английские.

## Префиксы

Для первого playable slice используется префикс `DZG_`:

- Фокусы: `DZG_proclaim_beaver_cooperatives`
- Идеи: `DZG_partisan_movement`
- Решения: `DZG_drink_krotovuha`
- Dynamic modifiers или scripted variables при необходимости могут использовать нижний регистр: `danzig_alexander_paranoia`

## Event namespace

Namespace: `br_danzig`

Пример:

- `br_danzig.1`
- `br_danzig.2`
- `br_danzig.3`

## GFX ID

- Портреты: `GFX_portrait_DZG_alexander_kurva`
- Фокусы: `GFX_goal_DZG_proclaim_beaver_cooperatives`
- Идеи: `GFX_idea_DZG_partisan_movement`

## Локализация

При переносе в `hoi4_mod/` каждый ID должен получить русскую локализацию:

- название;
- описание;
- tooltip, если эффект неочевиден;
- event title и desc для событий;
- названия вариантов ответа.

## Запреты

- Не использовать пробелы в ID.
- Не использовать кириллицу в ID.
- Не менять уже использованный ID без записи в [[99_DECISIONS_LOG]].
- Не смешивать стиль `danzig_` и `DZG_` внутри одной категории: для видимых страновых объектов использовать `DZG_`, для внутренних шкал можно `danzig_`.

