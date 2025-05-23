# Приложение для управления мероприятиями

## Описание проекта

Данное приложение создано с использованием **Streamlit** и позволяет вести учет данных о мероприятиях, участниках и их результатах. Пользователи могут вносить данные о мероприятиях, анализировать их по классам, ученикам или школе в целом, а также визуализировать результаты с помощью графиков.

# Установка зависимостей
Перед запуском приложения необходимо установить необходимые библиотеки. Выполните следующую команду в терминале:
pip install streamlit pandas matplotlib openpyxl

##Требования:
Python 3.8 или выше.
Установленные библиотеки: streamlit, pandas, matplotlib, openpyxl.  

###Запуск приложения
Создайте файл приложения :  
Сохраните код в файл с именем Project_2.py.  
Запустите приложение :  
Откройте терминал и перейдите в директорию, где находится файл Project_2.py.  
Выполните команду:streamlit run Project_2.py  
Откройте приложение в браузере :  
После запуска команды в терминале появится ссылка на локальный сервер (например, http://localhost:8501).  
Откройте ссылку в браузере.  
## Использование приложения
### Внесение данных
Перейдите в раздел "Внести данные" .
1. Заполните форму:
2. Введите название мероприятия.
3. Выберите дату мероприятия.
4. Укажите уровень мероприятия: Областной, Региональный, Городской или Школьный.
5. Выберите тип мероприятия: Индивидуальный или Групповой.
6. Укажите результат участия из предложенных вариантов.
7. Для индивидуальных мероприятий введите имя участника и его класс.
8. Для групповых мероприятий выберите классы и введите имена участников.
9. Нажмите кнопку "Сохранить данные" .
### Анализ данных
1. Перейдите в раздел "Анализировать данные" .
2. Выберите тип анализа:
3. По классу : просмотрите результаты для конкретного класса.
4. По ученику : просмотрите результаты для конкретного участника.
5.По школе : просмотрите общий рейтинг школы, включая количество мероприятий по уровням, распределение результатов и лидеров среди классов.
6. Нажмите кнопку "Проанализировать" .
7. Просмотрите результаты анализа и графики:
8. Круговые диаграммы для распределения результатов.
9. Столбчатые диаграммы для сравнения количества мероприятий.
10. Линейные графики для анализа активности классов.
### Cтруктура файла данных
Данные хранятся в файле events_data.xlsx
