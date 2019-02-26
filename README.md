# nuxtClientInit module

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![donate: Patreon](https://img.shields.io/badge/donate-patreon-orange.svg?style=flat-square)](https://www.patreon.com/potato4d)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![NPM version](https://img.shields.io/npm/v/nuxt-client-init-module.svg?style=flat)](https://npmjs.com/package/nuxt-client-init-module)
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors)
[![NPM downloads](https://img.shields.io/npm/dm/nuxt-client-init-module.svg?style=flat)](https://npmjs.com/package/nuxt-client-init-module)
[![codecov](https://codecov.io/gh/potato4d/nuxt-client-init-module/branch/master/graph/badge.svg)](https://codecov.io/gh/potato4d/nuxt-client-init-module)

> Provide client version of `nuxtServerInit`.

`nuxt-client-init-module` provides Nuxt.js with the ability to inject processing at client initialization.
Just like `nuxtServerInit`, it is possible to implement the` nuxtClientInit` action, which is executed only on the client-side rendering, in the root Vuex module.

<a href="https://patreon.com/potato4d">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" height="50">
</a>

## Installation

```bash
$ yarn add nuxt-client-init-module
```

## Usage

on nuxt.config.js

```
{
  ...
  modules: [
   'nuxt-client-init-module'
 ]
 ...
}
```

on store/index.js

```
export const actions = {
  nuxtClientInit({ commit }, context) {
    // code
  }
}
```

## Author

- [potato4d](https://twitter.com/potato4d)

## LICENSE

MIT

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars0.githubusercontent.com/u/6993514?v=4" width="100px;"/><br /><sub><b>HANATANI Takuma</b></sub>](https://potato4d.me)<br />[💻](https://github.com/potato4d/nuxt-client-init-module/commits?author=potato4d "Code") [🐛](https://github.com/potato4d/nuxt-client-init-module/issues?q=author%3Apotato4d "Bug reports") [👀](#review-potato4d "Reviewed Pull Requests") [💬](#question-potato4d "Answering Questions") | [<img src="https://avatars2.githubusercontent.com/u/13393900?v=4" width="100px;"/><br /><sub><b>tosuke</b></sub>](https://github.com/Tosuke)<br /> [🐛](https://github.com/potato4d/nuxt-client-init-module/issues?q=author%3ATosuke "Bug reports") | [<img src="https://avatars2.githubusercontent.com/u/1443118?v=4" width="100px;"/><br /><sub><b>Masaya Kazama</b></sub>](https://miyaoka.github.io/)<br /> [🐛](https://github.com/potato4d/nuxt-client-init-module/issues?q=author%3Amiyaoka "Bug reports") |
| :---: | :---: | :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!
