## Shopify Node Express
An shopify apps build with NodeJS using Express Framework

### Instalation
1. Create `.env` file
2. Fill the env file :

```bash

SHOPIFY_API_KEY=[your-app-api-key]
SHOPIFY_API_SECRET=[your-app-api-secret]

FORWARDING_ADDRESS=[your-url-forwarding-for-oauth]

```

### Run

`node index.js`

### Routes
1. `/` just print hello world
1. `/shopify` for installation add query `shop=your-shop.myshopify.com`
2. `/shopify/callback` for oauth callback