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
    "@mdi/font": "^6.5.95",
    "@vue/cli-plugin-babel": "^5.0.8",
    "@vue/cli-plugin-router": "^5.0.8",
    "@vue/cli-plugin-vuex": "^5.0.8",
    "@vue/cli-service": "^5.0.8",
    "@vue/compiler-sfc": "^3.2.31",
    "core-js": "^3.6.5",
    "vuetify": "^2.5.10",
    "vue": "^3.2.31",
    "vue-router": "^4.0.12",
    "vuex": "^4.0.2"
  },
  "devDependencies": {
    "@vue/cli-plugin-e2e-cypress": "^5.0.8",
    "@vue/cli-plugin-unit-jest": "^5.0.8",
    "@vue/cli-service-global": "^5.0.8",
    "@vue/test-utils": "^2.0.0-rc.16",
    "babel-eslint": "^10.1.0",
    "cypress": "^9.1.1",
    "eslint": "^7.x.x",
    "eslint-plugin-vue": "^7.x.x"
  },
  "browserslist": [
    "> 1%",
    "last 2 versions"
  ]
}
```