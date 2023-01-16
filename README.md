## Хакатон 2023
# Команда Número UNO "Las Teteras Desesperadas"
<h1 align="center">Задача: Автоматизированная обработка сканов документов 

## Состав команды
- Загальский Игорь - Project Manager
- Мишин Илья - Product Manager
- Мурейко Елена
- Иванов Иван
- Санникова Юлия
- Майнгерт Владимир
- Репенко Диана

## <a href="https://miro.com/app/board/uXjVP2DInDc=/?moveToWidget=3458764543238787224&cot=14" target="_blank">Ссылка на Miro</a> 
 
## Идеи реализации задачи:
1) Реализация с использованием библиотеки Python-Tesseract, которая является оболочкой для Google Tesseract-OCR Engine. 
2) Применение свёрточной нейронной сети с помощью модели CRNN, которая представляет собой комбинацию сверточной нейронной сети backbone CNN и рекуррентной нейронной сети RNN. 
3) Распознавание с помомощью open source библиотеки компьютерного зрения OpenCV, которая предназначена для анализа, классификации и обработки изображений; а также библиотеку Pillow, которая является ответвлением Python Imaging Library (PIL) для обработки открытия и обработки изображений во многих формата. 
 
 
## Выбранная идея реализации задачи:
Распознавание с помомощью библиотек OpenCV и Pillow
 
 
 
<h2 align="center">Чек-поинт №1.  

#### *1. Подготовить первый вариант программы, выполняющей сегментацию документов на скане.*
запустить скрипт test1.ipynb 
#### *2. Подготовить примеры работы первого варианта сегментации документов из предоставленного набора данных.*

 
 
#### *3. Оценить, какие документы удается сегментировать успешно, а при сегментации каких типов документов возникают проблемы. Описать успехи и проблемы сегментации.*
---------На данном этапе для выбранного малого набора документов сегментация проходит успешно во всех случаях, с небольшой погрешностью. --------------
