# Лабораторная №2 (Компьютерная графика)

## Рогозенко Дмитрий. Вариант 4

В данной лабораторной использовался язык программирования ```Java``` без сторонних библиотек. 

## Описание

Методы: Сегментация изображений: обнаружение точек, линий и перепадов яркости. Глобальная пороговая обработка (2 метода на выбор) + Адаптивная пороговая обработка.

## Описание

Все алгоритмы обработки состояли в том, чтобы преобразовать пиксели тем или иным способом. Приложение работает следующим образом: в графическом интерфейсе имеется кнопка Browse, 
которая открывает проводник по файловой системе и предоставляет возможность выбрать графический файл. Появляется превью выбранного изображения. 
Затем при нажатии на одну из кнопок обработки, на соседнем превью появляется обработанное изображение, также результат сохраняется в папку 
(с названием по выбранной обработке) с таким же названием изображения внутри папки, где находится исходное изображение.

![Screen of work example_1](https://github.com/RedExtreme12/CG_lab_2/blob/master/screens/screen_work_exmpl.png)

Например, для сегментации изображения изначально все пиксели изображения преобразовались в градацию серого, а затем устанавливались в черный или белый, в зависимости от того, превосходит ли значение в градации серого среднее значение или нет. Как результат сегментирование позволяет находить на изображении перепады цветов, яркости, очертания предметов, точки. Для тестирование разумно будет подбирать такие изображения, которые данными характеристиками отличаются. Например (в папке лабораторной в репозитории больше примеров):


