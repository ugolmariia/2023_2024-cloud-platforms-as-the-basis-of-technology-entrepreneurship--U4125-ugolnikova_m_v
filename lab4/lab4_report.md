University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/education/labs2023-2024/lab4/lab4/)

Group: U4125

Author: Ugolnikova Maria Vladimirovna

Lab: Lab4

Date of create: 05.05.2024

Date of finished:

Название приложения: MoodAnalyzer

Основная функциональность:
1. Анализ настроения текста: Пользователь может вводить текстовые сообщения, статьи, отзывы или любой другой текст в приложение, и AI-модель будет анализировать этот текст и определять его настроение (положительное, отрицательное или нейтральное).

2. Визуализация результатов: После анализа приложение предоставляет пользователю визуализацию результатов в виде графиков или диаграмм, показывающих распределение настроения в тексте.

3. История анализов: Приложение сохраняет историю анализов пользователя, позволяя просматривать предыдущие результаты и сравнивать их.

Инфраструктура приложения:
1. Frontend-сервер
2. Backend-сервер
3. База данных
4. NLP-модуль

Структура:
![image](https://github.com/ugolmariia/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship--U4125-ugolnikova_m_v/assets/103264273/b90c2b85-8c53-4a5c-a453-5117655b29c8)

**Расчет стоимости развертывания системы**

**Test**
MongoDB - M10, 10GB storage, 1.7GB RAM - 57$/месяц
NLP - syntax + sentiment analysis, <1M символов - 0.0015$/1000 символов
Frontend App - B2 instance, 768mb, 1.2GHz - 83$/месяц
Microservices - F1 instance (x2), 384mb, 600MHz - 83$/месяц
Redis - M1, 1GB - 46$/месяц
**ИТОГО: 270.5$/месяц**

**Pre-prod**
MongoDB - M40, 80GB storage, 16GB RAM - 619$/месяц
NLP - syntax + sentiment analysis, <5M символов - 0.00225$/1000 символов
Frontend App - B2 instance, 768mb, 1.2GHz - 83$/месяц
Microservices - F1 instance (x2), 384mb, 600MHz - 83$/месяц
Redis - M1, 1GB - 46$/месяц
**ИТОГО: 842.25$/месяц**

**Prod**
MongoDB - M80, 750GB storage, 128GB RAM - 4413$/месяц
NLP - syntax + sentiment analysis, 5M+ символов - 0.001875$/1000 символов
Frontend App - B2 instance, 768mb, 1.2GHz - 83$/месяц
Microservices - F1 instance (x2), 384mb, 600MHz - 83$/месяц
Redis - M1, 1GB - 46$/месяц
**ИТОГО: 4643.75$/месяц (10M символов в запросах)**
