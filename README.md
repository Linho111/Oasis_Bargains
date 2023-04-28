# Hydrogen template: Hello World

Hydrogen is Shopify’s stack for headless commerce. Hydrogen is designed to dovetail with [Remix](https://remix.run/), Shopify’s full stack web framework. This template contains a **minimal setup** of components, queries and tooling to get started with Hydrogen.

[Check out Hydrogen docs](https://shopify.dev/custom-storefronts/hydrogen)
[Get familiar with Remix](https://remix.run/docs/en/v1)

## What's included

- Remix
- Hydrogen
- Oxygen
- Shopify CLI
- ESLint
- Prettier
- GraphQL generator
- TypeScript and JavaScript flavors
- Minimal setup of components and routes

## Getting started

**Requirements:**

- Node.js version 16.14.0 or higher

```bash
npm create @shopify/hydrogen@latest -- --template hello-world
```

Remember to update `.env` with your shop's domain and Storefront API token!

## Building for production

```bash
npm run build
```

## Local development
git clone https://github.com/Linho111/Oasis_Bargains.git \
&& cd Oasis_Bargains \
&& echo "PUBLIC_STORE_DOMAIN=a7a11c-2.myshopify.com\nPUBLIC_STOREFRONT_API_TOKEN=85af61c724014f8bfe1c70cda74ca9ad\nSESSION_SECRET=LOCAL_SECRET" >> .env \
&& yarn \
&& yarn dev
```bash
npm run dev
```
