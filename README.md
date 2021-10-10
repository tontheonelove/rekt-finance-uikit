# Rekt UIkit

Rekt UIkit is a set of React components and hooks used to build pages on Rekt's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @rekt-finance/uikit`

## Setup

### Theme

Before using Rekt UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@rekt-finance/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@rekt-finance/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
