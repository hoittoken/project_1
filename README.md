## Проект №1 в рамках обучения профессии Data Science от Skill Factory

## ОПИСАНИЕ ЗАДАЧИ

**Есть база резюме**, выгруженная с сайта поиска вакансий hh.ru. [Файл с исходными данными](https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view?usp=sharing).

**Проблематика:** часть соискателей не указывает желаемую заработную плату, когда составляет своё резюме.

**Задача:** построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе.

### Используемые файлы
[База данных с сайта hh.ru](https://drive.google.com/file/d/1eGY6IDAqP5zh0Vyg4bF1gQd5nn0gT_W9/view?usp=sharing)

[Курсы валют с сайта mdf.ru](https://drive.google.com/file/d/1dOv7PysDnHw0bNHPUftpg5A7PhT2rhEC/view?usp=sharing)

### ОРГАНИЗАЦИОННАЯ ИНФОРМАЦИЯ

Проект состоит из четырёх частей:

1. Базовый анализ структуры данных

2. Преобразование данных

3. Разведывательный анализ

4. Очистка данных

### ЧТО НЕОБХОДИМО СДЕЛАТЬ ДЛЯ УСПЕШНОГО ВЫПОЛНЕНИЯ ПРОЕКТА?

* Внимательно **изучить детали задачи**.
* Скачать [датасет](https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view) и [ноутбук-шаблон](https://lms.skillfactory.ru/assets/courseware/v1/619ae706e569851b2a47820a175b212a/asset-v1:SkillFactory+DSPR-2.0+14JULY2021+type@asset+block/Ноутбук-шаблон_Project_1.ipynb).
* Обязательно **ознакомиться с дополнительным теоретическим материалом**, который даётся перед заданием.
* **Воспользоваться нашими советами и подсказками** при выполнении проекта.
* **Ответить на все контрольные вопросы**: за них вы можете максимально набрать 30 баллов на платформе.
* **Загрузить ноутбук** со своим решением на GitHub, оформив его в соответствии с требованиями.
* **Сдать проект на проверку** и получить 10 баллов (из них 8 баллов — за основное задание и 2 балла — за дополнительное) за выводы по разведывательному анализу.
* **Получить обратную связь** от команды курса.

Для успешного выполнения проекта вам необходимо набрать **21** балл из **40** возможных.

### Требования к оформлению ноутбука-решения
* Решение оформляется только в `Jupyter Notebook`.
* Решение оформляется в соответствии с ноутбуком-шаблоном.
* Каждое задание выполняется в отдельной ячейке, выделенной под задание (в шаблоне они помечены как **ваш код здесь**). Не следует создавать множество ячеек для решения задачи — это создаёт неудобства при проверке.
* Код для каждого задания оформляется в одной-двух jupyter-ячейках (не стоит создавать множество ячеек для решения задачи, это усложняет проверку).
* Решение должно использовать только пройденный материал: переменные, основные структуры данных (списки, словари, множества), циклы, функции, библиотеки numpy, pandas, matplotlib, seaborn, plotly. Если вы думаете, что для решения необходимо воспользоваться сторонними библиотеками или инструментами (например Excel), другими языками программирования или неизученными конструкциями, вы ошибаетесь :) Все задания решаются с помощью уже знакомых методов.
* Код должен быть читаемым и понятным: имена переменных и функций отражают их сущность, важно избегать многострочных конструкций и условий.
* Пользуйтесь [руководством PEP 8](https://lms.skillfactory.ru/courses/course-v1:SkillFactory+DSPR-2.0+14JULY2021/jump_to_id/958c1e42860d475999e9f9381dfe8b5a).
* Графики оформляются в соответствии с теми правилами, которые мы приводили в [модуле по визуализации данных](https://lms.skillfactory.ru/courses/course-v1:SkillFactory+DSPR-2.0+14JULY2021/jump_to_id/1fa00a018157484a9bae5d4557ef3e7c).
* **Обязательное требование:** графики должны содержать название, отражающее их суть, и подписи осей.
* Выводы к графикам оформляются в формате Markdown под самим графиком в отдельной ячейке (в шаблоне они помечены как **ваши выводы здесь**). Выводы должны быть представлены в виде небольших связанных предложений на русском языке.
