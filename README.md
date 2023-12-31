 ### Описание задачи  
**«Мониторинг экосистемы через IT-решения»** 

### Проблема  
Окружающая среда подвергается постоянным изменениям под влиянием естественных факторов и человеческой деятельности. Экологам, научным исследователям и властям необходимы надёжные данные для мониторинга состояния экосистем, принятия обоснованных решений по охране природы и реагирования на экологические вызовы. Однако традиционные методы сбора данных трудоёмки, часто неожиданно высока вероятность ошибок.

Из-за роста техногенного воздействия и изменения климата актуальность точных и оперативных экологических исследований возрастает. Наблюдение за флорой и фауной, качеством атмосферного воздуха, состоянием водных ресурсов и земельных участков требует интеграции данных самого разного рода и формата. 

### Решение
Решением этой проблемы могут стать IT-решения, которые будут:

- работать с данными из различных источников — спутниковые изображения, записи звуков животных, информация о погодных условиях, фотографии животных;
- анализировать полученные данные с помощью предобученных моделей машинного обучения, чтобы выявлять тренды, изменения и аномалии в экосистемах;
- визуализировать какие-либо данные для упрощения интерпретации результатов и поддержки принятия решений;
- автоматизировать процесс оповещения о критических событиях в экосистеме, таких как необычная активность термальных источников, внезапное исчезновение видов или загрязнения.

**Условия соревнования:**  
[Ссылка на Дататон](https://apps.skillfactory.ru/learning/course/course-v1:SkillFactory+MFTIDSLIGHT+2022_DEC/block-v1:SkillFactory+MFTIDSLIGHT+2022_DEC+type@sequential+block@13949a5c924a4f6caa67dce944bf7620/block-v1:SkillFactory+MFTIDSLIGHT+2022_DEC+type@vertical+block@eaa448ad8c7a44d8a164d108adee42e9)  

Работа над проектом займёт 2 недели — 2 спринта.

- **1 спринт.** В понедельник состоится открытие, где детально будут разобраны и объяснены задачи практикума.
- **2 спринт.** В пятницу дедлайн. Нужно загрузить прокомментированное решение с документацией на GitHub и передать проект на проверку ментору через форму.
- **Заключение.** В понедельник выступление команд и закрытие. Регламент питча — 3 минуты на команду, 2 минуты на демонстрацию прототипа.

### Этапы работы над проектом  
1. ### **Определение бизнес-проблемы:**
   - **Идентификация проблемы:** в данном случае - анализ смертности в результате загрязнения воздуха и выявление влияния различных факторов на эту проблему.
   - **Оценка ситуации.** Происходит определение доступных ресурсов и требований к проекту, оценка рисков и непредвиденных обстоятельств.
   - **Определение целей:** предсказание уровня смертности в зависимости от уровня загрязнения воздуха и других факторов.
   - **Составление плана проекта.** Выбор технологий и инструментов.

2. ### **Определение данных:**
   - **Сбор данных** о смертности, уровне загрязнения воздуха, климатических условиях и других факторах, которые могут влиять на качество воздуха.
   - **Описание данных.** Изучение данных и их поверхностные свойства, такие как формат данных, количество записей или идентичность полей.
   - **Исследование данных.** Углубиться в данные. Визуализация их и выявление взаимосвязей
   - **Оценка доступности и качества данных.**

3. ### **Подготовка данных:**

   - **Выбор данных.** Определите, какие наборы данных будут использоваться.
   - **Очистка данных.** Исправление или удаление ошибочных значений.
   - **Конструирование данных.** Выведдение новых атрибуов.
   - **Интеграция данных.** Созданте новых наборов данных путём объединения их из нескольких источников.
   - **Преобразование данных** в удобный формат для использования в моделях машинного обучения.

4. ### **Моделирование:**
   - **Выбор подходящих моделей** машинного обучения для анализа смертности в результате загрязнения воздуха (например, регрессионные модели, нейронные сети и т.д.).
   - **Создание тестовой схемы.** Разделение данных на обучающую, тестовую и проверочную выборку(при необходимости).
   - **Разработка моделей** для предсказания влияния различных факторов на уровень смертности.
   - **Оценка моделей.**

5. ### **Оценка:**
   - **Оценка результатов.** Соответствуют ли модели критериям цели проекта. Какая модель или модели должны быть одобрены для внедрения.
   - **Анализ результатов и выбор наилучшей модели.**
   - **Определение следующих шагов.** На основании результатов принять решение о том, следует ли приступить к развёртыванию, продолжить итерации моделей или начать новые проекты на основе полученных знаний.

6. ### **Внедрение:**
   - **Интеграция выбранной модели** в систему мониторинга уровня загрязнения воздуха.
   - **Развертывание модели** для ее использования для предсказания уровня смертности.

7. ### **Мониторинг и обслуживание:**
   - **Поддержка и обновление модели** на основе новых данных.
   - **Регулярный мониторинг** результатов и корректировка модели при необходимости.

### Краткая информация о данных
[Ссылка на файл](https://www.kaggle.com/datasets/akshat0giri/death-due-to-air-pollution-19902017/download?datasetVersionNumber=1)
- death-rates-from-air-pollution.csv - Файл содержащий информацию о загрязнени, смертности по годам и странам   
   Колонки:
   - Entity - Имя страны(231 уникальное значение)
   - Code - Код страны
   - Year - Рассматриваемый период: с 1990 до 2017г.
   - Загрязнение воздуха (общее) (смертей на 100 000) - общее число смертей (в миллионах) из-за загрязнения воздуха
   - Загрязнение воздуха в помещениях (смертей на 100 000) - смертность из-за загрязнения воздуха в помещениях (в миллионах)
   - Твердые частицы на открытом воздухе (смертность на 100 000 человек) - смертность из-за загрязнения наружного воздуха (в миллионах)
   - Загрязнение озоном на открытом воздухе (смертность на 100 000 человек) - смертность из-за загрязнения озоном (в миллионах)
