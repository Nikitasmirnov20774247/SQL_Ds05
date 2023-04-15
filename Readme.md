# Урок 5. SQL – оконные функции
1. Создайте представление, в которое попадут автомобили стоимостью  до 25 000 долларов
2. Изменить в существующем представлении порог для стоимости: пусть цена будет до 30 000 долларов (используя оператор ALTER VIEW) 
3. Создайте представление, в котором будут только автомобили марки “Шкода” и “Ауди”
4. https://drive.google.com/file/d/1rkNr6GHSE9ulRs39BB4RC80aKMg1c7Jw/view?usp=share_link
* Добавьте новый столбец под названием «время до следующей станции». Чтобы получить это значение, мы вычитаем время станций для пар смежных станций. Мы можем вычислить это значение без использования оконной функции SQL, но это может быть очень сложно. Проще это сделать с помощью оконной функции LEAD . Эта функция сравнивает значения из одной строки со следующей строкой, чтобы получить результат. В этом случае функция сравнивает значения в столбце «время» для станции со станцией сразу после нее.