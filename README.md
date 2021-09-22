<!-- PROJECT SHIELDS -->
<p>
  <img src="https://img.shields.io/badge/last%20commit-22%20set%2021-a3a52a" alt="last commit" />
  <img src="https://img.shields.io/badge/license-MIT-95c30e" alt="license MIT" />
</p>

<!-- PROJECT LOGO -->
<a href="">
  <h1 align="left">Profissionais SA</h1>
</a>

<!-- TABLE OF CONTENTS -->
## Tabela de Conteúdo

- [Sobre o Projeto](#sobre-o-projeto)
- [Estrutura de Desenvolvimento](#desenvolvimento)
- [Começando](#come%C3%A7ando)
  - [Estrutura de Arquivos](#estrutura-de-arquivos)
  - [Instalação](#instala%C3%A7%C3%A3o)
  - [Workflow](#workflow)
  - [Publicação](#publica%C3%A7%C3%A3o)
- [Commits](#commits)
- [Licença](#licen%C3%A7a)
- [Contato](#contato)

<!-- ABOUT THE PROJECT -->
## Sobre o Projeto

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.6.

<!-- PROJECT STRUCTURE -->
### Estrutura de Desenvolvimento

Abaixo segue o que foi utilizado na criação do projeto:

- [typeface-muli](https://www.npmjs.com/package/typeface-muli)- Livraria de CSS e enginer de arquivos de fontes;
- [velocity](https://www.npmjs.com/package/velocity-react)- Agregador de velocidade de DOM;
- [web-vitals]()- Livraria de definições e medidores de Web Vitals;

<!-- GETTING STARTED -->
## Começando

Para instanciar o projeto, siga os passos abaixo.

<!-- FILE STRUCTURE -->
### Estrutura de Arquivos

A estrutura de arquivos está da seguinte maneira:

```bash
dashboard
├── dist/
├── src/
│   ├── app/
│   │   ├── auth/
│   │   │   ├── index.html
│   │   │   └── index.js
│   │   ├── shared/
│   │   │   ├── sidebar/
│   │   │   │   ├── sidebar.html
│   │   │   │   └── sidebar.js
│   │   │   ├── header/
│   │   │   │   ├── header.html
│   │   │   │   └── header.js
│   │   │   ├── formItem/
│   │   │   │   ├── formItem.html
│   │   │   │   └── formItem.js
│   │   │   ├── sidebar/
│   │   │   │   ├── sidebar.html
│   │   │   │   └── sidebar.js
│   │   ├── services/
│   │   │   ├── authService.js
│   │   │   └── userService.js
│   │   ├── components/
│   │   │   ├── home/
│   │   │   │   ├── home.html
│   │   │   │   └── home.js
│   │   ├── controllers/
│   │   │   └── mainControler.js
│   │   └── directives/
│   │       └── mainDirective.js
│   ├── app.module.js
│   └── app.routes.js
├── assets/
│   ├── img/
│   ├── js/
│   ├── libs/
│   ├── styles/
│   │   ├── base/
│   │   │   ├── base.scss
│   │   │   └── reset.scss
│   │   ├── layout/
│   │   │   ├── form.scss
│   │   │   ├── header.scss
│   │   │   ├── buttons.scss
│   │   │   └── sidebar.scss
│   │   ├── components/
│   │   │   ├── cardConteudo.scss
│   │   │   └── cardCertificados.scss
│   │   └── abstracts/
│   │       ├── variables.scss
│   │       └── mixins.scss
│   └── main.scss
├── .eslintignore
├── .eslintrc
├── .gitignore
├── .prettierrc
├── .yarnrc
├── .yarnrc.yml
├── CREDITS
├── jsconfig.json
├── LICENSE
├── package.json
├── purge-tailwindcss.js
├── README.md
├── tailwind.config.js
└── yarn.lock
```

Serão explicados os arquivos e diretórios na seção de [Workflow](#workflow).

<!-- INSTALL -->
### Instalação

1. Para instalar e utilizar a aplicação o processo é o seguinte:

---

<!-- REPOSITORY -->
## Commits

1. Faça um Fork do projeto (`git clone https://github.com/`)
"Insira suas credenciais"
2. Crie uma Branch com a o número da tarefa (`git checkout -b GSA-1320`)
3. Adicione suas mudanças (`git add .`)
4. Comite suas mudanças (`git commit -m 'Comentário sobre a mudança realizada`)
5. Faça o Pull da Master (`git pull origin master`)
6. Faça o Push da Branch (`git push origin GSA-1320`)
7. Abra um Pull Request (`siga o link que aparecerá no console`) 

<!-- LICENSE -->
## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
