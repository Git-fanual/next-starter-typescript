## *This is a (semi) Full-Stack webdev template for personal use*

### This template utilizes:
    NextJS
    TypeScript
    Prisma
    Tailwind css (With the daisyUI library for quick ui prototyping)

***
## ***Prisma***

### The default DB provider used is a sqlite file called **dev.db**

### To change the default DB provider do the following:
    In the prisma/scheme.prisma file, change the following as needed

    datasource db {
        provider = "{dbprovider}"
        url      = env("DATABASE_URL")
    }

### In the .env file change the DATABASE_URL property accordingly
    DATABASE_URL="{dbtype}://johndoe:randompassword@localhost:5432/mydb?schema=public"
***
