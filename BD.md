## Юсуфов Умар Фалохиддинович

### 2.
База данных полиции, в которую входит 5 таблиц:
* crime(преступление);
* detainess(задержанный);
* documents(документы);
* employee(сотрудник);
* evidence(свидетельства).

##  2.1
	 Таблица "crime", которая содержит атрибуты:
* crimeid(Айди преступления, настроен по умолчанию, int);
* description(Описание, varchar(799));
* date_and_time(дата и время, varchar(199));
* information_about_the_accused(Свидение об обвиняемых(799)).

![](screenshots/crime1.png)	![](screenshots/Crime2.png)

	Таблица "detainess", которая содержит атрибуты:
* detainessid(Айди задержанного, настроен по умолчанию, int);
* id_employee(Айди сотрудника, int);
* id_crime(Айди преступления, int);
* date_and_time_of_detention(Дата и время задержания, varchar(799));
* additional_details_of_the_detention(Доп.детали задержания, varchar(799));

![](						![](

	Таблица "documents", которая содержит атрибуты:
* documentsid(Айди документа, настроен по умолчанию, int);
* id_crime(Айди преступления, int);
* date_of_creation(Дата создания, varchar(799)).

![](						![](

	Таблица "employee", которая содержит атрибуты:	
* employeeid(Айди сотрудника, настроен по умолчанию, int);
* fullname(Имя, varchar(199));
* rank(Звание, varchar(199));
* telephone(Телефон, varchar(199)).

![](screenshots/Employee.png)			![](screenshots/Employee2.png)

	Таблица "evidence", которая содержит атрибуты
* evidenceid(Айди свидетельства, настроен по умолчанию, int);
* description(Описание, varchar(799));
* witness_details()
