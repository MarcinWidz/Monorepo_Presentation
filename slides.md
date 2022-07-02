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

<h2 class="max-w-md mx-auto text-shadow-md">Maintien du code dans un produit multi-plateformes</h2>

<!-- We Will find a way BOI -->

---

# Sommaire

<div class="ml-20 grid gap-3">

### Introduction

### Présentation de l'entreprise

<div>

### Présentation du produit

- Difficulté et évolution de la stack technique

</div>

### Mission réalisé pendant le stage

<div>

### Analyse et bilan de la problématique

- Les problème d'une architecture multirepo
- Multirepo VS Monorepo
- Outils disponibles et leurs avantages
- Nouvelle génération des managers de monorepo

</div>

### Conclusion

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


ul {
  @apply ml-10
}
</style>

<!-- In bromance we trust -->

---

# Introduction

- Dévellopper dans un contexte professionel
- Qui utilise le monorepo ?

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

ul {
  @apply ml-10 text-xl
}
</style>

<img src="/img/lerna.svg" class="absolute right-30 top-1/3 w-65 animate-pulse transform -rotate-5" />
<img src="/img/turborepo.svg" class="absolute left-1/5 bottom-1/6 w-60 transform" />
<svg viewBox="0 0 262 163" class="absolute left-1/7 top-1/2 w-30 transform rotate-5"><polygon id="Path" fill="#ffffff" points="130.68 104.59 97.49 52.71 97.44 96.3 40.24 0 0 0 0 162.57 39.79 162.57 39.92 66.39 96.53 158.26"></polygon><polygon id="Path" fill="#ffffff" points="97.5 41.79 137.24 41.79 137.33 41.33 137.33 0 97.54 0 97.49 41.33"></polygon><path d="M198.66,86.86 C189.139872,86.6795216 180.538723,92.516445 177.19,101.43 C182.764789,93.0931021 193.379673,89.7432211 202.73,93.37 C207.05,95.13 212.73,97.97 217.23,96.45 C212.950306,90.4438814 206.034895,86.8725952 198.66,86.86 L198.66,86.86 Z" id="Path" fill="#96D8E9"></path><path d="M243.75,106.42 C243.75,101.55 241.1,100.42 235.6,98.42 C231.52,97 226.89,95.4 223.52,91 C222.86,90.13 222.25,89.15 221.6,88.11 C220.14382,85.4164099 218.169266,83.037429 215.79,81.11 C212.58,78.75 208.37,77.6 202.91,77.6 C191.954261,77.6076705 182.084192,84.2206169 177.91,94.35 C183.186964,87.0278244 191.956716,83.0605026 200.940147,83.9314609 C209.923578,84.8024193 217.767888,90.3805017 221.54,98.58 C223.424615,101.689762 227.141337,103.174819 230.65,102.22 C236.02,101.07 235.65,106.15 243.76,107.87 L243.75,106.42 Z" id="Path" fill="#48C4E5"></path><path d="M261.46,105.38 L261.46,105.27 C261.34,73.03 235.17,45.45 202.91,45.45 C183.207085,45.4363165 164.821777,55.3450614 154,71.81 L153.79,71.45 L137.23,45.45 L97.5,45.4499858 L135.25,104.57 L98.41,162.57 L137,162.57 L153.79,136.78 L170.88,162.57 L209.48,162.57 L174.48,107.49 C173.899005,106.416838 173.583536,105.220114 173.56,104 C173.557346,96.2203871 176.64661,88.7586448 182.147627,83.2576275 C187.648645,77.7566101 195.110387,74.6673462 202.89,74.67 C219.11,74.67 221.82,84.37 225.32,88.93 C232.23,97.93 246.03,93.99 246.03,105.73 L246.03,105.73 C246.071086,108.480945 247.576662,111.001004 249.979593,112.340896 C252.382524,113.680787 255.317747,113.636949 257.679593,112.225896 C260.041438,110.814842 261.471086,108.250945 261.43,105.5 L261.43,105.5 L261.43,105.38 L261.46,105.38 Z" id="Path" fill="#ffffff"></path><path d="M261.5,113.68 C261.892278,116.421801 261.504116,119.218653 260.38,121.75 C258.18,126.84 254.51,125.14 254.51,125.14 C254.51,125.14 251.35,123.6 253.27,120.65 C255.4,117.36 259.61,117.74 261.5,113.68 Z" id="Path" fill="#022f56"></path></svg>

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

---

# Présentation du produit

- Les 3 pilliers de la plateforme X-tract

  - Inscription
  - Planification organisation
  - Sécurisation

---

## Difficulté et évolution de la stack technique

### Langage unique

---

### Isolation

---

### 3 tier architecture

---

### Monorepo et CORE

---

# Mission réalisé pendant le stage

---

## Localisation par SMS

---

## Maintien de l'intégritée relationelle de la base de données

---

## Fiches de poste

---

## Création d'une API multi difusion des annonces

---

## Mentions honorables

---

## Intégration des cartes IGN sur la plateforme WEB

---

## Sauvegarde de la base de donnée automatique

---

## Refatoring, Refatoring, Refatoring...

---

# Analyse et bilan de la problématique

- Importance de la communication au sein de l'équipe
- Choix de l'architecture du repo

---

## Les problème d'une architecture multirepo

---

## Multirepo VS Monorepo

---

## Outils disponibles et leurs avantages

---

## Nouvelle génération des managers de monorepo

---

### Local caching

---

### Remote caching

---

### Local task orchestration

---

# Conclusion

---
