# Nuxt 3 Starter

This repo contains a fully configured nuxt 3 instance supporting:
- vite
- storybook
- vitest
- tailwind
- pinia.

## Do it yourself

### Initialize nuxt 3
Open a terminal, or from Visual Studio Code , open an integrated terminal and use the following command to create a new starter project:

```
npx nuxi init nuxt-app
```

Install the dependencies:

```
yarn install
```

### Add Storybook
Since Storybook (at the moment I wrote this document) is not supporting Nuxt-3, adding Storybook by `npx storybook init` won't work, so one has to add Storybook manually, by executing `yarn add -D @storybook/vue3` - if you want to have specific Storybook plugings, you'll need to add them manually as well.