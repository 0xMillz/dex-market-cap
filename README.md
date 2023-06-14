---
name: DEX MARKET CAP
slug: dex-market-cap
description: Simple Next.js template that uses Vercel Postgres as the database.
framework: Next.js
useCase: Starter
css: Tailwind
database: Vercel Postgres
deployUrl: https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fexamples%2Ftree%2Fmain%2Fstorage%2Fdex-market-cap&project-name=dex-market-cap&repository-name=dex-market-cap&demo-title=Vercel%20Postgres%20Next.js%20Starter&demo-description=Simple%20Next.js%20template%20that%20uses%20Vercel%20Postgres%20as%20the%20database.&demo-url=https%3A%2F%2Fdex-market-cap.vercel.app%2F&demo-image=https%3A%2F%2Fdex-market-cap.vercel.app%2Fopengraph-image.png&stores=%5B%7B"type"%3A"postgres"%7D%5D
demoUrl: https://dex-market-cap.vercel.app/
relatedTemplates:
  - postgres-prisma
  - postgres-kysely
  - postgres-sveltekit
---
## 🏗️ website under construction 🏗️  
# DEX Market Cap

In the spirit of decentralization, this is an attempt to build a trustless crypto market data aggregator that sources decentralized exchange data only. Centralized, custodial exchange APIs are notorious for serving stale, opaque, and inaccurate data, often manipulated by wash-trading and/or outright falsities.  

Planning to start listing exchanges supporting the [The Graph](https://thegraph.com/) first and then going on from there.  

Built with Next.js and [Vercel Postgres](https://vercel.com/postgres) as the database.

## Live site

https://dex-market-cap.vercel.app/

## Local development

Git clone and copy the .env.example file in this directory to .env.local (which will be ignored by Git):

```bash
cp .env.example .env.local
```

Then open `.env.local` and set the environment variables to match the ones in your Vercel Storage Dashboard.

Next, run Next.js in development mode:

```bash
pnpm dev
```
