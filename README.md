# Java-Data-Base-Lab

### 🔥Progress🔥:  
**Lab4:**  🌕🌑🌑🌑🌑🌑🌑🌑🌑🌑  _in progress..._  
**Lab5:**  🌑🌑🌑🌑🌑🌑🌑🌑🌑🌑  _in planning_  

## Задание:  
### Lab4:  
Работа с БД.  

    Сформировать таблицу товаров (id, prodid, title, cost) запросом из Java-приложения.  
    При запуске приложения очищать таблицу и заполнять N товаров вида:  
        id_товара 1 товар1 10   
        
Написать консольное приложение, которое позволяет:  
- Добавить товар в таблицу, в табице не может быть 2 товара с одинаковым именем  
    Пример:  
        `/add товар666 1050`  
        
- Удалить товар из таблицы	по имени.  
    Пример:  
        `/delete товар1984`  
        
- Вывести все товары в консоль.  
    Пример:  
        `/show_аll`  
        
- Узнать цену товара по его имени, либо если такого товара нет, то должно быть выведено сообщение "Такого товара нет".  
    Пример:   
        `/price товар777`  
        
- Изменить цену товара.  
    Пример:  
        `/change_price товар10 10000`  
        
- Вывести товары в заданном ценовом диапазоне цен.  
    Пример:  
        `/filter_by_price 1000 10000`  
        
Реализовать данное приложения пользуясь только средствами JDBC.  


### Lab5:  
    Реализовать графический интерфейс к Lab4.
