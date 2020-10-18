# Symfony + Svelte + TailwindCSS

## Requisites

PHP 7.4
symfony binary
node
yarn

## Instructions

Clone repository, then:

```sh
composer install
yarn install
yarn watch # or yarn build
```

## Commands used to build this package

symfony new --version=lts --full symfony-svelte
composer require symfony/webpack-encore-bundle
yarn add svelte-loader svelte tailwindcss postcss-loader@3.0.0
php bin/console make:controller HomeController

## Kudos

[Setting up Symfony and Svelte](https://www.garthmortensen.com/setting-up-symfony-and-svelte/) by [Garth Mortensen](https://github.com/voldemortensen)
[How to use TailwindCSS with Symfony's Encore](https://stefanbauer.me/articles/how-to-use-tailwindcss-with-symfonys-encore) by [Stefan Bauer](https://github.com/stefanbauer)
