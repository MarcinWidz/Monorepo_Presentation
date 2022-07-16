
# Introduction

<v-clicks>
<h4>Développer dans un contexte professionel</h4>
<div>
    <h4>Collaboration:</h4>
    <img v-after src="/img/equipe_ctract.png"/>
</div>
</v-clicks>

<!-- Le défi majeur qui s'impose pour le passage du contexte d'une formation au contexte professionnel peut se résumer en un mot : collaboration. On passe alors des projets auxquels on était le contributeur unique aux code-bases où on coopère avec une multitude de développeurs simultanément. Les interactions entre les développeurs sont façonnées par le code source.  -->

---

<div class="mt-50">
    <h2> Existe-t-il une façon de stocker le code source qui favorisrait la collaboration? </h2>
</div>

<!-- De ce fait, nous pourrons nous demander s'il existe un choix d'architecture de stockage de la code-base qui favoriserait la collaboration.  -->

---

#  Qui utilise le Monorepo ?


<div class="grid grid-cols-3 h-100 gap-4">
        <div class="flex-end-div">
            <img src="/svg/google-icon.svg" class="w-30">
            <p class="text-4xl">Google</p>
        </div>
        <div class="flex-end-div">
            <img src="/svg/facebook.svg" class="w-30">
            <p class="text-4xl">Facebook</p>
        </div>
        <div class="flex-end-div">
            <img src="/svg/microsoft.svg" class="w-50 mb-10">
            <p class="text-4xl">Microsoft</p>
        </div>
        <div class="flex-end-div">
            <div class="bg-white"><img src="/svg/uber.svg" class="w-50 p-5"></div>
            <p class="text-4xl">Uber</p>
        </div>
        <div class="flex-end-div">
            <img src="/svg/twitter.svg" class="w-30">
            <p class="text-4xl">Twitter</p>
        </div>
        <div class="flex-end-div">
            <img src="/svg/airbnb.svg" class="w-30">
            <p class="text-4xl">Airbnb</p>
        </div>
</div>

<!-- Aujourd'hui, les entreprises telles que Google, Facebook, Microsoft, Uber, Airbnb et Twitter utilisent toutes la même façon de stocker le code source. Il faut se demander si on n'aurait pas quelque chose à apprendre en suivant leur exemple. En effet, l'établissement d'accueil que j'ai intégré en Octobre 2021 a décidé de le faire. Après la présentation de l'entreprise, l’exploration des choix techniques qui ont été faits et une brève description de mes contributions au fil de ces 6 derniers mois, nous allons nous pencher sur les motivations qui nous ont mené à adopter cette configuration. -->