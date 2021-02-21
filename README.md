# Шахматы
## Цель
Реализовать на языке программирования Python игру "шахматы" максимально эффективно и приближенно к оригиналу.
## Технологии
Для отрисовки шахматной доски и вывода всей информации используется библиотека PyGame.
## Реализация
Приложение состоит из:
- файла core.py - для обработки перемещения фигур, содержит класс Board и классы каждой из фигур;
- папки data - для хранения всех изображений;
- файла main.py - для отрисовки доски и вывода всей информации пользователю, содержит класс Game и использует всё вышеперечисленное.
## Особенности
- явное разделение всей логики шахматной доски и её вывода пользователю на два файла, что позволяет легко переписать графический интерфейс на любую библиотеку с сохранение работоспособности шахматной доски;
- реализация всех основных правил игры (таких как рокировка, взятие пешки на проходе, превращение пешки);
- эффективные нахождения доступных ходов, всевозможные проверки без большого использования ресурсов системы.