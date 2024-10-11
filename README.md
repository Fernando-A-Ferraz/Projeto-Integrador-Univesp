# Mercadinho Chapadão

Este é o projeto Mercadinho Chapadão, uma aplicação web para gerenciar produtos de um mercadinho. A aplicação permite criar, editar, visualizar e deletar produtos, além de exibir uma lista de produtos com informações detalhadas.

## Funcionalidades

- Listar produtos
- Adicionar novo produto
- Editar produto existente
- Deletar produto
- Exibir detalhes do produto

## Tecnologias Utilizadas

- ASP.NET Core
- Entity Framework Core
- Razor Pages
- SQL Server

## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado em sua máquina:

- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)
- [Visual Studio](https://visualstudio.microsoft.com/) (ou outro IDE de sua preferência)

## Instalação

Siga os passos abaixo para configurar o projeto em sua máquina local:

1. **Clone o repositório:**

   git clone https://github.com/seu-usuario/mercadinho-chapadao.git cd mercadinho-chapadao

   
2. **Configure o banco de dados:**

   - Abra o arquivo `appsettings.json` e configure a string de conexão com o seu SQL Server.
   -
      "ConnectionStrings": {
   "DefaultConnection": "Server=SEU_SERVIDOR;Database=MercadinhoChapadao;User Id=SEU_USUARIO;Password=SUA_SENHA;"

 }

 
3. **Execute as migrações do Entity Framework:**

   dotnet ef database update
   


   4. **Execute a aplicação:**


   dotnet run
   

   5. **Acesse a aplicação:**
   

   Abra o navegador e acesse  http://localhost:5192
   
 

     

   
   

   
