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

 **Instale o Git**
Se ainda não tiver o Git instalado, baixe e instale [aqui](https://git-scm.com/). Ele permite que você copie projetos do GitHub para sua máquina.

 **Clone o projeto para sua máquina**

Abra o terminal (ou prompt de comando no Windows) e execute o seguinte comando para copiar o projeto:

git clone https://github.com/seu-usuario/mercadinho-chapadao.git


2. **Configure o banco de dados:**

   - No diretório do projeto, você encontrará um arquivo chamado appsettings.json. Abra este arquivo com um editor de texto (como o Notepad ou Visual Studio Code).

Encontre a parte com "ConnectionStrings" e substitua as informações por suas credenciais de banco de dados do SQL Server:
   
   ConnectionStrings:
   { 
      DefaultConnection: Server=SEU_SERVIDOR;Database=MercadinhoChapadao;User Id=SEU_USUARIO;Password=SUA_SENHA;
   }

 
3. **Execute as migrações do Entity Framework:**

Para configurar o banco de dados, você precisa aplicar as migrações. No terminal (ainda dentro da pasta do projeto), execute o seguinte comando:

   dotnet ef database update
   


4. **Execute a aplicação:**

Para rodar o projeto, use o seguinte comando no terminal:

   dotnet run
   
5. **Acesse a aplicação:**

   Após a aplicação iniciar, abra seu navegador e vá para:
   
 e acesse  http://localhost:5192
   
 

     

   
   

   
