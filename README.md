# prisma-06: Meus favoritos

- Para conseguir gerenciar as alterações feitas no banco de dados durante o desenvolvimento de uma aplicação, podemos usar o recurso de migrações do Prisma.
- Para usá-lo é bem simples: basicamente usamos o comando `prisma migrate dev`.
- ➡️ Execute o prisma migrate dev para gerar o banco no seu computador.
- ➡️ Crie alguns registros usando o endpoint já fornecido (POST `/favorites`).
- ➡️ Crie dois ou mais registros com a mesma URL e em seguida adicione uma propriedade `@unique` nesta propriedade.
- ➡️ Execute novamente o `prisma migrate dev` e estude o resultado.
