
<!--
*** Obrigado por estar vendo o nosso README. Se você tiver alguma sugestão
*** que possa melhorá-lo, dê um fork no repositório e crie uma Pull
*** Request ou abra uma Issue com a tag "sugestão".
*** Obrigado novamente!
*** Team Profissionais SA
-->

<!-- PROJECT SHIELDS -->
<p>
  <img src="https://img.shields.io/badge/windelw4-a0.1.0-fddd5c" alt="yarn package" />
  <img src="https://img.shields.io/badge/yarn%20package-v1.22.10-0e7fbf" alt="yarn package" />
  <img src="https://img.shields.io/badge/nodejs-v14.15.5-026e00" alt="nodejs version" />
  <img src="https://img.shields.io/badge/react%20js-v17.0.1-61dafb" alt="react js version" />
  <img src="https://img.shields.io/badge/last%20commit-14%20abr%2021-a3a52a" alt="last commit" />
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
  - [Pré-requisitos](#pr%C3%A9-requisitos)
  - [Estrutura de Arquivos](#estrutura-de-arquivos)
  - [Instalação](#instala%C3%A7%C3%A3o)
  - [Workflow](#workflow)
  - [Publicação](#publica%C3%A7%C3%A3o)
- [Commits](#commits)
- [Licença](#licen%C3%A7a)
- [Contato](#contato)

<!-- ABOUT THE PROJECT -->
## Sobre o Projeto

Este projeto visa a criação de um pacote básico que possa ser utilizado no momento de criação de projetos utilizando React Native, visto que o processo de instalação e configuração das libs no início de um projeto podem gerar certa complexidade e muitas vezes até erros que atrasam o processo, atrapalhando assim o fluxo de desenvolvimento.

<!-- PROJECT STRUCTURE -->
### Estrutura de Desenvolvimento

Abaixo segue o que foi utilizado na criação do projeto:

- [typeface-muli](https://www.npmjs.com/package/typeface-muli)- Livraria de CSS e enginer de arquivos de fontes;
- [velocity](https://www.npmjs.com/package/velocity-react)- Agregador de velocidade de DOM;
- [web-vitals]()- Livraria de definições e medidores de Web Vitals;

<!-- GETTING STARTED -->
## Começando

Para instanciar o projeto, siga os passos abaixo.

<!-- REQUIREMENTS -->
### Pré-requisitos

Antes de seguirmos para as configurações e uso, é ideal que você tenha o ambiente configurado para criar e testar aplicativos em React, para isso você pode seguir os guias abaixo:

<h3 align="left">LINUX</h3>
- [Install JDK](https://docs.datastax.com/en/jdk-install/doc/jdk-install/installOpenJdkDeb.html) - Instalação do Java Development Kitt;
- [Gettin Started NodeJS, ReactJS on linux](https://www.zeolearn.com/magazine/setup-react-ubuntu) - instalação e configuração do NodeJS e ReactJS;
- [Install Yarn](https://classic.yarnpkg.com/en/docs/install/#debian-stable) - Instalação do pacote yarn via NPM;
- [VSCode on Linux](https://code.visualstudio.com/docs/setup/linux) - IDE de desenvolvimento padrão VSCode;
- [MariaDB](https://www.digitalocean.com/community/tutorials/how-to-install-mariadb-on-ubuntu-20-04-pt) - Instalação do banco de dados MariaDB;
*Se existir algum problema nas instruções, por favor, contribua com um issues!*

<h3 align="left">WINDOWS</h3>
- [Install JDK](https://www.guru99.com/install-java.html) - Instalação do Java Development Kitt;
- [Install NodeJS and Yarn](https://www.liquidweb.com/kb/how-to-install-yarn-on-windows/) - Instalação do NodeJS e Yarn;
- [Install ReactJS](https://www.liquidweb.com/kb/install-react-js-windows/) - Instalação do ReactJS;
- [Install VSCode](https://code.visualstudio.com/download) - Instalação da IDE de desenvolvimento padrão VSCode;
- [Install MariaDB](https://www.mariadbtutorial.com/getting-started/install-mariadb/) - Instalação do MariaDB;
*Se existir algum problema nas instruções, por favor, contribua com um issues!*

<!-- FILE STRUCTURE -->
### Estrutura de Arquivos

A estrutura de arquivos está da seguinte maneira:

```bash
app
├── public/
│   ├── assets/
│   │   ├── fonts/
│   │   └── images/
│   ├── material-ui-static/
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── @fuse/
│   │   ├── colors/
│   │   ├── core/
│   │   ├── default-settings/
│   │   ├── hooks/
│   │   ├── layouts/
│   │   └── utils/
│   ├── @history/
│   │   ├── @history.js
│   │   └── index.js
│   ├── @lodash/
│   │   ├── @lodash.js
│   │   └── index.js
│   ├── app/
│   │   ├── auth/
│   │   │   ├── store/
│   │   │   ├── Auth.js
│   │   │   ├── authRoles.js
│   │   │   └── index.js
│   │   ├── fuse-configs/
│   │   │   ├── navigation-i18n/
│   │   │   ├── navigationConfig.js
│   │   │   ├── routesConfig.js
│   │   │   ├── settingsConfig.js
│   │   │   └── themeConfig.js
│   │   ├── fuse-layouts/
│   │   │   ├── windelw4/
│   │   │   ├── shared-components/
│   │   │   ├── FuseLayoutConfigs.js
│   │   │   └── FuseLayout.js
│   │   ├── main/
│   │   │   ├── apps/
│   │   │   │   ├── calendar/
│   │   │   │   ├── chat/
│   │   │   │   ├── dashboard/
│   │   │   │   ├── file-master/
│   │   │   │   ├── notes/
│   │   │   │   └── appsConfigs.js
│   │   │   ├── auth/
│   │   │   │   ├── fogot/
│   │   │   │   ├── login/
│   │   │   │   ├── logout/
│   │   │   │   └── register/
│   │   │   ├── callback/
│   │   │   └── pages/
│   │   │   │   ├── errors/
│   │   │   │   ├── maitenance/
│   │   │   │   ├── profile/
│   │   │   │   └── pagesConfig.js
│   │   ├── services/
│   │   │   ├── auth0Service/
│   │   │   │   ├── auth0Service.js
│   │   │   │   ├── auth0ServiceConfig.js
│   │   │   │   └── index.js
│   │   │   ├── firebaseService/
│   │   │   │   ├── firebaseService.js
│   │   │   │   ├── firebaseServiceConfig.js
│   │   │   │   └── index.js
│   │   │   └── jwtService/
│   │   │   │   ├── index.js
│   │   │   │   └── jwtService.js
│   │   ├── store/
│   │   │   ├── fuse/
│   │   │   │   ├── dialogSlice.js
│   │   │   │   ├── index.js
│   │   │   │   ├── messageSlice.js
│   │   │   │   ├── navbarSlice.js
│   │   │   │   ├── navigationSlice.js
│   │   │   │   └── settingsSlice.js
│   │   │   ├── i18nSlice.js
│   │   │   ├── index.js
│   │   │   ├── rootReducer.js
│   │   │   └── withReducer.js
│   │   ├── App.js
│   │   └── AppContext.js
│   ├── styles/
│   │   ├── index.css
│   │   ├── print.css
│   │   ├── prism.css
│   │   ├── tables.css
│   │   ├── tailwind-base.css
│   │   ├── tailwind-config.css
│   │   └── tailwind.css
│   ├── i18n.js
│   ├── index.js
│   ├── react-chartjs-2-default.js
│   ├── reportWebVitals.js
│   └── serviceWorker.js
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

<!-- WORKFLOW -->
### Workflow

Nesta seção haverão instruções para editar o template e manter a estrutura principal de módulos explicando para que os diretórios são utilizados e também os arquivos de configuração.

- **EM PRODUÇÃO** 

- **public/** - Diretório publico de arquivos estáticos da aplicação;
>- **assets/**- Diretório contendo todos os arquivos de imagens e fontes;
>- **material-ui-static/** Diretório contendo arquivos publicos do material ui;
>- *favicon.ico* - Arquivo icone da aplicação;
>- *index.html* - Index estátiva da aplicação;
>- *manifest.json* - Manifesto publico da aplicação;
- **src/** - Diretório principal de configuração e organização da aplicação;
>- **@fuse/** - Diretório de configurações, estilos e core do tema;
> >- **colors/** - Estilos de cores;
> >- **core/** - Core do tema;
> >- **default-settings/** - Configurações do tema default;
> >- **hooks/** - Hooks do tema;
> >- **layouts/** - Route do tema;
> >- **utils/** - Uteis do tema;
>- **@history/**
> >- *@history.js* - Definição do Browser History;
> >- *index.js* - Instância do Browser History;
>- **@lodash/**
> >- *@lodash.js* - Definição do UMD;
> >- *index.js* - Instância do UMD;
>- **app/** -
> >- **auth/** -
> > >- **store/** -
> > >- *Auth.js* -
> > >- *authRoles.js* -
> > >- *index.js* -
> >- **fuse-configs/** -
> > >- **navigation-i18n/** -
> > >- *navigationConfig.js* -
> > >- *routesConfig.js* -
> > >- *settingsConfig.js* -
> > >- *themeConfig.js* -
> >- **fuse-layouts/** -
> > >- **layout1/** -
> > >- **shared-components/** -
> > >- *FuseLayoutConfigs.js* -
> > >- *FuseLayout.js* -
> >- **main/** -
> > >- **apps/** -
> > >- **auth/** -
> > >- **callback/** -
> > >- **documentation/** -
> > >- **fogot/** -
> > >- **login/** -
> > >- **logout/** -
> > >- **pages/** -
> > >- **register/** -
> > >- **user-interface/** -
> >- **services/** -
> > >- **auth0Service/**-
> > > >- *auth0Service.js* -
> > > >- *auth0ServiceConfig.js* -
> > > >- *index.js* -
> > >- **firebaseService/**-
> > > >- *firebaseService.js* -
> > > >- *firebaseServiceConfig.js* -
> > > >- *index.js* -
> > >- **jwtService/**-
> > > >- *index.js* -
> > > >- *jwtService.js* -
> >- **store/** -
> > >- **fuse/** -
> > > >- *dialogSlice.js* -
> > > >- *index.js* -
> > > >- *messageSlice.js* -
> > > >- *navbarSlice.js* -
> > > >- *navigationSlice.js* -
> > > >- *settingsSlice.js* -
> > > >- *i18nSlice.js* -
> > > >- *index.js* -
> > > >- *rootReducer.js* -
> > > >- *withReducer.js* -
> >- *App.js* -
> >- *AppContext.js* -
>- **styles/** - Styles da aplicação e tema em CSS;
> >- *index.css* - Arquivo main CSS;
> >- *print.css* - Arquivo de impressões padrões;
> >- *prism.css* - Arquivo de padronização do highlighter theme que utiliza Sass;
> >- *tables.css* - Arquivo de padronização de Tables;
> >- *tailwind-base.css* - Arquivo base do Tailwind;
> >- *tailwind-config.css* - Arquivo de configuração do Tailwind;
> >- *tailwind.css* -Arquivo default do Tailwind;
>- *i18n.js* - Arquivo de configuração inicial do i18next que define linguagem padrão ou linguagens utilizadas na aplicação;
>- *index.js* - Arquivo padrão de start da aplicação;
>- *react-chartjs-2-default.js* -
>- *reportWebVitals.js* -
>- *serviceWorker.js* -
- *.eslintignore* -
- *.eslintrc* -
- *.gitignore* -
- *.prettierrc* -
- *.yarnrc* -
- *.yarnrc.yml* -
- *CREDITS* -
- *jsconfig.json* -
- *LICENSE* -
- *package.json* -
- *purge-tailwindcss.js* -
- *README.md* -
- *tailwind.config.js* -
- *yarn.lock* -

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
