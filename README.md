# Configure
Please, create .env from example.env by coping and configure parameters for AWS cognito

1. First install packages
```
$ yarn install
```

`After that it will generate Prisma client automatically.`

`Don't install prisma/client & prisma/cli because you already have prisma cli from nexus-prisma-plugin.`

Datamodel - Prisma schema

![Workflow](documentation/images/prisma-migrate.png)


If you have faced problem with migration, [click here](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-migrate) to read more.


Command:

```
$ npx prisma
```

```
$ npx prisma migrate
```


# Run install

```
$ yarn run dev
```


