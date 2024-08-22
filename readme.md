# Awesome Shopify [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[<img src="shopify.png" width="250px" align="right" alt="Shopify">](https://www.shopify.com/free-trial?ref=vitalogy)

> A curated list of awesome [Shopify](https://www.shopify.com) resources, libraries and open source projects.

[Shopify](https://www.shopify.com/blog/what-is-shopify?ref=vitalogy) is a popular e-commerce platform that allows to build and manage online stores.
If you want to contribute, please read the [contribution guidelines](https://github.com/julionc/awesome-shopify/blob/main/contributing.md).
Thanks to all [contributors](https://github.com/julionc/awesome-shopify/graphs/contributors), you're awesome and wouldn't be possible without you!

Note: Are You A Merchant? - [Bring your ideas to life for $1/month](https://shopify.pxf.io/ZQJOkq)

## Contents

- [Community](#community)
- [Documentation](#documentation)
- [Front-end Development](#front-end-development)
- [Mobile](#mobile)
- [Libraries](#libraries)
  - [Ruby](#ruby)
  - [Python](#python)
  - [JavaScript](#javascript)
  - [DotNet](#dotnet)
  - [Elixir](#elixir)
  - [Haskell](#haskell)
  - [Java](#java)
  - [Golang](#golang)
  - [PHP](#php)
  - [R](#r)
  - [Rust](#rust)
- [Examples](#examples)
  - [JavaScript Examples](#javascript-examples)
  - [PHP Examples](#php-examples)
  - [Python Examples](#python-examples)
  - [Ruby Examples](#ruby-examples)
  - [Elixir Examples](#elixir-examples)
- [Code Snippets](#code-snippets)
- [Tools](#tools)

## Community

- [@ShopifyPartners](https://twitter.com/ShopifyPartners) - The Official Shopify Partners Twitter account.
- [@ShopifyDevs](https://twitter.com/ShopifyDevs) - A Shopify Devs Team Twitter account.
- [Community Discussion Forums](https://community.shopify.com/) - Discussing eCommerce best practices and how to have a successful online store.
- [Shopify Partners Slack Community](https://shopifypartners.slack.com/) - Official Shopify Partners Slack Channel. If you are a Partner, go to your resources tab and it should be linked there as well.
- [Shopify Devs Discord Community](https://discord.com/invite/mdyHp6km2B) - Official Shopify Devs Discord Channel.
- [eCommTalk](https://ecommtalk.com/) - A Slack Community created to bring Shopify lovers together.
- [/r/shopify](https://www.reddit.com/r/shopify/) - The Shopify Reddit Community.

## Documentation

- [Developer changelog](https://shopify.dev/changelog) - The Official Developer Changelog blog with important changes to APIs and other developer products.
- [Developer guides](https://shopify.dev) - If you're new to developing apps for Shopify, take a look at the official guides to get an overview of the process.
- [Shopify - The OAuth flow for Authentication](https://shopify.dev/apps/auth/oauth) - This guide introduces the OAuth flow for public apps and custom apps that are created in the Partner Dashboard.
- [Shopify Partner Account](https://www.shopify.com/partners?ref=vitalogy) - If you don't have a Shopify Partner account yet head over here and create one, you'll need it before you can start developing apps.
- [Requirements for apps in the Shopify App Store](https://shopify.dev/apps/store/requirements) - For submitting apps to the Shopify App Store.
- [Everything You Need to Know About Development Stores](https://www.shopify.com/partners/blog/development-stores?ref=vitalogy) - You need to be familiar with development stores. They are used for testing and installing your apps, providing example stores running your app, and for signing up clients to Shopify. .

## Front-end Development

### UI/UX

- [Shopify Polaris](https://polaris.shopify.com) - Polaris is a React component library designed to help developers create the best experience for merchants. [GitHub](https://github.com/Shopify/polaris) :sunny:.
- [Shopify Polaris for Admin Figma UI kit](https://www.figma.com/@shopify) - Polaris for Admin Web UI kit is now available in Figma. You can access the full kit in Figma with reusable components and up-to-date Polaris guidelines, icons, and color palette.
- [Polaris icon explorer](https://polaris.shopify.com/icons) - A collection of simple and informative icons that draw on the visual language of the Polaris design system.
- [Shopify Polaris design system for Vue JS](https://github.com/ownego/polaris-vue) - Polaris Vue based on Shopify Polaris style guide, built especially for Vue 3.

### Dawn

[Dawn](https://shopify.dev/themes/tools/dawn) is Shopify's reference theme, which is built for performance, flexibility, and ease of use. It uses [Online Store 2.0](https://shopify.dev/themes/os20) features

- [Shopify Dawn](https://github.com/Shopify/dawn) - Shopify's first source available reference theme, with Online Store 2.0 features and performance built-in.
- [Figma - Shopify's Dawn Theme - Online Store 2.0](https://www.figma.com/community/file/1017615468313501249) - If you're designing themes for the new Shopify online store 2.0 and you wished you had the Dawn theme as a nicely put together Figma file.

### Liquid Template

- [Liquid](https://shopify.github.io/liquid/) - Liquid is safe, customer-facing template language for flexible web apps.
- [Liquid Cheat Sheet](https://www.shopify.com/partners/shopify-cheat-sheet) - A resource for building Shopify Themes with Liquid.
- [Liquid template language reference](https://shopify.dev/api/liquid) - Liquid is the backbone of all Shopify themes, and is used to load dynamic content to the pages of online stores.

### Others

- [Liquid Ajax Cart](https://liquid-ajax-cart.js.org) - A JavaScript library for building Shopify Ajax-carts using Liquid templates.
- [Cart.js](https://cartjs.org) - A JavaScript library to power your Shopify theme's cart.
- [Helium](https://github.com/idbakkasse/helium) - A Shopify theme environment from scratch ⚙️, with Online Store 2.0 features. Built with performance ⚡️ and best practices in mind, has hot Module Reloading on SASS/ES6 file changes for rapid development and many more other features out of the box.
- [Shopify Theme Lab](https://github.com/uicrooks/shopify-theme-lab) - Customizable modular development environment for blazing-fast Shopify theme creation, bundled with Vue.js and Tailwind CSS.
- [Shopify Packer](https://github.com/hayes0724/shopify-packer) - Modern development tool for Shopify using Webpack 5. Easy to extend and customize, zero build config, compatible with Slate and existing websites.
- [Setup and use Shopify metafields in your custom storefront](https://www.zauberware.com/en/articles/2019/setup-and-use-shopify-metafields-in-your-custom-storefront/) - Using GraphQL API to create and get Shopify Metafields.
- [Foundationify](https://github.com/lukebussey/foundationify) - A theme for Shopify based on the responsive Zurb Foundation 5 framework.
- [Uptown CSS](https://github.com/shoppad/uptowncss/) - Uptown CSS is a semantic toolkit designed to help developers build fully-responsive Shopify Apps.
- [Slate](https://github.com/Shopify/slate) - Slate is a toolkit for developing Shopify themes, designed to assist your workflow and speed up the process of developing, testing, and deploying themes. ⚠️
- [Shopify Skeleton theme](https://github.com/Shopify/skeleton-theme) - A simplified Shopify theme. ⚠️
- [shopify-css-import](https://github.com/Shopify/shopify-css-import) - Add CSS import functionality to Shopify theme development with Grunt.js or Gulp.js. ⚠️

## Mobile

You can use the iOS and Android Buy SDK to integrate Shopify checkout into your mobile applications. This lets you sell any of your physical products through the app and track sales info in your Shopify Admin. [Learn more here›](https://shopify.dev/custom-storefronts/tools).

### Android

- [Shopify Mobile for Android](https://www.shopify.com/install/android)
- [Shopify Mobile Buy SDK](https://github.com/Shopify/mobile-buy-sdk-android)

### iOS

- [Shopify Mobile for iPhone](https://www.shopify.com/install/mobile)
- [Shopify Mobile Buy SDK](https://github.com/Shopify/mobile-buy-sdk-ios)

###

## Libraries

You can use official Shopify libraries or any of the third party libraries below for authenticating and interacting with the Shopify API.

### Ruby

- [shopify_api](https://github.com/Shopify/shopify_api) - Shopify Ruby API.
- [shopify_app](https://github.com/Shopify/shopify_app) - A Ruby on Rails Engine.
- [omniauth-shopify-oauth2](https://github.com/Shopify/omniauth-shopify-oauth2) - Authentication using OmniAuth.
- [shopify-sinatra-app](https://github.com/kevinhughes27/shopify-sinatra-app) - Shopify Sinatra App.
- [lucid_shopify](https://github.com/lucidnz/lib-ruby-lucid-shopify) - Basic interfaces to the Shopify API.

### Python

- [shopify_python_api](https://github.com/Shopify/shopify_python_api) - ShopifyAPI library allows Python developers to programmatically access the admin section of stores.
- [django-shopify-auth](https://github.com/discolabs/django-shopify-auth) - A package for adding Shopify authentication to a Django app.
- [Django Shopify Webhook](https://github.com/discolabs/django-shopify-webhook) - A package for receiving Shopify Webhooks in Django.

### JavaScript

- [@shopify/koa-shopify-auth](https://github.com/Shopify/koa-shopify-auth) - Shopify Auth for Koa HTTP middleware framework.
- [@shopify/koa-shopify-graphql-proxy](https://github.com/Shopify/quilt/blob/main/packages/koa-shopify-graphql-proxy/README.md) - Shopify GraphQL Proxy for Koa HTTP middleware framework.
- [@shopify/koa-shopify-webhooks](https://github.com/Shopify/quilt/tree/main/packages/koa-shopify-webhooks) - Shopify Webhooks Middleware for Koa HTTP middleware framework.
- [js-buy-sdk](https://github.com/Shopify/js-buy-sdk) - Shopify JavaScript Buy SDK.
- [shopify-api-node](https://github.com/MONEI/Shopify-api-node) - Node.js Shopify connector.
- [shopify-node-api](https://github.com/christophergregory/shopify-node-api) - OAuth2 Module for Shopify API.
- [shopify-nextjs-toolbox](https://github.com/ctrlaltdylan/shopify-nextjs-toolbox) - A set of server side and client side NextJs utilities for integrating with Shopify's OAuth & App Bridge authentication.
- [nestjs-shopify](https://github.com/nestjs-shopify/nestjs-shopify) - Packages to develop Shopify application using NestJS.

### DotNet

- [nozzlegear/ShopifySharp](https://github.com/nozzlegear/ShopifySharp) - A .NET library for Shopify.
- [agileharbor/shopifyAccess](https://github.com/skuvault-integrations/shopifyAccess) - Shoppify API .NET wrapper.

### Elixir

- [sticksnleaves/exshopify](https://github.com/sticksnleaves/exshopify) - Elixir client for the Shopify API.
- [orbit-apps/elixir-shopifyapi](https://github.com/orbit-apps/elixir-shopifyapi) - ShopifyAPI and Plug.ShopifyAPI Elixir client.

### Haskell

- [haskell-shopify](https://github.com/aaronlevin/haskell-shopify) - A type-safe Haskell client for the Shopify API.

### Java

- [shopify-api-java-wrapper](https://github.com/SevenSpikes/shopify-api-java-wrapper) - The Java wrapper for the Shopify API.

### Golang

- [gopify](https://github.com/oussama4/gopify) - A simple package for developing Shopify applications in Go.
- [bold-commerce/go-shopify](https://github.com/bold-commerce/go-shopify) - Go client for the Shopify API.
- [go-shopify](https://github.com/kiwih/go-shopify) - Golang tool for connecting to Shopify's API.
- [shoauth](https://github.com/darrenpeters/shoauth) - Shopify oauth (oauth2) middleware for Golang.

### PHP

- [Shopify API Library for PHP](https://github.com/Shopify/shopify-php-api) - Official library provides support for PHP Shopify apps to access the Shopify Admin API 🚀.
- [pizdata/oauth2-shopify-php](https://github.com/pizdata/oauth2-shopify-php) - Shopify Provider for the OAuth 2.0 Client.
- [multidimension-al/oauth2-shopify](https://github.com/multidimension-al/oauth2-shopify) - Shopify's OAuth 2.0 support for the PHP League's OAuth 2.0 Client.
- [ShopifyExtras/PHP-Shopify-API-Wrapper](https://github.com/ShopifyExtras/PHP-Shopify-API-Wrapper) - Guzzle-based API client.
- [phpclassic/php-shopify](https://github.com/phpclassic/php-shopify) - PHP SDK for Shopify API.
- [ZfrShopify](https://github.com/zf-fr/zfr-shopify) - Guzzle client around Shopify API.
- [Shopify API Package for Laravel](https://github.com/joshrps/laravel-shopify-API-wrapper) - A Laravel API Wrapper.
- [donutdan4114/shopify](https://github.com/donutdan4114/shopify) - A simple Shopify PHP SDK for private apps to easily interact with the Shopify API.
- [slince/shopify-api-php](https://github.com/slince/shopify-api-php) - Shopify API Client for PHP.
- [ohmybrew/Basic-Shopify-API](https://github.com/osiset/Basic-Shopify-API) - A simple, tested, API wrapper for Shopify using Guzzle for REST and GraphQL.
- [osiset/laravel-shopify](https://github.com/osiset/laravel-shopify) - A full-featured Laravel package for aiding in Shopify App development.
- [buy-button-wordpress](https://github.com/Shopify/buy-button-wordpress) - Wordpress plugin for the Buy Button.
- [bold-shopify-toolkit](https://github.com/bold-commerce/bold-shopify-toolkit) - A Symfony Based Shopify api wrapper.
- [oseintow/laravel-shopify](https://github.com/oseintow/laravel-shopify) - Laravel Shopify is a simple package which helps to build robust integration into Shopify.
- [tothjmt/Laravel-Shopify](https://github.com/tothjmt/Laravel-Shopify) - A Laravel / Shopify API Wrapper.
- [CakePHP Plugin](https://github.com/cmcdonaldca/CakePHP-Shopify-Plugin) - A simple plugin for CakePHP.

### R

- [shopifyr](https://github.com/charliebone/shopifyr/) - Aims to provide an easy-to-use interface to the Shopify Admin API within R.

### Rust

- [Ventmere/shopify](https://github.com/Ventmere/shopify/) - Shopify API Client for Rust.

## Examples

A Open Source Projects

### JavaScript Examples

- [Shopify App Node](https://github.com/Shopify/shopify-app-template-node) - Boilerplate to create an embedded Shopify app made with Node, Next.js, Shopify-koa-auth, Polaris, and App Bridge React :sunny:.
- [Storefront API Examples](https://github.com/Shopify/storefront-api-examples) - Example custom storefront applications built on Shopify's Storefront API.
- [Product Reviews Sample App](https://github.com/Shopify/product-reviews-sample-app) - Sample app was built as a reference for how Shopify Developer tools can be used together to create a fully functional application.
- [SmallAwesomeShop](https://github.com/JsssCode/SmallAwesomeShop) - An Angular 7 App example using Shopify's Storefront GraphQL API.
- [Next.JS App with Session Token](https://github.com/ctrlaltdylan/shopify-session-tokens-nextjs) - An example of a Shopify App powered by NextJS with Session Tokens (no custom server necessary).
- [Vue Storefront 2](https://github.com/vuestorefront/shopify) - Vue Storefront 2 integration for Shopify.
- [Shopify app with Node.js, MongoDB, React.js and Express](https://github.com/kinngh/shopify-node-express-mongodb-app) - Boilerplate embedded app made with Express.js, MongoDB and React.js with webhooks, GDPR routes, monetization and more hooked up and ready to go.
- [Shopify App Starter (Typescript, Mongo, Express, React)](https://github.com/yoMerce/shopify-app-starter) - A shopify app starter written in Typescript. It uses Mongodb, Express and React.
- [Shopify Discount App Components)](https://github.com/Shopify/discount-app-components) - A library of discounts-focused React components to help in building Shopify apps.
- [Shopify App Template Remix](https://github.com/Shopify/shopify-app-template-remix) - A template for building a Shopify app using the Remix framework.
- [Shopify App Vue Template](https://github.com/Mini-Sylar/shopify-app-vue-template) - Create a Shopify App with node and vue 3.

### PHP Examples

- [shopify-app-php](https://github.com/Shopify/shopify-app-template-php) - Example Shopify PHP app (Laravel).

### Python Examples

- [shopify_django_app](https://github.com/shopify/shopify_django_app) - Shopify Django App Example.

### Ruby Examples

- [shopify-fulfillment-integration](https://github.com/Shopify/shopify-fulfillment-integration) - Example Fulfillment Service Integration with Shopify.
- [Hosted Payment Simulator](https://github.com/Shopify/hosted-payment-sim) - Example of using the [Hosted Payment SDK](https://shopify.dev/apps/payments/hosted-payment-sdk).
- [shopify-sim](https://github.com/urbandictionary/shopify-sim) - Sinatra app to preview a Shopify theme locally.
- [shopify-surge-pricing](https://github.com/kevinhughes27/shopify-surge-pricing) - A demo of surge pricing for Shopify based on cart update webhooks.
- [shopify-tax-receipts](https://github.com/kevinhughes27/shopify-tax-receipts) - Shopify app for automatically sending tax receipts when specified products are purchased.
- [partner-metrics-for-shopify](https://github.com/forsbergplustwo/partner-metrics-for-shopify) - Metrics Dashboard for Shopify Partners, on Rails.
- [Shopify app starter kit](https://github.com/ASoftCo/shopify-app-starter-kit) - A Shopify app boilerplate written in Ruby on Rails with appropriate tools to get your Shopify app up and running quickly 🚀.

### Elixir Examples

- [orbit-apps/elixir-shopify-app](https://github.com/orbit-apps/elixir-shopify-app) - Elixir Shopify App boilerplate (Phoenix).

## Code Snippets

- [freakdesign/Shopify-code-snippets](https://github.com/freakdesign/Shopify-code-snippets) - Shopify Code Snippets examples and tips.
- [vikrantnegi/shopify-code-snippets](https://github.com/vikrantnegi/shopify-code-snippets) - A compilation of code snippets for Shopify developers.
- [gocomet/snippets](https://github.com/gocomet/snippets) - A collection of code snippets, generally for use with Shopify.

## Tools

### Browser extensions

- [Shopify Theme Inspector for Chrome](https://chrome.google.com/webstore/detail/shopify-theme-inspector-f/fndnankcflemoafdeboboehphmiijkgp) - Profile and debug Liquid template on your Shopify store.
- [Shopify App Detector](https://chrome.google.com/webstore/detail/shopify-app-detector-by-f/lhfdhjladfcmghahdbcmlceajdlbkale) - Detect which apps and what theme a Shopify store is using. [GitHub](https://github.com/feracommerce/shopify_app_detector)
- [Shopify Theme Wizard](https://chrome.google.com/webstore/detail/shopify-app-detector-by-e/fhkelfkhcaokghlkckfgjoejhanelped) - Detect which theme a Shopify store is using.

### Command Line Tools

- [Shopify CLI](https://github.com/Shopify/shopify-cli) - Shopify CLI helps you build against the Shopify platform faster 🚀.
- [Shopify Theme Kit](https://github.com/Shopify/themekit) - Shopify theme development command line tool.
- [Shopify Theme Check](https://github.com/Shopify/theme-check) - The Ultimate Shopify Theme Linter.
- [ziplinesFly](http://ziplines.pixelcab.in) - Fly into Shopify development with ease workflow.
- [grunt-shopify](https://github.com/wilr/grunt-shopify) - Grunt plug-in for publishing Shopify theme assets.
- [Shopify Development Tools](https://github.com/ScreenStaring/shopify-dev-tools) - Assists with the development/maintenance of apps and stores: manipulate metafields and webhooks, open admin pages, retrieve information about shops, etc.
- [Shopify ID Export](https://github.com/ScreenStaring/shopify_id_export) - Dump Shopify product and variant IDs —along with other identifiers— to a CSV or JSON file.
- [Shopify Email Template Sync Client](https://github.com/mash/shync) - Shync can checkout/download the Shopify email templates from your Shopify store admin to your local machine, and push/sync your email templates on your local machine to Shopify.

### Editor
- [Shopify Liquid](https://marketplace.visualstudio.com/items?itemName=Shopify.theme-check-vscode) - Official VS Code extension for Shopify Liquid powered by Theme Check the Liquid linter and language server for online store themes ([Source Code](https://github.com/Shopify/theme-tools/tree/main/packages/vscode-extension)).
- [VS Code Liquid](https://github.com/panoply/vscode-liquid) - Liquid VS Code extension that supports formatting, syntax highlighting and more.
- [Shopify Textmate Bundle](https://github.com/meeech/shopify.tmbundle) - A Textmate Bundle for interacting with Shopify Theme Assets.
- [vim-liquid](https://github.com/tpope/vim-liquid) - Vim Liquid runtime files.
- [VS Code Liquid Snippets Extension](https://marketplace.visualstudio.com/items?itemName=killalau.vscode-liquid-snippets) - An extension for the VS Code editor with autocomplete snippets for Shopify Liquid.

### Services

- [Ngrok](https://ngrok.com) - Ngrok is a tool that makes it easy to expose your development environment to Internet.
- [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) - Cloudflare Tunnel to configure local server using cloudflare.
- [RequestBin](https://requestbin.net/) - It gives you a bucket to capture external requests. This is useful for seeing what the content of a [Shopify Webhook](https://help.shopify.com/en/manual/orders/notifications/webhooks) are.
- [Hookdeck](https://hookdeck.com/) - Hookdeck is a tool to monitor your [Shopify Webhooks](https://shopify.dev/api/admin/rest/reference/events/webhook) with custom retry logic, alerts and filtering.
- [Chaos Genius](https://github.com/chaos-genius/chaos_genius) - ML powered analytics engine for outlier/anomaly detection and root cause analysis. Connects with Shopify, Google & Facebook Ads, Postgres, Redshift, Snowflake, etc.
- [DeployBot](https://deploybot.com/) - Shopify integration in DeployBot is a great way to streamline the development, review, and deployment of your store themes.

### Utilities

- [Shopify Product CSVs and Images](https://github.com/shopifypartners/shopify-product-csvs-and-images) - Get your Shopify development stores started with great product data.
- [Sketch Shopify Data Populator](https://github.com/shopifypartners/sketch-shopify-data-populator) - A Sketch App plugin to populate your designs with meaningful ecommerce data.
- [City Ecommerce UI Kit](https://github.com/shopifypartners/City-Ecommerce-UI-Kit) - City is our free ecommerce UI kit based on a fictional fashion apparel shop. (Prototyping Shopify Store design)

### Raycast Extension
- [Search Shopify Liquid Documentation](https://www.raycast.com/maximedaraize/search-shopify-liquid-documentation) - Raycast extension to preview and access Shopify documentation.
- [Shopify Developer Changelog](https://www.raycast.com/sandypockets/shopify-developer-changelog) - Raycast extension listing the Shopify changlog.
