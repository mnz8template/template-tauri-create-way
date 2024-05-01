## flow

pnpm dlx create-tauri-app

ncu -i

pnpm i

## log

```
$ pnpm dlx create-tauri-app
✔ Project name · way-create-tauri
✔ Choose which language to use for your frontend · TypeScript / JavaScript - (pnpm, yarn, npm, bun)
✔ Choose your package manager · pnpm
✔ Choose your UI template · Vue - (https://vuejs.org/)
✔ Choose your UI flavor · TypeScript

Template created! To get started run:
  cd way-create-tauri
  pnpm install
  pnpm tauri dev


```

## bun

`bun x create-tauri-app@latest`

bun 没有 @latest 时，会出现按键失效，如：上下，删除等，注: 相同环境下 pnpm 没有问题, bun 存在。

`bun create tauri-app` 也不可以

```
$ bun -v
1.1.6
```
