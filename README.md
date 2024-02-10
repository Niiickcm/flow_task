# Fullstack Trello Clone: Next.js 14, Server Actions, React, Prisma, Stripe, Tailwind, MySQL

Características principais:

- Auth
- Organizations / Workspaces
- Painéis de criação
- Unsplash API para pegar boas imagens de capa aleatórias
- Registro de atividades para toda a organização
- Renomear e excluir quadro
- Criação de lista
- Renomear lista, excluir, arrastar e soltar, reordenar e copiar
- Criação de Card
- Descrição do Card, renomear, excluir, arrastar e soltar, reordenar e copiar
- Registro de atividades do Card
- Limite de painéis para cada organização
- Assinatura por Stripe para cada organização para desbloquear painéis ilimitados
- Landing page
- MySQL DB
- Prisma ORM
- shadcnUI & TailwindCSS

### Pré-requisitos

**Node version 18.x.x**

### Clone o repositorio

```shell
git clone https://github.com/Niiickcm/flow_task.git
```

### Instale os pacotes

```shell
npm i
```

### Configure o arquivo .env

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

STRIPE_API_KEY=

NEXT_PUBLIC_APP_URL=

STRIPE_WEBHOOK_SECRET=
```

### Configure o Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```

### Inicie o APP

```shell
npm run dev
```
