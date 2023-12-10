# lore

Let's Organise the Registry Easily!

Lore is a Strapi project used for keeping, maintaining and providing member data and other useful data for a hackerspace. Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

## Commands

### `develop`

In order to run the local development server, you need to set up some stuff in .env.
Create a file in the root directory called `.env`, and copy the contents of `.env.example` into it.

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
pnpm run dev
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
pnpm run start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
pnpm run build
```

## API

Strapi automatically generates a REST API based on the models.

To see the Swagger documentation for this API during local development, simply open http://localhost:1337/documentation/v1.0.0 (while the dev server is running).
