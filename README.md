# Sistema cadastro de vendedores e vendas

Projeto desenvolvido com ASP.Net Core, MVC e Entity Framework e conexão com bando de dados SQL Server.

Sistema foi criado com o objetivo de realizar um CRUD de vendedores e suas respectivas vendas. Assim que executar o projeto o próprio faz uma checagem se já existe dados no banco de dados, senão realiza a carga das informações.



## Tela de consulta geral dos vendedores

![](C:\Users\Rodrigo\Desktop\Cursos\Udemy\C# - dotNet\16 - Projeto-Sistema web-ASP.NET-EntityFramework\Projeto\SalesWebMvc\tela-consulta.PNG) Ao clicar no menu Sellers, é exibido todos as informações de vendedores cadastrados em nossa base de dados. Se clicar no botão "create new" redireciona para uma tela para cadastrar um novo usuario.



## Tela de cadastro de vendedor

![](C:\Users\Rodrigo\Desktop\Cursos\Udemy\C# - dotNet\16 - Projeto-Sistema web-ASP.NET-EntityFramework\Projeto\SalesWebMvc\tela-cadastro.PNG)

Tela que possibilita o cadastro de um novo vendedor na base de dados.



## Tela de consulta simples e agrupada

![](C:\Users\Rodrigo\Desktop\Cursos\Udemy\C# - dotNet\16 - Projeto-Sistema web-ASP.NET-EntityFramework\Projeto\SalesWebMvc\tela-consulta-simples-agrupadas.PNG)

Aqui o sistema habilita 2 forma de consultar os registros de venda. No caso consulta simples, onde é exibido na tela os dados de vendas pela data mínima e máxima. E consulta agrupada que no caso, é exibido as informações de maneira tabuladas com quantidade de vendas por dia, mês.