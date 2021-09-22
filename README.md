<!-- PROJECT SHIELDS -->
<p>
  <img src="https://img.shields.io/badge/last%20commit-22%20set%2021-a3a52a" alt="last commit" />
  <img src="https://img.shields.io/badge/license-MIT-95c30e" alt="license MIT" />
</p>

<!-- PROJECT LOGO -->
<a href="">
  <h1 align="left">Portal Farani</h1>
</a>

<!-- TABLE OF CONTENTS -->
## Tabela de Conteúdo

- [Sobre o Projeto](#sobre-o-projeto)
- [Estrutura de Desenvolvimento](#estrutura-de-desenvolvimento)
- [Começando](#come%C3%A7ando)
  - [Estrutura de Arquivos](#estrutura-de-arquivos)
  - [Instalação](#instala%C3%A7%C3%A3o)
  - [Workflow](#workflow)
  - [Deploy](#deploy)
- [Commits](#commits)
- [Licença](#licen%C3%A7a)
- [Contato](#contato)

<!-- ABOUT THE PROJECT -->
## Sobre o Projeto

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.6.

<!-- PROJECT STRUCTURE -->
### Estrutura de Desenvolvimento

Abaixo segue o que foi utilizado na criação do projeto:

- [Angular CLI](https://www.npmjs.com/package/@angular/cli) - O Angular CLI é uma ferramenta de interface de linha de comando que você usa para inicializar, desenvolver, criar scaffold e manter aplicativos Angular diretamente de um shell de comando.
- [Angular Material](https://material.angular.io/) - Componentes do Material Design para Angular.

<!-- GETTING STARTED -->
## Começando

Para instanciar o projeto, siga os passos abaixo.

<!-- FILE STRUCTURE -->
### Estrutura de Arquivos

A estrutura de arquivos está da seguinte maneira:

```bash
portalFarani
├── dist/
├── src/
│   ├── app/
│   │   ├── auth/
│   │   │   ├── login/
│   │   │   │   ├── login.html
│   │   │   │   └── login.js
│   │   │   ├── esqueceu-senha/
│   │   │   │   ├── esqueceu-senha.html
│   │   │   │   └── esqueceu-senha.js
│   │   │   ├── alterar-senha/
│   │   │   │   ├── alterar-senha.html
│   │   │   │   └── alterar-senha.js
│   │   │   └── cadastre-se/
│   │   │       ├── cadastre-se.html
│   │   │       └── cadastre-se.js
│   │   ├── shared/
│   │   ├── components/
│   │   ├── controllers/
│   │   ├── directives/
│   │   ├── services/
│   │   │   ├── authService.js
│   │   │   └── userService.js
│   │   ├── app.module.js
│   │   └── app.routes.js
│   └── assets/
│       ├── img/
│       ├── libs/
│       ├── js/
│       │   └── utils.js
│       ├── styles/
│       │   ├── base/
│       │   │   ├── base.scss
│       │   │   └── reset.scss
│       │   ├── layout/
│       │   │   ├── form.scss
│       │   │   └── buttons.scss
│       │   ├── components/
│       │   │   ├── cardConteudo.scss
│       │   │   └── cardCertificados.scss
│       │   └── abstracts/
│       │       ├── variables.scss
│       │       └── mixins.scss
│       └── main.scss
└── index.html

```

Serão explicados os arquivos e diretórios na seção de [Workflow](#workflow).

<!-- INSTALL -->
### Instalação

1. Para instalar e utilizar a aplicação o processo é bem simples, basta iniciar o clone do repositório no diretório base escolhido para o desenvolvimento:
```sh
git clone https://bitbucket.com/profissionaisSA/portalFarani
"Entre com suas credenciais do repositório."
```

2. Entre no diretório da aplicaçao e execute o NPM.

```sh
cd portalFarani
npm i
```

3. Agora basta executar o micro serviço para ver no browser. https:localhost:4200

```sh
ng serve
```

---

<!-- WORKFLOW -->
### Workflow

Nesta seção haverão instruções para editar o template e manter a estrutura principal de módulos explicando para que os diretórios são utilizados e também os arquivos de configuração.

- **dist/** - Diretório publico de arquivos estáticos da aplicação;
- **src/** - 
>- **app/** - Diretório principal de configuração e organização da aplicação;
> >- **auth/** - Autenticação da aplicação;
> > >- **login/** -
> > > >- *login.js* -
> > > >- *login.html* -
> > >- **esqueceu-senha/** -
> > > >- *esqueceu-senha.js* -
> > > >- *esqueceu-senha.html* -
> > >- **alterar-senha/** -
> > > >- *alterar-senha.js* -
> > > >- *alterar-senha.html* -
> >- **services/**  - Serviços da aplicação;
> > >- **authService.js** - Serviços relacionados a autenticação do usuário;
> > >- **userService.js** - Serviços relacionados ao usuário. ex.: get e update de dados cadastrais;
> >- **shared/**  - Componentes reutilizáveis ou particionados;
> >- **components/**  - Cada componente é tratado como um mini aplicativo Angular;
> >- **controllers/** - Controllers da aplicação;
> >- **directives/**  - Diretivas da aplicação;
> >- *app.module.js* -
> >- *app.routes.js* -
>- **assets/** - Arquivos da aplicação
> >- **img/** - Imagens e ícones;
> >- **libs/** - Bibliotecas de terceiros, como jQuery, Moment, Underscore, etc;
> >- **css/** - Arquivos de CSS;
> > >- **base/** - Código padrão para o projeto;
> > > >- *base.scss* - Css de base para estilização;
> > > >- *reset.scss* - Reset de estilos aplicados pelos navegadores;
> > > >- *typography.scss* - Relacionado a tipografia da aplicação;
> > > >- *animations.scss* - Keyframes de animações;
> > >- **layout/** - Contêm tudo que é necessário para criar o layout do site ou aplicação;
> > > >- *header.scss* -
> > >- **utilities/** - Guarda todas as ferramentas e auxiliares de SASS usados por todo o projeto.
> > > >- *variables.scss* -
> > > >- *mixins.scss* -
> > >- **components/** - Enquanto a pasta layout/é macro, a pasta components/ é mais focada em módulos;
> > > >- *carousel.scss* -
> > >- **main.scss** - Arquivo main CSS;
> >- **js/** - Arquivos Javascript que não são para o Angular;
> > >- *utils.js* - Funções e scripts que podem ser reutilizados na aplicação;
- *index.html* - Arquivo padrão de start da aplicação;

<!-- REPOSITORY -->
## Commits de Tarefas

1. Faça o clone do projeto (`git clone https://bitbucket.com/`)
"Insira suas credenciais"
2. Crie uma Branch com o número da tarefa no Jyra (`git checkout -b GSA-1320`)
3. Adicione suas mudanças (`git add .`)
4. Comite suas mudanças (`git commit -m 'Comentário sobre a mudança realizada`)
5. Faça o Pull da Master (`git pull origin master`)
6. Faça o Push da Branch (`git push origin GSA-1320`)
7. Abra um Pull Request (`siga o link que aparecerá no console`) 

<!-- DEPLOY -->
## Deploy

- execute o seguinte comando `ng build -- prod`
    - este comando irá gerar os arquivos para produção na pasta `dist/profissionais-frontend` 
    - é recomendado versionar as publicações, via branches ou usar o git flow

- Acesse o `S3` da amazon (https://s3.console.aws.amazon.com/) com suas credenciais (devem ser fornecidas pelo seu gestor)
    - Account ID or account alias; IAM user name; password

- Acesse o bucket desejado
    - Produção: `new-profissionaissa.com`
    - Homologação: `profissionaissa-dev`

- Delete os arquivos existentes: `EXCETO: robots.txt E sitemap.xml` (são arquivos que usados com o Google Analytics)
    - Caso tenha excluído os arquivos `robots.txt` e `sitemap.xml`, eles se encontra na pasta `src/` da aplicação

- Adicione os arquivos gerados na `dist/profissionais-frontend` 

- Torne todos os arquivos públicos (selecione os arquivos > vá em Ações > Tornar público)

- (Produção) Limpe o cache da aplicação: Acesse o CloudFront na Amazon (https://console.aws.amazon.com/cloudfront/)
    - Selecione o item responsável pela dashboard, pode identificá-lo pelo id (E3J8BJ80M22IJB), CNAME (www.profissionaissa.com)...
    - Após selecionar, vá até a aba "Invalidations"
    - Execute um `create invalidation` com o seguinte Object Paths: `/*` 

aws cloudfront create-invalidation \
    --distribution-id E3J8BJ80M22IJB \
    --paths "/*"

<!-- LICENSE -->
## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

<!-- CONTATO -->
## Contato

Profissionais SA - [Site Institucional](https://www.profissionaissa.com/) - **allinne.mara@profissionaissa.com.br**
