# Pizza Shop

O *Pizza Shop* é uma plataforma onde usuários podem cadastrar suas lojas, independentemente do tipo de comida (não se limita a pizzas). A plataforma foi construída com React, TypeScript e várias bibliotecas que aprimoram a experiência do usuário e a produtividade no desenvolvimento. O projeto integra um back-end pronto para gerenciar dados e realizar autenticação por e-mail.

# 🚀 Tecnologias Utilizadas

React: Biblioteca JavaScript para a construção da interface do usuário.

Vite: Ferramenta de build moderna que acelera o desenvolvimento, configurada com TypeScript.

Docker: Usado para facilitar a configuração do ambiente de desenvolvimento.

Axios: Biblioteca para realizar requisições HTTP para o back-end.

ShadCN: Utilizada para o design e componentes visuais modernos.

Tailwind CSS: Framework CSS utilitário que facilita a criação de layouts responsivos e estilizados.

Lucid React: Para obter imagens no formato de ícones e ilustrações.

Helmet: Permite a alteração de metadados da página, como o título da página.

Sonner: Biblioteca para notificações "toast", oferecendo uma maneira simples de exibir mensagens.

React Query: Biblioteca para gerenciar e fazer o cache das requisições de dados do front-end.

# 📂 Estrutura do Projeto
O projeto é dividido em diversas rotas principais, com funcionalidades específicas:

Dashboard: Página principal do usuário, onde ele pode ver as estatísticas do seu estabelecimento (contém 4 cards e dois gráficos).

Orders: Página onde o usuário pode visualizar os pedidos realizados e o status do pedido.

SignIn: Página de login do usuário, que permite a autenticação via e-mail.

SignUp: Página de cadastro do usuário, onde ele cria uma nova conta.

## Funcionalidades Adicionais:
Skeleton Loading: Ao carregar as páginas "Dashboard" e "Orders", um esqueleto de carregamento (skeleton) é exibido, melhorando a experiência do usuário enquanto os dados estão sendo carregados.

Cadastro de Lojas: Usuários podem cadastrar suas lojas na plataforma, que pode ser de qualquer tipo de comida, não apenas pizza. O sistema é flexível para diversas categorias de alimentação.

Autenticação por E-mail: O login é realizado apenas com e-mail, sem necessidade de senha. Após o login, um "toast" é exibido informando ao usuário que a liberação foi enviado para o seu e-mail (ainda não implementado para enviar o link por e-mail, mas ele é exibido no console do back-end e o usuário pode clicar no link para ser redirecionado ao Dashboard).

# 🌐 Como Rodar o Projeto Front-End
Para rodar o front-end do projeto, siga os seguintes passos:

Clone o repositório:

``` git clone https://github.com/Viniciusspss/pizzashop-web.git ``` 

Navegue até a pasta do projeto:

```cd pizzashop-web```

Instale as dependências:
```npm install``` ou ```npm install --legacy-peer-deps```

Inicie o servidor de desenvolvimento:

```npm run dev```

O front-end estará disponível em http://localhost:5173/.

# 🌐 Como Rodar o Projeto Back-End
O back-end deve ser inicializado separadamente. Siga os passos abaixo:

Clone o repositório:

``` git clone https://github.com/rocketseat-education/pizzashop-api ``` 

Navegue até a pasta do back-end (certifique-se de que o back-end esteja configurado corretamente):

```cd pasta-do-backend```

Instale e configure as dependências:

```bun install```

```docker compose up -d```

```bun migrate```

```bun seed```

Inicie o back-end:

```bun dev```

# 🛠️ Desenvolvimento
Durante o desenvolvimento, algumas bibliotecas e ferramentas foram essenciais para aumentar a produtividade e melhorar a experiência do usuário:

Axios foi utilizado para as requisições HTTP ao back-end.

React Query foi empregado para a gestão eficiente de dados assíncronos e o cache das informações.

Tailwind CSS e ShadCN proporcionaram um design moderno, com um excelente suporte a componentes customizados.


