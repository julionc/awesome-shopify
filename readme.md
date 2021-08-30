# Awesome Shopify [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[<img src="shopify.png" width="250px" align="right" alt="Shopify">](https://www.shopify.com/?ref=vitalogy)

> A curated list of awesome [Shopify](https://www.shopify.com) resources, libraries and open source projects.

[Shopify](https://www.shopify.com/blog/what-is-shopify?ref=vitalogy) is a popular e-commerce platform that allows to build and manage online stores.
If you want to contribute, please read the [contribution guidelines](https://github.com/julionc/awesome-shopify/blob/master/contributing.md).
Thanks to all [contributors](https://github.com/julionc/awesome-shopify/graphs/contributors), you're awesome and wouldn't be possible without you!

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
- [Shopify Devs Discord Community](https://discord.gg/mdyHp6km2B) - Official Shopify Devs Discord Channel.
- [eCommTalk](http://ecommtalk.com/) - A Slack Community created to bring Shopify lovers together.
- [/r/shopify](https://www.reddit.com/r/shopify) - The Shopify Reddit Community.

## Documentation

- [Developer changelog](https://developers.shopify.com/changelog) - The Official Developer Changelog blog with important changes to APIs and other developer products.
- [Developer guides](https://help.shopify.com/api/guides) - If you're new to developing apps for Shopify, take a look at the official guides to get an overview of the process.
- [Shopify - The OAuth flow for Authentication](https://help.shopify.com/api/guides/authentication/oauth) - This guide will walk you through the OAuth Authorization process.
- [Shopify Partner Account](https://www.shopify.com/partners?ref=vitalogy) - If you don't have a Shopify Partner account yet head over here and create one, you'll need it before you can start developing apps.
- [App requirements checklist](https://help.shopify.com/api/listing-in-the-app-store/app-review-checklist) - For submitting apps to the Shopify App Store.
- [Everything You Need to Know About Development Stores](https://www.shopify.com/partners/blog/development-stores?ref=vitalogy) - Understanding development stores.

## Front-end Development

### UI/UX

- [Shopify Polaris](https://polaris.shopify.com) - Polaris is a React component library designed to help developers create the best experience for merchants. [GitHub](https://github.com/Shopify/polaris) :sunny:.
- [Slate](https://github.com/Shopify/slate) - Slate is a toolkit for developing Shopify themes, designed to assist your workflow and speed up the process of developing, testing, and deploying themes.
- [Shopify Polaris UI Kit](https://polaris.shopify.com/resources/polaris-ui-kit) - The Sketch UI kit provides a set of reusable components to help you craft great products for Shopify.
- [Polaris icon explorer](https://polaris-icons.shopify.com) - A collection of simple and informative icons that draw on the visual language of the Polaris design system.
- [Shopify Theme Lab](https://github.com/uicrooks/shopify-theme-lab) - Customizable modular development environment for blazing-fast Shopify theme creation, bundled with Vue.js and Tailwind CSS.
- [Shopify Packer](https://github.com/hayes0724/shopify-packer) - Modern development tool for Shopify using Webpack 5. Easy to extend and customize, zero build config, compatible with Slate and existing websites.

### CSS Frameworks

- [Foundationify](https://github.com/lukebussey/foundationify) - A theme for Shopify based on the responsive Zurb Foundation 5 framework.
- [Uptown CSS](https://github.com/shoppad/uptowncss/) - Uptown CSS is a semantic toolkit designed to help developers build fully-responsive Shopify Apps.

### Liquid Template

- [Liquid](https://shopify.github.io/liquid/) - Liquid is safe, customer-facing template language for flexible web apps.
- [Liquid Cheat Sheet](https://www.shopify.com/partners/shopify-cheat-sheet) - A resource for building Shopify Themes with Liquid.
- [Liquid template language reference](https://shopify.dev/docs/themes/liquid/reference) - Liquid is the backbone of all Shopify themes, and is used to load dynamic content to the pages of online stores.

### Others

- [Shopify Dawn](https://github.com/Shopify/dawn) - Shopify's first source available reference theme, with Online Store 2.0 features and performance built-in.
- [Cart.js](https://cartjs.org) - A JavaScript library to power your Shopify theme's cart.
- [Shopify Skeleton theme](https://github.com/Shopify/skeleton-theme) - A simplified Shopify theme.
- [shopify-css-import](https://github.com/Shopify/shopify-css-import) - Add CSS import functionality to Shopify theme development with Grunt.js or Gulp.js.
- [Setup and use Shopify metafields in your custom storefront](https://www.zauberware.com/en/articles/2019/setup-and-use-shopify-metafields-in-your-custom-storefront/) - Using GraphQL API to create and get Shopify Metafields.

## Mobile

You can use the iOS and Android Buy SDK to integrate Shopify checkout into your mobile applications. This lets you sell any of your physical products through the app and track sales info in your Shopify Admin. [Learn more here›](https://help.shopify.com/en/api/storefront-api/tools).

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
- [lucid_shopify](https://github.com/luciddesign/lucid_shopify) - Basic interfaces to the Shopify API.

### Python

- [shopify_python_api](https://github.com/Shopify/shopify_python_api) - ShopifyAPI library allows Python developers to programmatically access the admin section of stores.
- [django-shopify-auth](https://github.com/discolabs/django-shopify-auth) - A package for adding Shopify authentication to a Django app.
- [Django Shopify Webhook](https://github.com/discolabs/django-shopify-webhook) - A package for receiving Shopify Webhooks in Django.

### JavaScript

- [@shopify/koa-shopify-auth](https://github.com/Shopify/quilt/tree/master/packages/koa-shopify-auth) - Shopify Auth for Koa HTTP middleware framework.
- [@shopify/koa-shopify-graphql-proxy](https://github.com/Shopify/quilt/blob/master/packages/koa-shopify-graphql-proxy/README.md) - Shopify GraphQL Proxy for Koa HTTP middleware framework.
- [@shopify/koa-shopify-webhooks](https://github.com/Shopify/quilt/tree/master/packages/koa-shopify-webhooks) - Shopify Webhooks Middleware for Koa HTTP middleware framework.
- [js-buy-sdk](https://github.com/Shopify/js-buy-sdk) - Shopify JavaScript Buy SDK.
- [shopify-api-node](https://github.com/MONEI/Shopify-api-node) - Node.js Shopify connector.
- [shopify-node-api](https://github.com/christophergregory/shopify-node-api) - OAuth2 Module for Shopify API.
- [shopify-nextjs-toolbox](https://github.com/ctrlaltdylan/shopify-nextjs-toolbox) - A set of server side and client side NextJs utilities for integrating with Shopify's OAuth & App Bridge authentication.

### DotNet

- [nozzlegear/ShopifySharp](https://github.com/nozzlegear/ShopifySharp) - A .NET library for Shopify.
- [agileharbor/shopifyAccess](https://github.com/agileharbor/shopifyAccess) - Shoppify API .NET wrapper.

### Elixir

- [sticksnleaves/exshopify](https://github.com/sticksnleaves/exshopify) - Elixir client for the Shopify API.
- [pixelunion/elixir-shopifyapi](https://github.com/pixelunion/elixir-shopifyapi) - ShopifyAPI and Plug.ShopifyAPI Elixir client.
- [shopify_elixir](https://github.com/sdn90/shopify_elixir) - A Shopify API library for Elixir.

### Haskell

- [haskell-shopify](https://github.com/aaronlevin/haskell-shopify) - A type-safe Haskell client for the Shopify API.

### Java

- [shopify-api-java-wrapper](https://github.com/SevenSpikes/shopify-api-java-wrapper) - The Java wrapper for the Shopify API.

### Golang

- [bold-commerce/go-shopify](https://github.com/bold-commerce/go-shopify) - Go client for the Shopify API.
- [go-shopify](https://github.com/kiwih/go-shopify) - Golang tool for connecting to Shopify's API.
- [shoauth](https://github.com/darrenpeters/shoauth) - Shopify oauth (oauth2) middleware for Golang.

### PHP

- [pizdata/oauth2-shopify-php](https://github.com/pizdata/oauth2-shopify-php) - Shopify Provider for the OAuth 2.0 Client.
- [multidimension-al/oauth2-shopify](https://github.com/multidimension-al/oauth2-shopify) - Shopify's OAuth 2.0 support for the PHP League's OAuth 2.0 Client.
- [ShopifyExtras/PHP-Shopify-API-Wrapper](https://github.com/ShopifyExtras/PHP-Shopify-API-Wrapper) - Guzzle-based API client.
- [phpclassic/php-shopify](https://github.com/phpclassic/php-shopify) - PHP SDK for Shopify API.
- [ZfrShopify](https://github.com/zf-fr/zfr-shopify) - Guzzle client around Shopify API.
- [Shopify API Package for Laravel](https://github.com/joshrps/laravel-shopify-API-wrapper) - A Laravel API Wrapper.
- [donutdan4114/shopify](https://github.com/donutdan4114/shopify) - A simple Shopify PHP SDK for private apps to easily interact with the Shopify API.
- [slince/shopify-api-php](https://github.com/slince/shopify-api-php) - Shopify API Client for PHP.
- [ohmybrew/Basic-Shopify-API](https://github.com/ohmybrew/Basic-Shopify-API) - A simple, tested, API wrapper for Shopify using Guzzle for REST and GraphQL.
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

- [Shopify App Node](https://github.com/Shopify/shopify-app-node) - Boilerplate to create an embedded Shopify app made with Node, Next.js, Shopify-koa-auth, Polaris, and App Bridge React :sunny:.
- [Storefront API Examples](https://github.com/Shopify/storefront-api-examples) - Example custom storefront applications built on Shopify's Storefront API.
- [Product Reviews Sample App](https://github.com/Shopify/product-reviews-sample-app) - Sample app was built as a reference for how Shopify Developer tools can be used together to create a fully functional application.
- [SmallAwesomeShop](https://github.com/JsssCode/SmallAwesomeShop) - An Angular 7 App example using Shopify's Storefront GraphQL API.
- [Shopify App with Node.js, MongoDB and Next.js](https://github.com/kinngh/shopify-node-mongodb-next-app) - Boilerplate embedded app made with Node.js, MongoDB and Next.js.
- [Next.JS App with Session Token](https://github.com/ctrlaltdylan/shopify-session-tokens-nextjs) - An example of a Shopify App powered by NextJS with Session Tokens (no custom server necessary).
- [Vue Storefront 2](https://github.com/vuestorefront/shopify) - Vue Storefront 2 integration for Shopify.

### Python Examples

- [shopify_django_app](https://github.com/shopify/shopify_django_app) - Shopify Django App Example.

### Ruby Examples

- [shopify-fulfillment-integration](https://github.com/Shopify/shopify-fulfillment-integration) - Example Fulfillment Service Integration with Shopify.
- [Hosted Payment Simulator](https://github.com/Shopify/hosted-payment-sim) - Example of using the [Hosted Payment SDK](https://docs.shopify.com/api/sdks/hosted-payment-sdk).
- [shopify-sim](https://github.com/urbandictionary/shopify-sim) - Sinatra app to preview a Shopify theme locally.
- [shopify-surge-pricing](https://github.com/kevinhughes27/shopify-surge-pricing) - A demo of surge pricing for Shopify based on cart update webhooks.
- [shopify-tax-receipts](https://github.com/kevinhughes27/shopify-tax-receipts) - Shopify app for automatically sending tax receipts when specified products are purchased.
- [partner-metrics-for-shopify](https://github.com/forsbergplustwo/partner-metrics-for-shopify) - Metrics Dashboard for Shopify Partners, on Rails.
- [Shopify app starter kit](https://github.com/ASoftCo/shopify-app-starter-kit) - A Shopify app boilerplate written in Ruby on Rails with appropriate tools to get your Shopify app up and running quickly 🚀.

### Elixir Examples

- [pixelunion/elixir-shopify-app](https://github.com/pixelunion/elixir-shopify-app) - Elixir Shopify App boilerplate (Phoenix).

## Code Snippets

- [freakdesign/Shopify-code-snippets](https://github.com/freakdesign/Shopify-code-snippets) - Shopify Code Snippets examples and tips.
- [vikrantnegi/shopify-code-snippets](https://github.com/vikrantnegi/shopify-code-snippets) - A compilation of code snippets for Shopify developers.
- [gocomet/snippets](https://github.com/gocomet/snippets) - A collection of code snippets, generally for use with Shopify.

## Tools

### App

- [Shopify developer-tools](https://github.com/shopifypartners/developer-tools) - A macOS app that connects to your Shopify store(s) and allows you to make authenticated calls to the Admin API, generate dummy data, and view and customize Polaris components. [More info](https://www.shopify.com/partners/blog/developer-tools).

### Browser extensions

- [Shopify Theme Inspector for Chrome](https://chrome.google.com/webstore/detail/shopify-theme-inspector-f/fndnankcflemoafdeboboehphmiijkgp) - Profile and debug Liquid template on your Shopify store.
- [ShopifyFD Dashboard Tool](https://github.com/freakdesign/shopifyFD) - Chrome extension to provide additional functionality to the Shopify dashboard.
- [Custom Fields for Shopify](https://github.com/freakdesign/shopify-custom-fields) - Chrome extension to navigate across the custom fields.
- [Shopify App Detector](https://chrome.google.com/webstore/detail/shopify-app-detector-by-f/lhfdhjladfcmghahdbcmlceajdlbkale) - Detect which apps and what theme a Shopify store is using. [GitHub](https://github.com/feracommerce/shopify_app_detector)
- [Shopify Theme Wizard](https://chrome.google.com/webstore/detail/shopify-theme-wizard-by-e/fhkelfkhcaokghlkckfgjoejhanelped) - Detect which theme a Shopify store is using.

### Command Line Tools

- [Shopify CLI](https://github.com/Shopify/shopify-cli) - Shopify CLI helps you build against the Shopify platform faster 🚀.
- [Theme Kit](https://github.com/Shopify/themekit) - Theme asset interaction library and management.
- [Shopify Theme Kit](https://github.com/Shopify/themekit) - Shopify theme development command line tool.
- [Shopify Theme Check](https://github.com/Shopify/theme-check) - The Ultimate Shopify Theme Linter.
- [ziplinesFly](http://ziplines.pixelcab.in) - Fly into Shopify development with ease workflow.
- [grunt-shopify](https://github.com/wilr/grunt-shopify) - Grunt plug-in for publishing Shopify theme assets.
- [Shopify Development Tools](https://github.com/ScreenStaring/shopify-dev-tools) - Assists with the development/maintenance of apps and stores: manipulate metafields and webhooks, open admin pages, retrieve information about shops, etc.
- [Shopify ID Export](https://github.com/ScreenStaring/shopify_id_export) - Dump Shopify product and variant IDs —along with other identifiers— to a CSV or JSON file.
- [Shopify Email Template Sync Client](https://github.com/mash/shync) - Shync can checkout/download the Shopify email templates from your Shopify store admin to your local machine, and push/sync your email templates on your local machine to Shopify.

### Editor

- [VS Code Liquid](https://github.com/panoply/vscode-liquid) - Liquid VS Code extension that supports formatting, syntax highlighting and more.
- [Shopify Textmate Bundle](https://github.com/meeech/shopify.tmbundle) - A Textmate Bundle for interacting with Shopify Theme Assets.
- [vim-liquid](https://github.com/tpope/vim-liquid) - Vim Liquid runtime files.
- [VS Code Liquid Snippets Extension](https://marketplace.visualstudio.com/items?itemName=killalau.vscode-liquid-snippets) - An extension for the VS Code editor with autocomplete snippets for Shopify Liquid.

### Services

- [Ngrok](https://ngrok.com) - Ngrok is a tool that makes it easy to expose your development environment to Internet.
- [RequestBin](http://requestbin.net) - It gives you a bucket to capture external requests. This is useful for seeing what the content of a [Shopify Webhook](https://help.shopify.com/en/manual/orders/notifications/webhooks) are.
- [Hoodeck](https://hookdeck.io) - Hoodeck is a tool to monitor your [Shopify Webhooks](https://help.shopify.com/api/reference/webhook) with custom retry logic, alerts and filtering. Useful to provide visbility and save time when working with webhooks in development and production.

### Utilities

- [Shopify Product CSVs and Images](https://github.com/shopifypartners/shopify-product-csvs-and-images) - Get your Shopify development stores started with great product data.
- [UnProduct-Shopify](https://github.com/byjord/UnProduct-Shopify) - Non-uniform test product data for the Shopify Platform. Use UnProduct-Shopify to simulate real world products.
- [Sketch Shopify Data Populator](https://github.com/shopifypartners/sketch-shopify-data-populator)
- [City Ecommerce UI Kit](https://github.com/shopifypartners/City-Ecommerce-UI-Kit) - City is our free ecommerce UI kit based on a fictional fashion apparel shop. (Prototyping Shopify Store design)
