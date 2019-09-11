# ktor-examples
Quick and fast rapid development with ktor [![Build Status](https://travis-ci.org/daggerok/ktor-examples.svg?branch=master)](https://travis-ci.org/daggerok/ktor-examples)

[[toc]]

## HTML + CSS

<!--
<<< @/ktor-html-css-example/src/Application.kt{highlightLines}
-->

@[code lang=kotlin transcludeWith=tag::snippet-1](@/ktor-html-css-example/src/Application.kt)

## VuePress docs

```shell script
npm i
npm run build
npx serve .vuepress/dist/
```

open http://localhost:5000/

Documentation is deployed on [GitHub Pages](https://daggerok.github.io/ktor-examples/)

## resources

* [Ktor project](https://ktor.io)
* [Ktor Getting Started](https://ktor.io/quickstart/index.html)
* [Ktor project generator: start.ktor.io](https://start.ktor.io)
* [YouTube: Server-Side Development with Ktor by Hadi Hariri - Bengaluru, June 22, 2019](https://www.youtube.com/watch?v=Y4kyTpi_qO4)
* [VuePress](https://v1.vuepress.vuejs.org/guide/markdown.html#import-code-snippets)
* [VuePress partial includes: markdown-it-vuepress-code-snippet-enhanced](https://www.npmjs.com/package/markdown-it-vuepress-code-snippet-enhanced)
