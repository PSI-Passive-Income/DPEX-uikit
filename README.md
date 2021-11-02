# 🥞 Pancake UIkit

**This repository is not used anymore. See the [https://github.com/pancakeswap/pancake-toolkit](Pancake toolkit) instead**

[![Version](https://img.shields.io/npm/v/@passive-income/dpex-uikit)](https://www.npmjs.com/package/@passive-income/dpex-uikit) [![Size](https://img.shields.io/bundlephobia/min/@passive-income/dpex-uikit)](https://www.npmjs.com/package/@passive-income/dpex-uikit)

Pancake UIkit is a set of React components and hooks used to build pages on Pancake's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @passive-income/dpex-uikit`

## Setup

### Theme

Before using Pancake UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@passive-income/dpex-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@passive-income/dpex-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://pancakeswap.github.io/pancake-uikit/)
