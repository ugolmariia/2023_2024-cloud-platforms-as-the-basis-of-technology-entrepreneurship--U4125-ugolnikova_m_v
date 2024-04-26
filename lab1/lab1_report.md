University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/education/labs2023-2024/lab1/lab1/#_3)
Year: 2023/2024
Group: U4125
Author: Ugolnikova Maria Vladimirovna
Lab: Lab1
Date of create: 26.04.2024
Date of finished:

###Алгоритм выполнения работы

1. Создаем service account с ролью Storage Admin
<img width="596" alt="image" src="https://github.com/ugolmariia/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship--U4125-ugolnikova_m_v/assets/103264273/2f4bd273-fc97-49a2-b7a8-553b671aa4d9">
<img width="571" alt="image" src="https://github.com/ugolmariia/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship--U4125-ugolnikova_m_v/assets/103264273/5d87cc91-952c-402b-9adc-bee932537d7b">
<img width="895" alt="image" src="https://github.com/ugolmariia/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship--U4125-ugolnikova_m_v/assets/103264273/6764adfe-a1b1-4108-8872-a69c4421dbdd">

2. Создаем вирутальную машину
<img width="951" alt="image" src="https://github.com/ugolmariia/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship--U4125-ugolnikova_m_v/assets/103264273/8b0a0cc4-e4f2-44b5-9066-52e0608575cd">

3. Копируем файлы на VM
<img width="765" alt="image" src="https://github.com/ugolmariia/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship--U4125-ugolnikova_m_v/assets/103264273/cc0c5323-3c2a-49c9-8985-b37edc0674df">

4. Меняем роль на Compute Viewer
<img width="842" alt="image" src="https://github.com/ugolmariia/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship--U4125-ugolnikova_m_v/assets/103264273/5761ed43-50fd-4b0d-96fa-d13aa95f0420">

5.Отправляем повторно запрос на копирование файлов
<img width="1484" alt="image" src="https://github.com/ugolmariia/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship--U4125-ugolnikova_m_v/assets/103264273/a70487a8-ca4b-4dc6-acd7-cac051cf2bda">
Получаем ошибку 403 - недостаточно прав доступа


