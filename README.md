# Zerops x Adonis.js

A bare-bones example of Adonis.js with postgress. It provides a lightweight starting point for building web applications with minimal configuration. Zerops makes deploying and running Adonis.js apps, a breeze.

![Adonis](https://github.com/zeropsio/recipe-shared-assets/blob/main/covers/svg/cover-adonis.svg)

AdonisJS is a TypeScript-first web framework for Node.js. You can use it to create a full-stack web application or a JSON API server.

## Recipe features

- Latest version of **Adonis.js** running on a **Zerops Node.js** and **Postgres** service.

<br/>

## Production vs. development

This recipe is ready for production as is, and will scale horizontally by adding more containers in case of high traffic surges. If you want to achieve the highest baseline reliability and resiliace, start with at least two containers (add `minContainers: 2` in recipe YAML in the `app` service section, or change the minimum containers in "Automatic Scaling configuration" section of service detail).

<br/>

## Changes made over the default installation

If you want to modify your existing Adonis.js app to efficiently run on Zerops, there are no changes needed in the codebase on top of the standard installation, just add [zerops.yml](https://github.com/zeropsio/recipe-adonis/blob/main/zerops.yml) to your repository.

<br/>

Need help setting your project up? Join [Zerops Discord community](https://discord.com/invite/WDvCZ54).
