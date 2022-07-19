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
src: ./chapters/introduction.md
---

---
src: ./chapters/company.md
---

---
src: ./chapters/inscription.md
---

---
src: ./chapters/gestion.md
---
# Sécurisation

- But principal de l'application mobile
- Organisateur notifié pour alerter les secouristes

- Accident de raid hannibal
- Détection de choc automatique

<img src="/img/gestion_dalertes.png" class="mt-5" />

<!-- accéléréromètre et gyroscope -->

---

# Difficulté et évolution de la stack technique

<!-- put cool image behind it -->

---

### Langage unique

- Initialement Kotlin, Swift & Django
- Difficulé de recrutement et de prise en main
- Le choix de javascript et react

<!-- Put icons of javascript & React -->

---

### Isolation

- Problème de gestion d'état
- Redux
- Les actions de Redux ont inspirés la réflexion sur le modèle d'architecture du code

---

### 3 tier architecture

- Presentation Tier (La présentation des données)
- Buissness Logic Tier (Le traitement des données et la logique métier)
- Data Tier (L'accès aux données persistantes)

<img src="/img/TTA.png" class="w-50 mt-5 mx-auto" />

Chaque couche communique uniquemeent avec ses voisins imédiats

<!-- Adjust size of image -->

---

### Niveau de présentation

- Components
  - Librairie d'interface utilisateur (UI)
  - Couche avec laquelle l'utilisateur intéragis
- Actions
  - Pont entre la couche de présentation et la couche de logique métier
  - Purement déclarative
  - Le seul but est d'appellé les bons services

---

## Niveau logique métier

- Services

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

<img src="/svg/lerna.svg" class="absolute right-30 top-1/3 w-65 animate-pulse transform -rotate-5" />
<img src="/svg/turborepo.svg" class="absolute left-1/5 bottom-1/6 w-60 transform" />
<img src="/svg/nx.svg" class="absolute left-1/7 top-1/2 w-30 transform rotate-5"/>

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
