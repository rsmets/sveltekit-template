# sveltekit-template

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

## Prisma

Prisma is the chosen ORM. Some notable prisma commands are:

- To open the prisma db interface in the browser

  ```sh
  npx prisma studio
  ```

- Generate artifacts (e.g. Prisma Client)

  ```sh
  npx prisma generate
  ```

- Create a migration from changes in Prisma schema, apply it to the database, trigger generators (e.g. Prisma Client)

  ```sh
  npx prisma migrate dev --name=<migration_name>
  ```

- Validate your Prisma schema
  ```sh
  npx prisma validate
  ```

## Trunk

[Trunk](https://docs.trunk.io/cli) cli is being used to help with linting and overall code quality.
