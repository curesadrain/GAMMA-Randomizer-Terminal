# GAMMA Randomizer Terminal

Placeable hideout terminal for **S.T.A.L.K.E.R. Anomaly / G.A.M.M.A.** designed for stash scanning, random gear selection, and numeric rolls.

[English](#english) • [Українська](#українська) • [Русский](#русский)

---

## English

### Overview

**GAMMA Randomizer Terminal** is an interactive placeable gadget for Hideout Furniture that scans nearby player stashes and storage containers to randomly pick armor, helmets, and weapons, or roll arbitrary numbers directly inside your safehouse.

Uses a dedicated laptop prop visual model (`dynamics\\equipments\\trade\\prop_laptop.ogf`) and integrates seamlessly into the Hideout Furniture interaction system with a custom standalone UI dialog.

### Key Features

- **Stash Scanner:** Automatically scans nearby `inventory_box` containers within configurable radii (**1m / 3m / 5m / 10m / 15m**).
- **Armor Mode:** Classifies scanned gear into Light, Medium, Heavy, Exoskeletons, and Helmets. Features single-category inspection and one-click random pick across all or selected categories.
- **Weapon Mode:** Categorizes scanned firearms into Pistols, SMGs, Shotguns, Rifles (assault & machine guns), and Sniper Rifles.
- **Live Icon Preview:** Interactive item list on the left with instant in-game item texture/icon preview, section name, and source storage on the right.
- **Number Generator:** Dedicated RNG tab with custom configurable minimum and maximum ranges.
- **Pure Modular DLTX:** Non-destructive configuration injection (`items_armor_randomizer_terminal.ltx` and `mod_craft_armor_randomizer_terminal.ltx`) without overwriting base game or third-party gadget configs.
- **Full Trilingual Support:** English, Ukrainian, and Russian localizations included out of the box.

### Requirements

- [S.T.A.L.K.E.R. Anomaly](https://www.moddb.com/mods/stalker-anomaly) (1.5.1 / 1.5.2) with DLTX
- [G.A.M.M.A.](https://discord.gg/stalker-gamma)
- [Gadgets for Hideout Furniture](https://www.moddb.com/mods/stalker-anomaly) by DoktorDauerfeuer & Hideout Furniture by Aoldri

### Crafting Recipe

Craftable at any Tier 3 Workbench via Workshop Menu:
- **Recipe:** 1x Broken Detector + 2x Capacitors + 2x Copper Wire + 2x Metal Scrap

### Installation

1. Download `GAMMA_Randomizer_Terminal_v0.5.zip` from [Releases](https://github.com/curesadrain/GAMMA-Randomizer-Terminal/releases).
2. Install via **Mod Organizer 2** (*Install a new mod from an archive*).
3. Position it **below** `Gadgets for Hideout Furniture - DoktorDauerfeuer` in your MO2 left panel.
4. Enable the mod and launch the game.

### Changelog

- **v0.5:** Added Weapon scanning tab (`w_pistol`, `w_smg`, `w_shotgun`, `w_rifle`, `w_sniper`), tab memory between sessions, dedicated category roll buttons, and modular DLTX separation.
- **v0.4:** Added interactive item icon preview panel with support for custom texture atlases.
- **v0.3:** Resolved CUI3tButton text rendering crash during modal UI initialization.

### Credits

- **Sorano ([curesadrain](https://github.com/curesadrain))** — Logic, UI scripting, DLTX configs, localization, and packaging.
- **DoktorDauerfeuer** — Original Gadgets for Hideout Furniture.
- **Aoldri** — Hideout Furniture framework.

---

## Українська

### Огляд

**GAMMA Randomizer Terminal** — це інтерактивний термінал для системи меблів схованки (Hideout Furniture), який сканує найближчі ящики та схованки гравця для випадкового вибору спорядження, шоломів, зброї або генерації випадкових чисел.

Використовує візуальну модель ноутбука (`prop_laptop.ogf`) і повноцінно інтегрується в систему взаємодії Hideout Furniture зі власним кастомним графічним інтерфейсом.

### Основні можливості

- **Сканер схованок:** Автоматично опитує контейнери `inventory_box` навколо термінала в радіусі **1 / 3 / 5 / 10 / 15 метрів**.
- **Режим «БРОНЯ»:** Сортує знайдене спорядження за класами: легка, середня, важка броня, екзоскелети та шоломи. Підтримує вибір випадкового предмета з усіх або всередині обраної категорії.
- **Режим «ЗБРОЯ»:** Розподіляє зброю за категоріями: пістолети, пістолети-кулемети, рушниці/дробовики, штурмові гвинтівки та снайперські гвинтівки.
- **Попередній перегляд іконок:** Список знайдених предметів ліворуч та інтерактивна панель праворуч із відображенням ігрової іконки, назви та контейнера, де лежить предмет.
- **Генератор чисел:** Окремий режим випадкових чисел із гнучким діапазоном значень («Від» та «До»).
- **Чистий модульний DLTX:** Безпечне підключення без перезапису файлів оригінальних аддонів чи бази GAMMA.
- **Повна тримовна локалізація:** Англійська, українська та російська мови.

### Вимоги

- S.T.A.L.K.E.R. Anomaly 1.5.1/1.5.2 + DLTX
- Модпак G.A.M.M.A.
- Аддон *Gadgets for Hideout Furniture* (DoktorDauerfeuer) та *Hideout Furniture* (Aoldri)

### Крафт

Виготовляється на верстаті (базові набори №3):
- 1x Зламаний детектор + 2x Конденсатори + 2x Мідний дріт + 2x Металобрухт

### Встановлення

1. Завантажте `GAMMA_Randomizer_Terminal_v0.5.zip` зі сторінки [Releases](https://github.com/curesadrain/GAMMA-Randomizer-Terminal/releases).
2. Встановіть через **Mod Organizer 2**.
3. Розташуйте в лівому списку MO2 **нижче** за мод `Gadgets for Hideout Furniture - DoktorDauerfeuer`.
4. Активуйте мод і запустіть гру.

---

## Русский

### Описание

**GAMMA Randomizer Terminal** — размещаемый гаджет для Hideout Furniture, который сканирует ящики и контейнеры вокруг и случайным образом выбирает экипировку, шлемы, оружие или генерирует случайные числа прямо в убежище.

Использует модель ноутбука (`prop_laptop.ogf`), взаимодействует через штатную систему Hideout Furniture и открывает собственный графический интерфейс.

### Возможности

- **Сканер хранилищ:** Сканирует только контейнеры `inventory_box` вокруг терминала с выбором радиуса (**1 / 3 / 5 / 10 / 15 м**).
- **Режим «БРОНЯ»:** Категоризация: лёгкая, средняя, тяжёлая, экзоскелеты, шлемы. Выбор случайного предмета из всех найденных или внутри выбранной категории.
- **Режим «ОРУЖИЕ»:** Категории: пистолеты, пистолеты-пулемёты, дробовики, винтовки (автоматы и пулемёты), снайперские винтовки.
- **Панель предпросмотра иконок:** Клик по строке в списке выводит игровую инвентарную иконку, название предмета и контейнер, в котором он лежит.
- **Режим «ЧИСЛО»:** Быстрый генератор случайных чисел в заданном диапазоне («От» и «До»).
- **Чистый модульный DLTX:** Не перетирает оригинальный файл предметов DoktorDauerfeuer, подключаясь через автономные конфиги.
- **Трёхъязычная локализация:** В комплекте переводы на английский, украинский и русский языки.

### Требования

- S.T.A.L.K.E.R. Anomaly 1.5.1 / 1.5.2 + DLTX
- Модпак G.A.M.M.A.
- Аддон *Gadgets for Hideout Furniture* (DoktorDauerfeuer) и *Hideout Furniture* (Aoldri)

### Крафт

Верстак (набор инструментов №3):
- 1x Сломанный детектор + 2x Конденсаторы + 2x Медная проволока + 2x Металлолом

### Установка

1. Скачайте `GAMMA_Randomizer_Terminal_v0.5.zip` из [Releases](https://github.com/curesadrain/GAMMA-Randomizer-Terminal/releases).
2. Установите через **Mod Organizer 2**.
3. Расположите в левой панели MO2 **ниже** аддона `Gadgets for Hideout Furniture - DoktorDauerfeuer`.
4. Активируйте мод и запустите игру.
