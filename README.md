# naturalist-parser
Утилита для скачивания изображений дикой природы с сайта [**INaturalist**](https://www.inaturalist.org/).

По умолчанию программа загружает фотографии снежных барсов по ссылкам из файла `observations.csv`, но вы можете заменить его на свой собственный, скачав таблицу аналогичного формата с *INaturalist*.

Все фотографии сохраняются под своими UUID в папку `images/`.
## Развертывание и запуск
> [!NOTE]
> Предполагается, что у вас уже установлен пакетный менеджер `uv`, а также система контроля версий `git`.
1. Клонируем репозиторий
```bash
git clone https://github.com/Kakoy-Nikakoy-Corp/naturalist-parser.git
cd naturalist-parser
```
2. Устанавливаем зависимости
```bash
uv sync
```
3. Запускаем скрипт
```bash
uv run main.py
```

***by ubiquiste, 2026*** 👾
