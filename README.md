# @vite-pwa/nuxt before install prompt using Vite

This repo using custom `install-pwa.ts` module to enable [beforeinstallprompt](https://developer.mozilla.org/en-US/docs/Web/API/BeforeInstallPromptEvent) event in Vite.

We're using `autoUpdate` register type, the options in Nuxt moved to the `install-pwa.ts` parameters and so you need to keep in sync `display` option in your pwa options and `installPwa` parameters.

Check the [defult layout](https://github.com/vite-pwa/nuxt/blob/main/playground/layouts/default.vue) to use `prompt` register type.


