# Алгоритм обнаружия и сопровождения объектов по видео
## Первый вариант (реализован)
- Берем каждый кадр с видео камеры
- Отправляем его в обученную сеть YOLO
- Получаем на выходе из сети области, на которых сеть обнаружила интересующие нас объекты
- Добавляем отображение этих областей на видео кадр
- Показываем обработанный кадр с  результатами работы сети

## Второй вариант (необходимо реализовать в следующей итерации)
- Добавляем к первому алгоритму отслеживание объектов с помощью YOLO - https://docs.ultralytics.com/ru/modes/track/
- сеть YOLO добавляет каждому обнаруженному объекту уникальный идентификатор
- используя присвоенный идентифакатор, можно отследить движение обнаруженных объектов от кадра к кадру

## Проблема / Задача
1. Прогонять каждый кадр через сеть YOLO представляется неэффективным расходованием вычислительных ресурсов
2. В определенных условиях (темно, неподходящий фон, маленький размер объекта) сеть YOLO не может эффективно обнаруживать объекты при широких углах обзора и маленьком фокусном расстоянии
3. При обнаружении объектов может использоваться тепловизор с низким разрешением (например, 300 пикселей на 400 пикселей), на изображении с которого крайне сложно обнаруживать объекты с помощью YOLO
4. Качество обнаружения с помощью сети YOLO можно повысить, если своевременно увеличить зум (увеличить фокусное расстояние и уменьшить угол обзора) и повернуть камеру в нужном направлении 

## Предлагаемые решения
- Дополнить сеть YOLO набором более простых и более специфичных алгоритмов, которые могут определять появление признаков, требующих подключение сети YOLO и/или поворот и изменение зума камеры
- Ключевым признаком представляется детекция движения 
- Существует несколько алгоритмов детекции движения без использования нейронных сетей
- Object Tracking with SIFT Algorithm --> https://medium.com/@siromermer/object-tracking-with-sift-algorithm-using-opencv-51be3c6882c9
- Object Tracking with FAST Algorithm --> https://medium.com/@siromermer/tracking-objects-with-fast-algorithm-using-opencv-dea6dab97825
- Object Tracking with ORB Algorithm --> https://medium.com/thedeephub/detecting-and-tracking-objects-with-orb-using-opencv-d228f4c9054e
- Object Tracking with Background Subtraction --> https://medium.com/thedeephub/detecting-and-tracking-moving-objects-with-background-subtractors-using-opencv-f2ff7f94586f
- Object Tracking with Lucas-Kanade --> https://medium.com/thedeephub/object-tracking-and-path-mapping-using-lucas-kanade-optical-flow-in-opencv-2ea018e391d4
- Object Tracking with SIFT Algorithm --> https://medium.com/thedeephub/object-tracking-with-mean-shift-and-cam-shift-algorithms-using-opencv-fc2f30327199

## Третий вариант (требует RND)
 
