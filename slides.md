---
theme: unicorn
highlighter: shiki
themeConfig:
  primary: '#4d7534'
---


# Vimを使ってみよう
君も今日からvimmerになれる

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: table-contents
---
# Contents
1. なぜVimなのか

---
layout: two-cols
---

<template v-slot:default>

# なぜVimなのか


- **1991年に誕生したCLIテキストエディタ**: 
  - 根強い人気
  - IDEではない
- **爆速コーディング**:
  - マウス無しの豊富なキーバインド
  - 3種類のモード
- **豊かなカスタマイズ性**: 
  - 豊富なプラグイン
  - 設定をいじるだけで一日が溶ける

</template>
<template v-slot:right>

<!-- ![test](https://www.kaoriya.net/blog/2013/12/06/06.png) -->
<img src="https://www.kaoriya.net/blog/2013/12/06/06.png" width="400"/>

</template>

---
layout: cover
---

# Vimの将来
## Vimの課題
- メンテナーが1人しかいない
- VimScriptで実装されている
  - 実装のために新しい言語を覚える必要がある

## Neovimの登場
- API実装
- Neovim v0.5.0からLua実装
<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->
---

---
