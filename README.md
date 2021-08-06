<p align="center">
  <a href="https://www.npmjs.com/package/@femike/swagger-protect" target="blank"><img src="dist/favicon.svg" width="120" alt="Swagger Protect Logo" /></a>
</p>
<p align="center">Swagger Protect UI</p> 
<p align="center">
<a href="https://www.npmjs.com/org/femike"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/org/femike"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/org/femike"><img src="https://img.shields.io/npm/dm/@femike/swagger-protect-ui.svg" alt="NPM Downloads" /></a>
<!-- <a href="#"><img src="https://img.shields.io/badge/donate-PayPal-ff3f59.svg" alt="Donate PayPal" /></a> -->
<a href="https://yoomoney.ru/to/41001486944398/250"><img src="https://img.shields.io/badge/donate-%D0%AEMoney-blueviolet.svg" alt="Donate ЮMoney" /></a>
</p>

## Installation

```bash
$ npm install @femike/swagger-protect-ui

# OR

$ yarn add @femike/swagger-protect-ui
```

# User Interface For Module Swagger Protect

See: [@femike/swagger-protect](https://www.npmjs.com/package/@femike/swagger-protect)

<p align="center"><img width="540" src="https://github.com/femike/swagger-protect-ui/blob/main/images/screen_1.png"></img></p>

## Vue 3 + Typescript + Vite

This template should help get you started developing with Vue 3 and Typescript in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur). Make sure to enable `vetur.experimental.templateInterpolationService` in settings!

### If Using `<script setup>`

[`<script setup>`](https://github.com/vuejs/rfcs/pull/227) is a feature that is currently in RFC stage. To get proper IDE support for the syntax, use [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) instead of Vetur (and disable Vetur).

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates. However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can use the following:

### If Using Volar

Run `Volar: Switch TS Plugin on/off` from VSCode command palette.

### If Using Vetur

1. Install and add `@vuedx/typescript-plugin-vue` to the [plugins section](https://www.typescriptlang.org/tsconfig#plugins) in `tsconfig.json`
2. Delete `src/shims-vue.d.ts` as it is no longer needed to provide module info to Typescript
3. Open `src/main.ts` in VSCode
4. Open the VSCode command palette
5. Search and run "Select TypeScript version" -> "Use workspace version"
