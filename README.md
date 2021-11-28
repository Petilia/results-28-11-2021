# results-28-11-2021

При возникновении вопросов пишите в телеграм https://t.me/Ilia_Petryashin

# Обучение модели

Colab для обучения модели. Вначале к нему подключается Google Drive, с которого подкачивается датасет. Датасет доступен по ссылке https://drive.google.com/file/d/18TZpjY-Z53AHeLccQ9OxvAcM3Sdtfiso/view?usp=sharing

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nb9aCvlY895IvEI4Qlv4TLJDBp553QWm?authuser=1)<br>

# Проверка работы модели на примерах

Можно также загрузить свои изображения и проверить на них. Для этого нужно поменять путь к файлу TEST_IMAGE_PATH
Кроме того, для отображения картинки придется скопировать путь, выдаваемой моделью
![image](https://user-images.githubusercontent.com/94632457/143732363-eba07a5f-2b57-4a84-82c5-5f3f221a473a.png)
Или можно просто перейти в каталог YOLOX и открыть изображение из него
![image](https://user-images.githubusercontent.com/94632457/143732393-4680c0f6-f885-47a8-9e42-8ae169a1be44.png)

Пример)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bDkUTKj24B5ZFXgshGQtw48R0n9sPll6?authuser=1#scrollTo=ePrLaAhN2OKQ)<br>

![image](https://user-images.githubusercontent.com/94632457/143732627-3c2b7382-6ea9-4f34-8cd9-67dfb02e5ea4.png)

# Валидация результатов 

Google Colab для загрузки Ваших датасетов и выгрузки результатов в csv
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OXlQP12dkRSsDlD6adhu5VXlcpwKAbQ6?authuser=1#scrollTo=7BEUiqH-zh1c)<br>
В него необходимо загрузить ваши данные (рекомендуется подгружать их в архивированном zip формате например из GoogleDrive, а потом разархивировать)

# Папки репозитория
config - в папке лежат файлы конфигурации модели (пригождаются только в Colab)  
csv Результаты - Результаты модели на выданном датасете. TigVsLeo.csv - задача с тиграми и леопардами. PrincessVsNotPrincess.csv - задача с Принцессой  
Для примера формирования csv - вспомогательная папка  
Модели - папка с обученными за процесс хакатона моделями (лучшая - 6_10ep_new_aug.pth )  
