# Автоматическое построение черновика презентации на основе текста ВКР #

Разработка программы по автоматическому построению черновика презентации на основе текста выпускной квалификационной работы, написаной на факультете ВМК МГУ.

### Как настроить окружение ###

Перейти в рабочий каталог:  
```cd graduation-thesis-presentation```

Создать виртуальное окружение:  
```virtualenv --no-site-packages -p python3 venv```

Активировать виртуальное окружение:  
```source venv/bin/activate```

Установить все необходимые пакеты:  
```pip install -r requirements.txt```

### Как проверить работу программы ###

Запустить Jupyter Notebook:  
```jupyter notebook```

В открывшемся окне браузера выбрать файл *common_info.ipynb*.

Поменять значения переменных в первых двух ячейках.

Сохранить файл *common_info.ipynb*.

Открывать разные файлы, читать описания ячеек и последовательно выполнять код внутри них.

Непосредственно генерация презентации происходит внутри файла *collect_presentation.ipynb*.