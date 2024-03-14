# DB_MIPT_2024

- Скачал датасет customer segmentation

- Написал docker-compose с образом mongo и датасетом

![Alt text](images/image.png)

- Поднял контейнер

![Alt text](images/2.png)

- Закачал датасет

![Alt text](images/1image.png)

- mongosh

![Alt text](images/1image-1.png)

- findOne

![Alt text](images/1image-2.png)

- insert

![Alt text](images/1image-3.png)

- update

![Alt text](images/1image-4.png)

- delete

![Alt text](images/1image-5.png)

- индексы
- замерим сначала без индексов

![Alt text](images/1image-6.png)

- создадим индекс

![Alt text](images/1image-7.png)

- замерим с индексом

![Alt text](images/1image-8.png)

- датасет маленький, поэтому по времени  не видно улучшения, но видно что totalDocsExamined стал меньше