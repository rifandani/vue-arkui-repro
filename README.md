# Intro

This is the reproduction repo for [arkui toast issue](https://github.com/chakra-ui/ark/issues/1193).
Cloned from [rifandani/vue-app](https://github.com/rifandani/vue-app).

## Description

When I trying to get the slot props from `ToastPlacements` & `ToastGroup` component, I expected the props to be typed correctly, but instead I got the `any` type

## Steps to reproduce

- Open `AppToastProvider.vue` in `src/app/AppToastProvider.vue`
- Hover over `placements` & `toasts` variable from `v-slot`