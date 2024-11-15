<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

# Landmarks Detection
Этот репозиторий содержит код, используемый для обработки набора данных изображений крыльев бабочек с помощью нейронных сетей.

## Установка и настройка программ и пакетов
Процесс установки и настройки программ и пакетов необходимых для работы кода описан в файле `INSTALL.md`.

## Структура проекта

```
├── LICENSE            <- Лицензия с открытым исходным кодом, если она 
│                         выбрана
├── README.md          <- README верхнего уровня для разработчиков, 
│                         использующих этот проект.
├── data
│   ├── external       <- Данные из сторонних источников.
│   ├── interim        <- Промежуточные данные, которые были преобразованы 
│   │                     программой.
│   ├── processed      <- Конечных данных, которые будут использоваться 
│   │                     для обучения и моделирования.
│   └── raw            <- Необработанные исходные данные.
│
│
├── models             <- Обученные модели.
│
├── notebooks          <- Блокноты Jupyter
│
├── references         <- Словари данных, справочники и все другие 
│                         пояснительные материалы.
│
├── reports            <- Генерируемые отчеты в формате HTML, PDF, LaTeX и т.д.
│   └── figures        <- Создаваемые графики и рисунки использующиеся в отчетах.
│
├── test               <- Тесты для исходного кода
│
├── requirements.txt   <- Файл с перечислением пакетов и их версий.
│                         Создать можно с помощью `pip freeze > requirements.txt`.
│
└── landmarks_detection   <- Исходный код проекта.
    │
    ├── __init__.py             <- Делает landmarks_detection модулем Python
    │
    ├── config.py               <- Хранит полезные переменные и конфигурацию
    │
    ├── dataset.py              <- Сценарии для загрузки или генерации данных
    │
    ├── features.py             <- Функции для моделирования
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Код для предсказания моделей          
    │   └── train.py            <- Код для обучения моделей
    │
    └── plots.py                <- Код для создания визуализаций
```