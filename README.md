# Workshop for build VUE + Vuetify

## Introduction

This workshop is designed to help you build a simple web application using Vue.js and Vuetify. We will cover the basics of setting up a Vue project, integrating Vuetify for UI components, and deploying the application.

## Prerequisites

- Basic knowledge of JavaScript and HTML
- Node.js and npm installed on your machine
- A code editor (like Visual Studio Code)
- Git installed on your machine
- Basic understanding of Git
- A web browser (like Chrome or Firefox)
- A terminal or command prompt
- A GitHub account (optional, for deployment)
- A web server (like Apache or Nginx) for deployment
- A cloud service provider (like AWS, Azure, or Google Cloud) for deployment (optional)
- A domain name (optional, for deployment)
- Basic knowledge of REST APIs (optional, for backend integration)
- Basic knowledge of JSON (optional, for data handling)
- Basic knowledge of CSS (optional, for styling)
- Basic knowledge of responsive design (optional, for mobile compatibility)
- Basic knowledge of accessibility (optional, for web accessibility)
- Basic knowledge of SEO (optional, for search engine optimization)

## Getting Started

```bash
npm install -g @vue/cli
vue create vue-vuetify-workshop
cd vue-vuetify-workshop
vue add vuetify
vue add router
```

## edit package.json

```json
{
  "name": "vue-vuetify-workshop",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "serve": "vue-cli-service serve",
    "build": "vue-cli-service build",
    "lint": "vue-cli-service lint"
  },
  "dependencies": {
    "@mdi/font": "5.9.55",
    "axios": "^1.7.9",
    "core-js": "^3.8.3",
    "roboto-fontface": "*",
    "vue": "^3.2.13",
    "vue-router": "^4.0.3",
    "vuetify": "3.8.2",
    "webfontloader": "^1.0.0"
  },
  "devDependencies": {
    "@babel/core": "^7.12.16",
    "@babel/eslint-parser": "^7.12.16",
    "@vue/cli-plugin-babel": "~5.0.0",
    "@vue/cli-plugin-eslint": "~5.0.0",
    "@vue/cli-plugin-router": "~5.0.0",
    "@vue/cli-service": "~5.0.0",
    "eslint": "^7.32.0",
    "eslint-plugin-vue": "^8.0.3",
    "vue-cli-plugin-vuetify": "~2.5.8",
    "webpack-plugin-vuetify": "3.1.1"
  },
  "eslintConfig": {
    "root": true,
    "env": {
      "node": true
    },
    "extends": [
      "plugin:vue/vue3-essential",
      "eslint:recommended"
    ],
    "parserOptions": {
      "parser": "@babel/eslint-parser"
    },
    "rules": {}
  },
  "browserslist": [
    "> 1%",
    "last 2 versions",
    "not dead",
    "not ie 11"
  ],
  "overrides": { 
    "acorn": "8.8.0",
    "cross-spawn": "7.0.5",
    "postcss": "8.4.31"
  },
  "resolutions": {
    "postcss": "8.4.31",
    "cross-spawn": "7.0.5",
    "**/cross-spawn": "7.0.5",
    "foreground-child/cross-spawn": "7.0.5"
  }
}

```
