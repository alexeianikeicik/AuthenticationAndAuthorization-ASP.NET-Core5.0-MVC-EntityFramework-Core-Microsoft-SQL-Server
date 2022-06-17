# AuthenticationAndAuthorization-ASP.NET-Core5.0-MVC-EntityFramework-Core-Microsoft-SQL-Server

The application is a page where you can register with certain rights (roles) and log in to the system. Depending on the rights (roles) in the system, access to the page for adding new roles in the system will be allowed or closed.

Приложение представляет из себя страницу, где можно зарегистрироваться с определёнными правами(ролями) и залогиниться в системе. В зависимости от прав(ролей) в системе будет разрешён или закрыт доступ к странице добавления новых ролей в системе.

The main page of the application looks like this: Главная страница приложения выглядит так:
![1](https://user-images.githubusercontent.com/85065601/174324088-3cc4e023-e81c-45da-8d70-2d2c75f6cd1c.jpg)

Creating a user with User rights: Создание пользователя с правами User:
![2](https://user-images.githubusercontent.com/85065601/174324560-5a0e5106-38f5-4070-9353-2333535b3ca8.jpg)

Creating a user with Admin rights: Создание пользователя с правами Admin:
![3](https://user-images.githubusercontent.com/85065601/174324670-65efcb82-d7bb-4b03-87bc-81c6041b9a8c.jpg)

Log in to the system as a user with User rights: Логинимся в системе пользователем с правами User:
![4](https://user-images.githubusercontent.com/85065601/174324993-38f12da1-db0e-44b1-87c4-018d42f53287.jpg)

Viewing roles in the system by a user with User rights: Просматриваем роли в системе пользователем с правами User:
![5](https://user-images.githubusercontent.com/85065601/174325289-966e7089-f9a5-47c0-b075-17c2772a2ae5.jpg)

We are trying to create a new role in the system by a user with User rights. Access denied: Пытаемся создать новую роль в системе  пользователем с правами User. Доступ запрещён:
![6](https://user-images.githubusercontent.com/85065601/174325845-b260cf91-81e2-4543-8eef-954be7a99691.jpg)

Log in to the system as a user with Admin rights: Логинимся в системе пользователем с правами Admin:
![7](https://user-images.githubusercontent.com/85065601/174326442-b9f3b405-d7da-4b31-af4d-4ef1ccf7740c.jpg)

Viewing roles in the system by a user with Admin rights: Просматриваем роли в системе пользователем с правами Admin:
![8](https://user-images.githubusercontent.com/85065601/174326714-2094644f-4421-4b7d-a0e3-b6ff35d326e2.jpg)

We are trying to create a new role in the system by a user with Admin rights. Access is allowed. You can enter the name of a new role and create it: Пытаемся создать новую роль в системе  пользователем с правами Admin. Доступ разрешён. Можно вводить название новой роли и создавать её:
![9](https://user-images.githubusercontent.com/85065601/174327160-642e2a59-f6f5-46f0-9d6a-598ede22ab08.jpg)
