# CursoMVC

In this project, I made my first web application using dotnet and MVC architecture. This application consists of in a website with 4 tabs: 
* Home
* Privacy
* "Categorias"
* "Produtos"

The Home and privacy tab, which still contains the same layout as the standard module provided by visual studio 2019, which was the IDE used in the project.

The "produtos" and "Categorias" tabs consist of tabs for registering categories and products.

Each category has a description in which the category name is stored and an Id created by the application for search purposes, whereas products have the following attributes:

* Id: This Id is generated by the application and has search purposes only.

* Descrição: This object contains the name of the product.

* Quantidade: In this field, the quantity of each respective product is stored.

* Preço: Here is where the price of the respective product is stored.

* Categoria Id: Here is where the category to which the product belongs will be chosen.

I used this project to learn about MVC architecture, because it is a good way to organize the applications.

![](https://i.imgur.com/rmRC8Vq.jpeg)

For this project i use Entity Framework Core to Sql Server, that i import to my project with this command:

`Install-Package Microsoft.EntityFrameworkCore.SqlServer`

And the tools of Entity Framework Core that I import with:

`Install-Package Microsoft.EntityFrameworkCore.Tools`

To create my DataBase I use the Migration, to add the Migration to my Project I use the command:

`Add-Migration InitialCreate`

 Obs: InitialCreate is the name I gave for this change in the database, for each "Add-Migration" you have to put a new name.
 
 And I use the command:
 `Update-Database`
 to Update my DataBase when I don something new.
 
 Reference: I used the knowledge obtained in the class "Application Development with .NET" given by Professor Anderson Clavico Moreira on the Digital Innovation One website to make this project.