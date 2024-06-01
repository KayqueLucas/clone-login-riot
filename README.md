# Clone de Página de Login

Este projeto é um clone de uma página de login simples, desenvolvido usando React e Vite, com estilos em CSS. Ele serve como um exemplo básico de como criar uma interface de login funcional e estilizada com essas tecnologias.

## Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- HTML
- CSS
- JavaScript

## Funcionalidades

- Interface de usuário responsiva
- Formulário de login com campos para e-mail e senha
- Validação básica de formulário

## Capturas de Tela

(Adicione aqui capturas de tela do seu projeto)

## Pré-requisitos

Certifique-se de ter o Node.js instalado em sua máquina. Você pode verificar se ele está instalado executando o seguinte comando:

```sh
node -v
```

## Instalação

1. Clone este repositório para a sua máquina local:

```sh
git clone https://github.com/seu-usuario/clone-pagina-login.git
```

2. Navegue até o diretório do projeto:

```sh
cd clone-pagina-login
```

3. Instale as dependências do projeto:

```sh
npm install
```

## Executando o Projeto

Após instalar as dependências, você pode iniciar o servidor de desenvolvimento do Vite:

```sh
npm run dev
```

Abra o navegador e acesse `http://localhost:5173` para ver a página de login.

## Estrutura do Projeto

```
clone-pagina-login/
├── public/
│   ├── favicon.ico
│   └── index.html
├── src/
│   ├── components/
│   │   └── LoginForm.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── styles/
│       └── main.css
├── .gitignore
├── package.json
├── README.md
└── vite.config.js
```

- **public/**: Contém arquivos estáticos, incluindo o `index.html`.
- **src/**: Contém o código-fonte do projeto.
  - **components/**: Contém componentes React, como o formulário de login.
  - **styles/**: Contém arquivos CSS.
  - **App.jsx**: Componente principal do aplicativo.
  - **main.jsx**: Ponto de entrada do React.
- **.gitignore**: Arquivos e diretórios ignorados pelo Git.
- **package.json**: Gerencia dependências e scripts do projeto.
- **vite.config.js**: Configuração do Vite.

## Customização

Você pode customizar este projeto conforme suas necessidades:

- **Estilos**: Modifique os arquivos CSS em `src/styles`.
- **Componentes**: Adicione ou modifique componentes React em `src/components`.
- **Funcionalidade**: Adicione lógica adicional ao componente `LoginForm.jsx` para validar os campos de e-mail e senha.

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Para isso, faça um fork do repositório, crie uma nova branch para suas alterações e envie um pull request.
