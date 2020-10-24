## IMPORTANTE
esta es una pagina hecha con gatsby que consume los recursos
del backend (strapi) y los renderiza.

entonces la idea es crear una pagina con un diseño distinto (ojala una retrochimba)
en donde se puedan ver estos tipos de contenido:

- Podcast realizados
- Videos realizados
- Exposiciones fotograficas

esto graficamente son cosas diferentes, pero a nivel de datos para hacer algo sencillo
se tienen que todo son articulos que tienen una categoria (podcast, video, fotos), entonces
me imagino que se pueden hacer diferentes componentes uno para mostrar los podcast,
otro para los videos y otro para las exposiciones fotograficas


mks que embarrada con la demora pero me enrede mucho con graphql al fin no entendi
ese hp! entonces dejo esta plantilla que pienso revisar para ver si se puede hacer
algo diferente.... 

Todo bien!!


# Strapi Starter Gatsby Blog

Gatsby starter for creating a blog with Strapi.

![screenshot image](/screenshot.png)

This starter allows you to try Strapi with Gatsby with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. So do not hesitate to add new features and report bugs!

## Features

- 2 Content types: Article, Category
- 2 Created articles
- 3 Created categories
- Responsive design using UIkit
- SEO and social media friendly

Pages:

- "/" to display every articles
- "/article/:id" to display one article
- "/category/:id" display articles depending on the category

## Getting started

The easiest way to try this starter is to run it locally on your computer.

First, you'll need to create your own copy of this starter. You can do so by clicking [the "Use this template" button](https://github.com/strapi/strapi-starter-gatsby-blog/generate) on GitHub, and filling the [form](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)

### Backend

Create a Strapi project named `backend` using the [blog template](https://github.com/strapi/strapi-template-blog):

```
# Using Yarn
yarn create strapi-app backend --template https://github.com/strapi/strapi-template-blog

# Or using NPM
npx create-strapi-app backend --template https://github.com/strapi/strapi-template-blog
```

The Strapi server will automatically start and import sample seed data.

### Frontend

Leave the Strapi backend running in the background. Open another terminal tab, and make sure you're in the `frontend` directory:

```bash
cd frontend
```

Install dependencies and start the Gatsby server:

```bash
# Using yarn
yarn install
yarn develop

# Using npm
npm install
npm run develop
```

If you want to change the default environment variables, create a `.env` file like this:

```sh
cp .env.example .env
```

The Gatsby server will run here => [http://localhost:3000](http://localhost:3000)

Enjoy this starter!
