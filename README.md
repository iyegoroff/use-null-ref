# use-null-ref

[![npm](https://img.shields.io/npm/v/use-null-ref)](https://npm.im/use-null-ref)
[![build](https://github.com/iyegoroff/use-null-ref/workflows/build/badge.svg)](https://github.com/iyegoroff/use-null-ref/actions/workflows/build.yml)
[![publish](https://github.com/iyegoroff/use-null-ref/workflows/publish/badge.svg)](https://github.com/iyegoroff/use-null-ref/actions/workflows/publish.yml)
![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/npm/use-null-ref)
[![Bundlephobia](https://img.shields.io/bundlephobia/minzip/use-null-ref?label=min+gzip)](https://bundlephobia.com/package/use-null-ref)
[![npm](https://img.shields.io/npm/l/use-null-ref.svg?t=1495378566925)](https://www.npmjs.com/package/use-null-ref)

Super simple hook for `eslint-plugin-no-null` users

## Getting started

`$ npm i use-null-ref`

## Overview

```ts
import { useRef } from 'react'

export const useNullRef = <T>() => useRef<T>(null)
```
