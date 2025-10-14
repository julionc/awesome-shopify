# Awesome Shopify [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


[<img src="media/shopify.png" width="250px" align="right" alt="Shopify">](https://www.shopify.com/free-trial?ref=vitalogy)

> Curated list of awesome [Shopify](https://www.shopify.com) resources, libraries, and open-source projects for developers and designers.

[Shopify](https://www.shopify.com/blog/what-is-shopify?ref=vitalogy) is a leading e-commerce platform that allows you to build and manage online stores.

> 💡 **Note for merchants:** [Bring your ideas to life for $1/month](https://shopify.pxf.io/ZQJOkq)

![GitHub last commit](https://img.shields.io/github/last-commit/julionc/awesome-shopify)
![GitHub Repo stars](https://img.shields.io/github/stars/julionc/awesome-shopify)

## Contents

- [Official Resources](#official-resources)
- [Documentation](#documentation)
- [Themes & Design](#themes--design)
- [Frontend Development](#frontend-development)
- [Mobile](#mobile)
- [Libraries](#libraries)
  - [Ruby](#ruby)
  - [Python](#python)
  - [JavaScript](#javascript)
  - [DotNet](#dotnet)
  - [Elixir](#elixir)
  - [Java](#java)
  - [Golang](#golang)
  - [PHP](#php)
  - [R](#r)
  - [Rust](#rust)
- [Example Apps](#example-apps)
  - [JavaScript Examples](#javascript-examples)
  - [PHP Examples](#php-examples)
  - [Python Examples](#python-examples)
  - [Ruby Examples](#ruby-examples)
  - [Elixir Examples](#elixir-examples)
- [Code Snippets](#code-snippets)
- [Developer Tools](#developer-tools)
- [Community](#community)

## Official Resources

- [Developer Changelog](https://shopify.dev/changelog) - Official blog with important updates to APIs and developer products.
- [Developer Guides](https://shopify.dev) - Overview of app development for Shopify.
- [Shopify Partner Account](https://www.shopify.com/partners?ref=vitalogy) - Required to start building apps.

## Documentation

- [OAuth Flow for Authentication](https://shopify.dev/docs/apps/build/authentication-authorization/access-tokens/authorization-code-grant)
- [App Store Requirements](https://shopify.dev/docs/apps/launch/app-requirements-checklist)
- [Development Stores](https://www.shopify.com/partners/blog/development-stores?ref=vitalogy)
- [App Design Guidelines](https://shopify.dev/docs/apps/design)

## Themes & Design

- [Shopify Horizon](https://github.com/Shopify/horizon) - Flagship of Shopify’s next-gen themes.
- [Shopify Dawn](https://github.com/Shopify/dawn) - Official Online Store 2.0 theme.
- [Figma – Dawn Theme](https://www.figma.com/community/file/1017615468313501249)
- [City Ecommerce UI Kit](https://github.com/shopifypartners/City-Ecommerce-UI-Kit)
- [Sketch Shopify Data Populator](https://github.com/shopifypartners/sketch-shopify-data-populator)

## Frontend Development

### Polaris Web Components ✨🚀

- [Polaris Web Components](https://shopify.dev/docs/api/app-home/using-polaris-components) - Shopify's UI toolkit for building interfaces that match the Shopify Admin design system.
   [Polaris UI Kit - Community](https://www.figma.com/community/file/1554895871000783188/polaris-ui-kit-community) - This UI Kit gives you Figma components that match the Polaris Web Components library.
- [App Bridge Web Components](https://shopify.dev/docs/api/app-home/app-bridge-web-components)

### Polaris React (Deprecated ⚠️)
- [Polaris React](https://polaris-react.shopify.com/) - Legacy React component library. [GitHub](https://github.com/Shopify/polaris-react)
- [Polaris Icon Explorer](https://polaris-react.shopify.com/icons)
- [Polaris Vue](https://github.com/ownego/polaris-vue) - Vue 3 implementation.

### Hydrogen (Headless)
- [Hydrogen](https://hydrogen.shopify.dev) - Headless stack for custom storefronts. [Source code](https://github.com/Shopify/hydrogen).
- [Fluid](https://github.com/frontvibe/fluid) - Hydrogen + Sanity for structured content management.
- [Pilot (Weaverse Hydrogen Theme)](https://github.com/Weaverse/pilot) - Fully featured Shopify Hydrogen theme crafted for launching modern, high-performance headless storefronts. Includes TypeScript, Tailwind CSS, GraphQL code generation, React Router, Oxygen deployment, and customization via Weaverse Studio. 🚀

### Liquid Template

- [Liquid](https://shopify.github.io/liquid/) - Template language created by Shopify.
- [Liquid Cheat Sheet](https://www.shopify.com/partners/shopify-cheat-sheet) - A resource for building Shopify Themes with Liquid.
- [Liquid template language reference](https://shopify.dev/docs/api/liquid) - Liquid is the backbone of all Shopify themes, and is used to load dynamic content to the pages of online stores.

### Others

- [Shopify UI Extensions](https://github.com/Shopify/ui-extensions) – Repo for the public definition of Shopify’s UI extension APIs. Developers use this to build strongly-typed UI extensions for Shopify surfaces. 🧰

## Mobile

### Buy SDK

You can use the iOS and Android Buy SDK to integrate Shopify checkout into your mobile applications. This lets you sell physical products directly through your app and track sales in your Shopify Admin. [Learn more ›](https://shopify.dev/docs/storefronts/mobile)

- [Shopify Mobile Apps](https://www.shopify.com/install) - Official Shopify mobile app for merchants.
- [Shopify Mobile Buy SDK (Android)](https://github.com/Shopify/mobile-buy-sdk-android) - Android SDK to integrate Shopify checkout within native apps. 🧰
- [Shopify Mobile Buy SDK (iOS)](https://github.com/Shopify/mobile-buy-sdk-ios) - iOS SDK to integrate Shopify checkout within native apps. 🧰

### Checkout Sheet Kit

- [Shopify Checkout Sheet Kit (React Native)](https://github.com/Shopify/checkout-sheet-kit-react-native) - Native module for embedding Shopify checkout in React Native apps. 🧰
- [Shopify Checkout Sheet Kit (Swift)](https://github.com/Shopify/checkout-sheet-kit-swift) - Native Swift SDK for embedding Shopify’s one-page checkout UI directly into iOS apps. 🧰

## Libraries

You can use official Shopify libraries or any of the third party libraries below for authenticating and interacting with the Shopify API.

### Ruby

- [Shopify Ruby API](https://github.com/Shopify/shopify_api)
- [A Rails Engine for building Shopify Apps](https://github.com/Shopify/shopify_app)
- [Shopify OAuth2 Strategy for OmniAuth](https://github.com/Shopify/omniauth-shopify-oauth2)

### Python

- [Shopify Python API](https://github.com/Shopify/shopify_python_api)
- [django-shopify-auth](https://github.com/discolabs/django-shopify-auth) - A package for adding Shopify authentication to a Django app.
- [Django Shopify Webhook](https://github.com/discolabs/django-shopify-webhook) - A package for receiving Shopify Webhooks in Django.

### JavaScript

- [Shopify API and app tools for JavaScript](https://github.com/Shopify/shopify-app-js)
- [js-buy-sdk](https://github.com/Shopify/js-buy-sdk) - Shopify JavaScript Buy SDK. (Check Cart API ⚠️)
- [shopify-api-node](https://github.com/MONEI/Shopify-api-node) - Node.js Shopify connector.
- [nestjs-shopify](https://github.com/nestjs-shopify/nestjs-shopify) - Packages to develop Shopify application using NestJS.

### DotNet

- [nozzlegear/ShopifySharp](https://github.com/nozzlegear/ShopifySharp) - A .NET library for Shopify.
- [agileharbor/shopifyAccess](https://github.com/skuvault-integrations/shopifyAccess) - Shoppify API .NET wrapper.

### Elixir

- [orbit-apps/elixir-shopifyapi](https://github.com/orbit-apps/elixir-shopifyapi) - ShopifyAPI and Plug.ShopifyAPI Elixir client.
- [sticksnleaves/exshopify](https://github.com/sticksnleaves/exshopify) - Elixir client for the Shopify API. ⚠️

### Java

- [ShopifyJavaSDK](https://github.com/smolloy/ShopifyJavaSDK) - Resteasy-based java client for the Shopify API.
- [shopify-api-java-wrapper](https://github.com/SevenSpikes/shopify-api-java-wrapper) - The Java wrapper for the Shopify API. ⚠️

### Golang

- [bold-commerce/go-shopify](https://github.com/bold-commerce/go-shopify) - Go client for the Shopify API.
- [gopify](https://github.com/oussama4/gopify) - A simple package for developing Shopify applications in Go. ⚠️
- [go-shopify](https://github.com/kiwih/go-shopify) - Golang tool for connecting to Shopify's API. ⚠️
- [shoauth](https://github.com/darrenpeters/shoauth) - Shopify oauth (oauth2) middleware for Golang. ⚠️

### PHP

- [Shopify API Library for PHP](https://github.com/Shopify/shopify-api-php) - Official library provides support for PHP Shopify apps to access the Shopify Admin API 🚀.
- [phpclassic/php-shopify](https://github.com/phpclassic/php-shopify) - PHP SDK for Shopify API.
- [ohmybrew/Basic-Shopify-API](https://github.com/osiset/Basic-Shopify-API) - A simple, tested, API wrapper for Shopify using Guzzle for REST and GraphQL.
- [bold-shopify-toolkit](https://github.com/bold-commerce/bold-shopify-toolkit) - A Symfony Based Shopify api wrapper.
- [pizdata/oauth2-shopify-php](https://github.com/pizdata/oauth2-shopify-php) - Shopify Provider for the OAuth 2.0 Client. ⏱
- [Kyon147/laravel-shopify](https://github.com/Kyon147/laravel-shopify) - A full-featured Laravel package for aiding in Shopify App development. ⏱
- [multidimension-al/oauth2-shopify](https://github.com/multidimension-al/oauth2-shopify) - Shopify's OAuth 2.0 support for the PHP League's OAuth 2.0 Client. ⏱
- [ShopifyExtras/PHP-Shopify-API-Wrapper](https://github.com/ShopifyExtras/PHP-Shopify-API-Wrapper) - Guzzle-based API client. ⏱
- [ZfrShopify](https://github.com/zf-fr/zfr-shopify) - Guzzle client around Shopify API.
- [slince/shopify-api-php](https://github.com/slince/shopify-api-php) - Shopify API Client for PHP. ⏱
- [oseintow/laravel-shopify](https://github.com/oseintow/laravel-shopify) - Laravel Shopify is a simple package which helps to build robust integration into Shopify. ⚠️
- [tothjmt/Laravel-Shopify](https://github.com/tothjmt/Laravel-Shopify) - A Laravel / Shopify API Wrapper. ⚠️
- [donutdan4114/shopify](https://github.com/donutdan4114/shopify) - A simple Shopify PHP SDK for private apps to easily interact with the Shopify API. ⚠️

### R

- [shopifyr](https://github.com/charliebone/shopifyr/) - Aims to provide an easy-to-use interface to the Shopify Admin API within R. ⏱

### Rust

- [Ventmere/shopify](https://github.com/Ventmere/shopify/) - Shopify API Client for Rust. ⏱
- [A Shopify API Client for Rust](https://github.com/0xtlt/shopify_api)
- [Shopify Function Rust](https://github.com/Shopify/shopify-function-rust)

## Example Apps

### JavaScript Examples

- [Shopify App Node](https://github.com/Shopify/shopify-app-template-node) - Boilerplate to create an embedded Shopify app made with Node, Next.js, Shopify-koa-auth, Polaris, and App Bridge React :sunny:.
- [Shopify App Template Remix](https://github.com/Shopify/shopify-app-template-remix) - A template for building a Shopify app using the Remix framework.
- [Product Reviews Sample App](https://github.com/Shopify/product-reviews-sample-app) - Sample app was built as a reference for how Shopify Developer tools can be used together to create a fully functional application.
- [Shopify Discount App Components)](https://github.com/Shopify/discount-app-components) - A library of discounts-focused React components to help in building Shopify apps.
- [Storefront API Examples](https://github.com/Shopify/storefront-api-examples) - Example custom storefront applications built on Shopify's Storefront API. ⚠️
- [Shopify app with Node.js, MongoDB, React.js and Express](https://github.com/kinngh/shopify-node-express-mongodb-app) - Boilerplate embedded app made with Express.js, MongoDB and React.js with webhooks, GDPR routes, monetization and more hooked up and ready to go.
- [Shopify app with Next.js and Prisma ORM](https://github.com/kinngh/shopify-nextjs-prisma-app) - Starter template for building embedded Shopify apps using Next.js and Prisma ORM, preconfigured with essential integrations.
- [Shopify App Vue Template](https://github.com/Mini-Sylar/shopify-app-vue-template) - Create a Shopify App with node and vue 3.
- [VienDinhCom/next-shopify-storefront](https://github.com/VienDinhCom/next-shopify-storefront) - A shopping cart using TypeScript, Tailwind CSS, Headless UI, Next.js, React.js, Hydrogen, and GraphQL API.
- [SmallAwesomeShop](https://github.com/JsssCode/SmallAwesomeShop) - An Angular 7 App example using Shopify's Storefront GraphQL API. ⚠️
- [Next.js App with Session Token](https://github.com/ctrlaltdylan/shopify-session-tokens-nextjs) - An example of a Shopify App powered by Next.js with Session Tokens (no custom server necessary). ⚠️
- [Vue Storefront 2](https://github.com/vuestorefront/shopify) - Frontend platform for headless commerce. ⚠️
- [Shopify App Starter (TypeScript, Mongo, Express, React)](https://github.com/yoMerce/shopify-app-starter) - A shopify app starter written in TypeScript. It uses MongoDB, Express and React. ⚠️

### PHP Examples

- [shopify-app-php](https://github.com/Shopify/shopify-app-template-php) - Example Shopify PHP app (Laravel).

### Python Examples

- [shopify_django_app](https://github.com/shopify/shopify_django_app) - Shopify Django App Example.

### Ruby Examples

- [Shopify Fulfillment Integration](https://github.com/Shopify/shopify-fulfillment-integration) - Example Fulfillment Service Integration with Shopify. ⚠️
- [Hosted Payment Simulator](https://github.com/Shopify/hosted-payment-sim) - Example of using the [Hosted Payment SDK](https://shopify.dev/apps/payments/hosted-payment-sdk). ⚠️
- [Shopify Surge Pricing](https://github.com/kevinhughes27/shopify-surge-pricing) - A demo of surge pricing for Shopify based on cart update webhooks. ⚠️
- [shopify-tax-receipts](https://github.com/kevinhughes27/shopify-tax-receipts) - Shopify app for automatically sending tax receipts when specified products are purchased. ⚠️
- [partner-metrics-for-shopify](https://github.com/forsbergplustwo/partner-metrics-for-shopify) - Metrics Dashboard for Shopify Partners, on Rails. ⚠️
- [Shopify app starter kit](https://github.com/ASoftCo/shopify-app-starter-kit) - A Shopify app boilerplate written in Ruby on Rails with appropriate tools to get your Shopify app up and running quickly. ⚠️

### Elixir Examples

- [Elixir Shopify App (Phoenix)](https://github.com/orbit-apps/elixir-shopify-app)

## Code Snippets

- [freakdesign/shopify-code-snippets](https://github.com/freakdesign/Shopify-code-snippets) - Shopify Code Snippets examples and tips.
- [vikrantnegi/shopify-code-snippets](https://github.com/vikrantnegi/shopify-code-snippets) - A compilation of code snippets for Shopify developers.
- [gocomet/snippets](https://github.com/gocomet/snippets) - A collection of code snippets, generally for use with Shopify.

## Developer Tools

### CLI Tools
- [Shopify CLI](https://github.com/Shopify/cli) - CLI to build apps, themes, and hydrogen storefronts for Shopify 🚀. 
- [Theme Kit](https://github.com/Shopify/themekit) - Shopify theme development command line tool. ⚠️
- [Theme Check](https://github.com/Shopify/theme-check) - The Ultimate Shopify Theme Linter. ⚠️

### CI/CD & Deployment

- [Shopify Online Store (GitHub Marketplace)](https://github.com/marketplace/shopify-online-store) - Automates Shopify theme deployments from GitHub pushes, streamlining your CI/CD workflow.

### Editors
- [Shopify Liquid for VS Code](https://marketplace.visualstudio.com/items?itemName=Shopify.theme-check-vscode)
- [vim-liquid](https://github.com/tpope/vim-liquid)
- [zed-shopify-liquid](https://github.com/TheBeyondGroup/zed-shopify-liquid)

### Services

- [Ngrok](https://ngrok.com) - A tool that makes it easy to expose your development environment to Internet.
- [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/) - To configure local server using cloudflare.
- [RequestBin](https://requestbin.net/) - It gives you a bucket to capture external requests. This is useful for seeing what the content of a [Shopify Webhook](https://shopify.dev/docs/api/webhooks) are.
- [Hookdeck](https://hookdeck.com/) - Tool for monitoring, managing and debugging Shopify Webhooks with custom retry logic, alerts, and filtering.
- [DeployHQ](https://www.deployhq.com/shopify) - Shopify integration in DeployHQ is a great way to streamline the development, review, and deployment of your store themes.

### Browser Extensions

- [Shopify Theme Inspector for Chrome](https://chrome.google.com/webstore/detail/shopify-theme-inspector-f/fndnankcflemoafdeboboehphmiijkgp) - Profile and debug Liquid template on your Shopify store.
- [Shopify App Detector](https://chrome.google.com/webstore/detail/shopify-app-detector-by-f/lhfdhjladfcmghahdbcmlceajdlbkale) - Detect which apps and what theme a Shopify store is using. [GitHub](https://github.com/feracommerce/shopify_app_detector)
- [Shopify Theme Wizard](https://chrome.google.com/webstore/detail/shopify-app-detector-by-e/fhkelfkhcaokghlkckfgjoejhanelped) - Detect which theme a Shopify store is using.

### Raycast Extension

- [Shopify Liquid Docs Search](https://www.raycast.com/maximedaraize/search-shopify-liquid-documentation) - Search and preview Shopify Liquid docs.
- [Developer Changelog](https://www.raycast.com/sandypockets/shopify-developer-changelog) - View the latest Shopify developer changelog.

### Utilities

- [Shopify Product CSVs](https://github.com/shopifypartners/product-csvs) - Get your Shopify development stores started with great product data.
- [Shopify Product CSVs and Images](https://github.com/shopifypartners/shopify-product-csvs-and-images) - Get your Shopify development stores started with great product data.

## Community

- [Shopify Devs on X](https://x.com/ShopifyDevs)
- [Reddit – /r/shopify](https://www.reddit.com/r/shopify/)
- [Shopify Figma Community](https://www.figma.com/@Shopify)
- [Developer Forums](https://community.shopify.dev) - Shopify Developer Community Forums.
- [Developers Discord](https://discord.com/invite/shopify-developers-597504637167468564) - Official Shopify Developers Discord server.
- [Merchants Community](https://community.shopify.com/) - Discussing eCommerce best practices and how to have a successful online store.

## Contributing

If you want to contribute, please read the [contribution guidelines](https://github.com/julionc/awesome-shopify/blob/main/contributing.md).  
Thanks to all [contributors](https://github.com/julionc/awesome-shopify/graphs/contributors) — you're awesome and this wouldn’t be possible without you! 🙌
