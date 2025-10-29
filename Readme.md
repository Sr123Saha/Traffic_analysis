
# Traffic analysis



<h1 align="center"><summary style="font-size: 24px;">Привет, я рад тебя тут видеть 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="30"/></summary></h1>

## Введение 🐸
 - Проект направлен на определение и анализ интенсивности транспортных и пешеходных потоков с использованием методов компьютерного зрения.  
Основная цель — **автоматизировать подсчёт количества машин и людей** на видео с камер наблюдения или светофоров, а также провести **оценку точности обученной модели YOLO11**.


<h1> </h1>


## Цель 🐛
 - Сделать модель которая будет искать и считать людей и машин на видео 

## О работе 🐌
 ### 1.) Работа с данными 📝
 -  поиск данных
 - распаковка данных
 ### 2.) Работа с моделью 🧩
  -  Подготовка данных и классов для модели Yolo
  -  Проверка наличия GUDA(для обучения на видеокарте)
  -  Обучение 1 модели Yolo11m затем обучение Yolo11n
  -  Оценка моделей
  - создание трекинга на основе этих моделей
 ### 3.) Создание приложения 🧩
  -  создание приложения


## Структра проекта
  - main.ipynb
  - program.ipynb
 ### 1.) learned
 - train9
 - train12
 ### 2.) Progress report
 ### 3.) tracking_dataset
 - 8698-213454544_small
 - 2697636-uhd_1920_1440_30fps


## Что потребуется чтобы запустить проект
 *  Наличие устройства для запуска 
 *  Наличие Видеокарты 
 *  вам потребуется наличие Python 3.11 и выше
 *  желательно наличие компелятора

## Отчет по выполненной работе
 - <a href="https://github.com/Sr123Saha/Traffic_analysis/blob/main/Progress%20report/Презентация.pdf" target="_blank">Отчет в PDF</a>
 - <a href="https://github.com/Sr123Saha/Traffic_analysis/blob/main/Progress%20report/Презентация.pptx" target="_blank">Отчет в PPTX</a>

## Участники 🧑‍💻

- Серый Александр-  [github](https://github.com/Sr123Saha)
 <h1></h1>

## Источники 📜

####   Датасеты
 -  <a href="https://universe.roboflow.com/bennett-wfjzb/traffic-camera-iuruy/dataset/1" target="_blank">roboflow.com</a> - распознание машин
 -  <a href="https://universe.roboflow.com/homecameras/frigate-object-detection/dataset/1" target="_blank">roboflow.com</a> - распознание людей
 -  <a href="https:///ru/companies/recognitor/articles/505694/" target="_blank">habr.com</a> - Самая сложная задача в Computer Vision
 -  <a href="https:///ru/companies/recognitor/articles/505694/" target="_blank">habr.com</a> - Самая сложная задача в Computer Vision
 -  <a href="https://habr.com/ru/articles/452392/" target="_blank">habr.com</a> - Подборка датасетов для машинного обучения
 -  <a href="https://www.youtube.com/watch?v=uMzOcCNKr5A" target="_blank">www.youtube.com</a> - Yolov8 object tracking 100% native | Object detection with Python | Computer vision tutorial
 -  <a href="https://www.youtube.com/watch?v=m9fH9OWn8YM" target="_blank">www.youtube.com</a> - Train Yolov8 object detection on a custom dataset | Step by step guide | Computer vision tutorial
 -  <a href="https://habr.com/ru/companies/cinimex/articles/838888/" target="_blank">habr.com</a> - Гайд по трекингу экспериментов в ML
  -  <a href="https://habr.com/ru/articles/514450/" target="_blank">habr.com</a> - Как работает Object Tracking на YOLO и DeepSort
  -  <a href="https://habr.com/ru/articles/585248/" target="_blank">habr.com</a> - Подсчет автомобильного трафика с использованием COMPUTER VISION
  -  <a href="https://docs.ultralytics.com/" target="_blank">docs.ultralytics.com</a> - Ultralytics YOLO Docs




 Также как источник информации использовались 
  - <a href="https://chatgpt.com/" target="_blank">ChatGPT</a>
  - <a href="https://chat.deepseek.com/" target="_blank">deepseek</a>

# Вывод

 - Работа достаточно интересная мы узнали новую тему и открыли новые возможноси