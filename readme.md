# BcRikko/NES.css [![explain]][source] [![translate-svg]][translate-list]

<!-- [![size-img]][size] -->

[explain]: http://llever.com/explain.svg
[source]: https://github.com/chinanf-boy/Source-Explain
[translate-svg]: http://llever.com/translate.svg
[translate-list]: https://github.com/chinanf-boy/chinese-translate-list
[size-img]: https://packagephobia.now.sh/badge?p=Name
[size]: https://packagephobia.now.sh/result?p=Name

「 **任天堂风格(8 像素位)**的 CSS 框架. 」

[中文](./readme.md) | [english](https://github.com/BcRikko/NES.css)

---

## 更新 ✅

<!-- doc-templite START generated -->
<!-- repo = 'BcRikko/NES.css' -->
<!-- commit = '32abcde4b6df780800ff9712ca89aefc6c08418b' -->
<!-- time = '2018-12-02' -->
翻译的原文 | 与日期 | 最新更新 | 更多
---|---|---|---
[commit] | ⏰ 2018-12-02 | ![last] | [中文翻译][translate-list]

[last]: https://img.shields.io/github/last-commit/BcRikko/NES.css.svg
[commit]: https://github.com/BcRikko/NES.css/tree/32abcde4b6df780800ff9712ca89aefc6c08418b

<!-- doc-templite END generated -->

### 贡献

欢迎 👏 勘误/校对/更新贡献 😊 [具体贡献请看](https://github.com/chinanf-boy/chinese-translate-list#贡献)

## 生活

[help me live , live need money 💰](https://github.com/chinanf-boy/live-need-money)

---

<div align="center">
  <a href="https://bcrikko.github.io/NES.css/" target="_blank"><img src="https://user-images.githubusercontent.com/5305599/49061716-da649680-f254-11e8-9a89-d95a7407ec6a.png" alt="NES.css: NES-style  CSS framework" style="max-width:100%;" width="600" height="315"></a>

</div>

NES.css 是**任天堂风格(8 像素位)**的 CSS 框架.

## 安装

### CDN

```html
<!-- minify -->
<link
  href="https://bcrikko.github.io/NES.css/css/nes.min.css"
  rel="stylesheet"
/>
```

OR

```html
<!-- non-minified -->
<link href="https://bcrikko.github.io/NES.css/css/nes.css" rel="stylesheet" />
```

### npm

TODO:

- [ ] 如何在 npm 使用它

## 使用

NES.css 只提供组件样式,请根据需要定义布局.

默认情况下，`Press Start 2P`仅支持英文字符，如果您使用的是英语以外的字体(如日语),请使用其他字体.

### 推荐 Fonts

| 国家语言  | Font                                                               |
| --------- | ------------------------------------------------------------------ |
| (Default) | [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P) |
| 英语   | [Kongtext](https://www.dafont.com/kongtext.font)                   |
| 日语  | [美咲フォント](http://www.geocities.jp/littlimi/misaki.htm)        |
| 日语  | [Nu もち](http://kokagem.sakura.ne.jp/font/mochi/)                 |

## 仅有 CSS

NES.css 只包含 CSS,不需要 JavaScript.

## 浏览器支持

我们支持以下浏览器的最新版本.

- Chrome
- Firefox
- Safari

未经证实

- IE/Edge

## 开发

### 可执行

```sh
git clone git@github.com:BcRikko/NES.css.git
cd NES.css

npm i

npm run watch
npm run build
```

通过预提交钩子，在提交时 ， Lint→format→build 自动运行，文件输出到`css`目录。

TODO：

- [ ] 我想改为使用 CI 完成的构建

### 项目结构

```
.
|- index.html: Demo 页面
|- style.css: Demo 页面样式
|- css: 分发文件
|- scss: 源文件
    |- base
    |   |- reboot.scss: **不要修改!** (Bootstrap Reboot)
    |   |- generic.scss: 通用样式 和 覆盖 reboot.css
    |   |- variables.scss: 常用变量
    |- elements
    |- form
    |- icons: 提供 16x16 icon
    |- pixel-arts: 其他大于 16x16 的 icon.
    |- utilities
```

## Copyright 和 license

代码和文档版权 2018 归，[B.C.Rikko](https://github.com/BcRikko)所有。根据 MIT 许可证发布的代码.在 Creative Commons 下发布的文档.
