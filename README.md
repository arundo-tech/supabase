[![@nuxtjs/supabase](./docs/public/cover.jpg)](https://supabase.nuxtjs.org)

This is a friendly fork of [nuxt-modules/supabase](https://github.com/nuxt-modules/supabase).

The goals of this fork are :

* [ ] full support of nuxt SSG
* [ ] working example of a nuxt site in SSG mode
* [ ] manual switch to SSR or SSG mode
* [ ] auto-dectection of SSR/SSG mode
* [ ] working example of a magic link email auth with supabase
* [ ] working example of auto session token renewal
* [ ] working example of auth event (login, logout, renewal, ...)
* [ ] documentation on how to embed this module in a nuxt layer and use it in another nuxt site
* [ ] documentation on how to link to an existing nuxt site to allow dev/test/debug session on both projects
* [ ] migration to pnpm (?)
* [ ] an extended demo nuxt app with :
* [ ]   - some public nuxt content pages
* [ ]   - some public nuxt content pages
* [ ]   - some auth protected nuxt content pages
* [ ]   - a layer nuxt package (containing the auth logic)
* [ ]   - a basic rules set to define public/private routes for content pages


We will submit a PR when all the goals will be fullfilled.
This project will be deprecated when the PR will be merged mainstream.


# Nuxt Supabase

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![Nuxt][nuxt-src]][nuxt-href]
[![Volta][volta-src]][volta-href]

> [Supabase](https://supabase.com) module for [Nuxt](https://v3.nuxtjs.org)

- [✨ &nbsp;Changelog](https://github.com/nuxt-community/supabase-module/blob/main/CHANGELOG.md)
- [📖 &nbsp;Read the documentation](https://supabase.nuxtjs.org)
- [▶ &nbsp;Video](https://www.youtube.com/watch?v=jIyiRT6zT8Q)
- [👾 &nbsp;Demo](./demo)

## Features

- Nuxt 3 ready
- Vue 3 composables
- Usage in API server routes
- Authentication support
- Use supabase-js isomorphic client
- TypeScript support

## Usage

Checkout https://supabase.nuxtjs.org

## Nuxt 2

If you are looking for a solution with Nuxt 2, checkout https://github.com/supabase-community/nuxt-supabase

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Prepare development server using `yarn dev:prepare` or `npm run dev:prepare`
4. Build module using `yarn build` or `npm build`
5. Launch playground using `yarn dev` or `npm run dev`

## License

[MIT License](./LICENSE)

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/@nuxtjs/supabase/latest.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-version-href]: https://npmjs.com/package/@nuxtjs/supabase

[npm-downloads-src]: https://img.shields.io/npm/dt/@nuxtjs/supabase.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-downloads-href]: https://npmjs.com/package/@nuxtjs/supabase

[github-actions-ci-src]: https://github.com/nuxt-community/supabase-module/workflows/ci-main/badge.svg
[github-actions-ci-href]: https://github.com/nuxt-community/supabase-module/actions?query=workflow%3Aci

[codecov-src]: https://img.shields.io/codecov/c/github/nuxt-community/supabase-module.svg?style=flat&colorA=18181B&colorB=28CF8D
[codecov-href]: https://codecov.io/gh/nuxt-community/supabase-module

[license-src]: https://img.shields.io/npm/l/@nuxtjs/supabase.svg?style=flat&colorA=18181B&colorB=28CF8D
[license-href]: https://npmjs.com/package/@nuxtjs/supabase

[nuxt-src]: https://img.shields.io/badge/Nuxt-18181B?logo=nuxt.js
[nuxt-href]: https://nuxt.com

[volta-src]: https://user-images.githubusercontent.com/904724/209143798-32345f6c-3cf8-4e06-9659-f4ace4a6acde.svg
[volta-href]: https://volta.net/nuxt-modules/supabase?utm_source=readme_nuxt_supabase
