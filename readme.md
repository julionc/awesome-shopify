# Awesome Shopify [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of amazingly awesome [Shopify](https://www.shopify.com/) resources, libraries and open source projects.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Table of Contents

- [Documentation](#documentation)
- [Community](#community)
- [Front-end Development](#front-end-development)
- [Libraries](#libraries)
  - [Ruby](#ruby-libraries)
  - [Python](#python-libraries)
  - [Javascript](#javascript-node-libraries)
  - [.NET](#dotnet)
  - [Elixir](#elixir)
  - [Haskell](#haskell)
  - [Java](#java)
  - [Golang](#golang)
  - [PHP](#php)
  - [R](#r)
- [Tools](#tools)
- [Examples](#examples)
  - [Ruby](#ruby-1)

## Documentation

  - [Developer guides](https://docs.shopify.com/api/guides) - If you're new to developing apps for Shopify, take a look at the official guides to get an overview of the process.
  - [Shopify’s OAuth flow for authentication](https://docs.shopify.com/api/guides/authentication/oauth) - This guide will walk you through the OAuth Authorization process.
  - [Shopify Partner Account](https://www.shopify.com/partners) - If you don't have a Shopify Partner account yet head over [here](https://www.shopify.com/partners) and create one, you'll need it before you can start developing apps.
  - [App requirements checklist for submitting apps to the Shopify App Store](https://docs.shopify.com/api/listing-in-the-app-store/app-review-checklist)

## Community

  - [@ShopifyPartners](https://twitter.com/ShopifyPartners) - The official Shopify Partners Twitter account.
  - [@ShopifyDevs](https://twitter.com/ShopifyDevs) - A Shopify Devs Team Twitter account.
  - [Discussion Forums](https://ecommerce.shopify.com/forums) - Discussing ecommerce best practices and how to have a successful online store.
  - [eCommTalk](http://ecommtalk.com/shopify/) - A Slack Community created to bring Shopify lovers together.
  - [/r/shopify](https://www.reddit.com/r/shopify) - The Shopify Reddit community.

## Front-end Development

### CSS Frameworks
  - [Timber](https://github.com/Shopify/Timber) - A faster and easier way to build Shopify themes.
  - [Foundationify](https://github.com/lukebussey/foundationify) - A theme for Shopify based on the responsive Zurb Foundation 5 framework.
  - [Shopify Embedded App Frontend Framework](https://github.com/microapps/Shopify-Embedded-App-Frontend-Framework)
  - [preamble](https://github.com/sdn90/preamble) - A Shopify theme framework with Babel and Webpack.

### Others
  - [Cart.js](https://cartjs.org/) - A Javascript library to power your Shopify theme's cart.
  - [gocomet/snippets](https://github.com/gocomet/snippets) - A collection of code snippets, generally for use with Shopify.
  - [Shopify Skeleton theme](https://github.com/Shopify/skeleton-theme) - A simplified Shopify theme.

## Libraries

You can use official Shopify libraries or any of the third party libraries below for authenticating and interacting with the Shopify API.

### Ruby
  - [shopify_api](https://github.com/Shopify/shopify_api) - Shopify Ruby API.
  - [shopify_app](https://github.com/Shopify/shopify_app) - A Ruby on Rails Engine.
  - [shopify-sinatra-app](https://github.com/kevinhughes27/shopify-sinatra-app) - Shopify Sinatra App.
  - [omniauth-shopify-oauth2](https://github.com/Shopify/omniauth-shopify-oauth2) - Authentication using OmniAuth.
  - [lucid_shopify](https://github.com/luciddesign/lucid_shopify) - Basic interfaces to the Shopify API.

### Python
  - [shopify_python_api](https://github.com/Shopify/shopify_python_api) - Shopify Python API
  - [django-shopify-auth](https://github.com/discolabs/django-shopify-auth)
  - [Django Shopify Webhook](https://github.com/discolabs/django-shopify-webhook)

### JavaScript (Node)
  - [shopify-api-node](https://github.com/microapps/shopify-api-node) - Node Shopify connector.
  - [Shopify API SDK for Node](https://github.com/ctalkington/node-shopify-api) - Shopify API SDK for Node.
  - [shopify-node-api](https://github.com/christophergregory/shopify-node-api) - OAuth2 Module for Shopify API.
  - [node-shopify-auth](https://github.com/jonpulice/node-shopify-auth) - Shopify Node.js + Express Auth Module
  - [meteor-shopify](https://github.com/froatsnook/meteor-shopify) - Shopify API access for Meteor.
  - [js-buy-sdk](https://github.com/Shopify/js-buy-sdk) - Shopify JavaScript Buy SDK

### .NET
  - [nozzlegear/ShopifySharp](https://github.com/nozzlegear/ShopifySharp) - A .NET library for Shopify.
  - [cmcdonaldca/shopify.net](https://github.com/cmcdonaldca/shopify.net) - Lightweight object-oriented .NET client.
  - [teference/shopify-dotnet](https://github.com/teference/shopify-dotnet) - Shopify API C#.NET SDK
  - [agileharbor/shopifyAccess](https://github.com/agileharbor/shopifyAccess) - Shoppify API .NET wrapper

### Elixir
  - [shopify_elixir](https://github.com/sdn90/shopify_elixir) - A Shopify API library for Elixir.

### Haskell
  - [haskell-shopify](https://github.com/aaronlevin/haskell-shopify) - A type-safe Haskell client for the Shopify API.

### Java
  - [shopify-api-java-wrapper](https://github.com/SevenSpikes/shopify-api-java-wrapper) - Java wrapper for the Shopify API.

### Golang
  - [go-shopify](https://github.com/kiwih/go-shopify) - Golang tool for connecting to Shopify's API.
  - [shoauth](https://github.com/darrenpeters/shoauth) - Shopify oauth (oauth2) middleware for Golang.

### PHP
  - [ShopifyExtras/PHP-Shopify-API-Wrapper](https://github.com/ShopifyExtras/PHP-Shopify-API-Wrapper) - Guzzle-based API client.
  - [ZfrShopify](https://github.com/zf-fr/zfr-shopify) - Guzzle client around Shopify API.
  - [Shopify API Package for Laravel](https://github.com/joshrps/laravel-shopify-API-wrapper) - A Laravel API Wrapper.
  - [CakePHP Plugin](https://github.com/cmcdonaldca/CakePHP-Shopify-Plugin) - A simple plugin for CakePHP.  
  - [tothjmt/Laravel-Shopify](https://github.com/tothjmt/Laravel-Shopify) - A Laravel / Shopify API Wrapper.
  - [donutdan4114/shopify](https://github.com/donutdan4114/shopify) - A simple Shopify PHP SDK for private apps to easily interact with the Shopify API.
  - [buy-button-wordpress](https://github.com/Shopify/buy-button-wordpress) - Wordpress plugin for the Buy Button

### R
  - [shopifyr](https://github.com/charliebone/shopifyr/) - Aims to provide an easy-to-use interface R

## Tools

### Browser extensions
  - [ShopifyFD Dashboard Tool](https://github.com/freakdesign/shopifyFD) - Chrome extension to provide additional functionality to the Shopify dashboard.
  - [Custom Fields for Shopify](https://github.com/freakdesign/shopify-custom-fields) - Chrome extension to navigate across the custom fields.

### Command Line Tools
  - [Theme Kit](https://github.com/Shopify/themekit) - Theme asset interaction library and management.
  - [Shopify Theme](https://github.com/shopify/shopify_theme) - A console tool for interacting with Shopify Theme Assets.
  - [ziplinesFly](http://ziplines.pixelcab.in/) - Fly into Shopify development with ease workflow.
  - [grunt-shopify](https://github.com/wilr/grunt-shopify) - Grunt plug-in for publishing Shopify theme assets.

### Editor
  - [Shopify Textmate Bundle](https://github.com/meeech/shopify.tmbundle) - A Textmate Bundle for interacting with Shopify Theme Assets.
  - [vim-liquid](https://github.com/tpope/vim-liquid) - Vim Liquid runtime files.

### Utilities
  - [ForwardHQ](https://forwardhq.com/) - Get a public link directly to the web project running on your computer.
  - [Ngrok](https://ngrok.com/) -  Ngrok is a tool that makes it easy to expose your development environment to Internet.  
  - [RequestBin](http://requestb.in) -  It gives you a bucket to capture external requests. This is useful for seeing what the content of a [Shopify Webhook](https://docs.shopify.com/api/reference/webhook) are.

## Examples
A Open Source Projects

### Ruby
  - [shopify-fulfillment-integration](https://github.com/Shopify/shopify-fulfillment-integration) - Example Fulfillment Service Integration with Shopify.
  - [Hosted Payment Simulator](https://github.com/Shopify/hosted-payment-sim) - Example of using the [Hosted Payment SDK](https://docs.shopify.com/api/sdks/hosted-payment-sdk).
  - [ShopifyPrintful](https://github.com/urbandictionary/shopify-printful) - A Ruby gem that synchronizes order item images between Shopify and Printful.
  - [shopify-sim](https://github.com/urbandictionary/shopify-sim) - Sinatra app to preview a Shopify theme locally.
  - [shopify-surge-pricing](https://github.com/kevinhughes27/shopify-surge-pricing) - A demo of surge pricing for Shopify based on cart update webhooks.
  - [shopify-tax-receipts](https://github.com/kevinhughes27/shopify-tax-receipts) - Shopify app for automatically sending tax receipts when specified products are purchased.
  - [partner-metrics-for-shopify](https://github.com/forsbergplustwo/partner-metrics-for-shopify) - Metrics Dashboard for Shopify Partners, on Rails.

### Python
  - [shopify_django_app](https://github.com/shopify/shopify_django_app) - Shopify Django App Example.

## License

    Creative Commons Attribution 4.0 International License (CC BY 4.0)

    http://creativecommons.org/licenses/by/4.0/