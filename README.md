# `@avdp211/streak-counter` - a basic streak counter

This is a basic streak counter - inspired by DuoLingo - written in TypeScript and meant for the browser (uses `localStorage`).

## Install

```shell
yarn add @avdp211/streak-counter
```
npm install @avdp211/streak-counter

Usage

import {streakCounter} from '@avdp211/streak-counter'
const today = new Date()
const streak = streakCounter(localStorage,today)
//streak returns an object:
//{
//  currentCount: 1,
//  lastLoginDate: "25/04/2022",
//  startDate: "25/04/2022",
//}
