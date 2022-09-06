# 🥞 SMove UIkit

[![Version](https://img.shields.io/npm/v/@smove/uikit)](https://www.npmjs.com/package/@smove/uikit) [![Size](https://img.shields.io/bundlephobia/min/@smove/uikit)](https://www.npmjs.com/package/@smove/uikit)

SMove UIkit is a set of React components and hooks used to build pages on SMove's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @smove/uikit`

## Setup

### Theme

Before using SMove UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@smove/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@smove/uikit'
...
<ResetCSS />
```
