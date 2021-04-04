# Vue 3 TailwindCss + PrimeVue Template
A Vue 3 application template implementing the [PrimeVue](https://www.primefaces.org/primevue/) UI Toolkit, [TailwindCss](https://tailwindcss.com/), Vue Router, and Fontawesome.

### Instantiation
Make sure Vue CLI and Vue CLI init are installed globally

```
npm i -g @vue/cli
npm i -g @vue/cli-init
```

To create a new project from this template run the following command

```shell
vue init s-schoen/vue3-tailwindcss-primevue my-project-directory
```

### Development

Using the Vue mustache syntax (`{{ }} `) in templates of components does not work as these get replaced by `vue init`. Use `v-text` instead.
