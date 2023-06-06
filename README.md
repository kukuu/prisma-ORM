# Working with ORM

Object Relational Mapping (ORM) is a technique used in creating a "bridge" between object-oriented programs and, in most cases, relational databases.

Put another way, you can see the ORM as the layer or middleware that connects object oriented programming (OOP) to relational databases.

When interacting with a database using OOP languages, you'll have to perform different CRUD operations like creating, reading, updating, and deleting (CRUD) data from a database. By design, you use SQL for performing these operations in relational databases.

While using SQL for this purpose isn't necessarily a bad idea, the ORM and ORM tools help simplify the interaction between relational databases and different OOP languages. Acting as a middleware and providing an abstraction layer.

### Working with Prisma ORM

1. Start prisma studio

```bash
npx prisma studio
```

This will open up the studio in localhost:5555. Here you can interact with tha actual database. Do CRUD operations. Filter records and view it.

2. Migrate database

```bash
npx prisma migrate dev
```

Run the above migration command after adding new models or modifying the existing ones in prism/schema directory.

3. Seed Database

```bash
npx prisma db seed
```

4. References

-  [Prisma docs](https://www.prisma.io/docs/reference/api-reference)

