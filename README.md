# Cadastro de produtos
[![NPM](https://img.shields.io/npm/l/react)] 

# Sobre o projeto

Essa é uma aplicação ASP.NET MVC que foi feita em um projeto no bootcamp GFT Start #4 .NET.

Essa aplicação console é uma pequena página de cadastro de produtos usando como base funções CRUD, onde você consegue cadastrar, editar, apagar, informar a quantidade do produto em estoque. Além disso, os produtos podem ser de diferentes categorias que podem ser criadas e cada produto é identificado por um Id diferente.

Essa aplicação é documentada no Swagger.

Todas essas informações são armazenadas em um banco de dados SQL Server.


# Tecnologias utilizadas

## Back end
- C# .NET

## Front end
- HTML

## Implantação em produção
- Back end: Visual Studio 2019
- Banco de dados: SQL Server

# Passo a passo
Usando o Visual Studio 2019, depois de inicializa-lo, criei um novo projeto do tipo "Aplicativo Web do ASP.NET Core (Model-View-Controller)" usando a versão .NET 5.0, o nome e o local do projeto é de escolha própria.

### Projeto MVC:
Depois de criado, o Visual Studio cria uma página localhost padrão e é ela que usei como base para trabalhar. É de muita importância ter alguns pacotes instalados no seu projeto, sendo eles o do Entity Framework utilizando o banco de dados SQL Server e as ferramentas do Entity Framework para conseguir utilizar o migrations.

Gerenciador de pacotes NuGet:
```Gerenciador de pacotes NuGet
Install-Package Microsoft.EntityFrameworkCore.SqlServer
Install-Package Microsoft.EntityFrameworkCore.Tools
```

Depois de instalado o pacotes e ter configurado o Entity Framework, executei alguns comandos para criar o banco de dados e suas tabelas.

Gerenciador de pacotes NuGet:
```Gerenciador de pacotes NuGet
Add-Migration InitialCreate
Update-Database
```



# Autor

Arthur Alcebíades

https://www.linkedin.com/in/arthur-alceb%C3%ADades-7b67a6211
