---
theme: seriph
background: "/img/wallhaven-839zjk.jpg"
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
title: Mémoire RNCP Marcin Widz
download: true
exportFilename: "marcin-widz-presentation-RNCP.pdf"
---

# Monorepo

<h2 class="max-w-md mx-auto text-shadow-md">Modularisation effective pour le maintien du code dans un produit multi-plateformes</h2>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Introduction

- Dévellopper dans un contexte professionel
- Qui utilise le monorepo ?

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# Présentation de l'entreprise

<div class="ml-10 mt-20 grid gap-20 grid-cols-2">
  <div>
    <h2>L'histoire d'X-Fabric</h2>
    <img src="/img/x-fabric-logo.png" class="mt-5 w-70" />
  </div>

  <div>
    <v-click>
      <h2>L'origine d'X-Tract</h2>
      <img v-after src="/img/x-tract.jpg" class="mt-5 w-70" />
    </v-click>
  </div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}

.slidev-vclick-target {
  transition: opacity 200ms ease;
}

.slidev-vclick-hidden {
  opacity: 0;
  pointer-events: none;
}

</style>
