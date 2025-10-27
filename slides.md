---
theme: default
background: /img/hotel_new_york.jpg
title: Forum PHP 2025 - Retour d'expérience
info: |
  ## Forum PHP 2025 - REX
  Retour d'expérience sur le Forum PHP 2025
  Présentation pour AFUP Nantes - 28 octobre 2025
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
colorSchema: light
---

# Retour sur le Forum PHP 2025

<div class="mt-4">
  <img src="/img/logo_forumphp_2025.png" class="h-32 inline-block" alt="Forum PHP 2025 Logo" />
</div>

---
layout: two-cols
layoutClass: gap-16
---

# Qui suis-je ?

<img src="/img/me.jpeg" class="rounded-lg w-64 h-80 object-cover shadow-lg mx-auto mt-8" alt="Nicolas Demay" />

::right::

<div class="mt-16">

## Nicolas Demay

<br>

- 👨‍💻 **Développeur PHP Freelance**
- ⏱️ **+20 ans d'expérience développement PHP**
- 🎓 **Certifié Symfony 7 Developer**
- 🤖 **Boosté à l'IA**

</div>

---
layout: image-right
image: /img/conference.jpeg
backgroundSize: cover
class: my-custom-layout
---

<style>
.my-custom-layout .slidev-layout {
  grid-template-columns: 1fr 2fr !important;
}
</style>

# Forum PHP 2025

<div class="bg-white bg-opacity-90 p-6 rounded-lg shadow-xl">

## L'événement

- **📅 Dates** : 9 et 10 octobre 2025
- **📍 Lieu** : Disney Hotel New York - The Art of Marvel
- **👥 Participants** : Plus de 700 participants
- **🎤 Conférences** : Plus de 40 talks

<div class="mt-4 text-sm opacity-75">

Plus d'infos : [event.afup.org/forum-php-2025](https://event.afup.org/forum-php-2025/)

</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 125px;">
    <img src="/img/amaury-bouchard.png" alt="Amaury Bouchard" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Amaury BOUCHARD</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Les bases de la sécurité</h1>
    <p class="text-xl text-gray-600">des développements Web</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-4">
  <div class="bg-gradient-to-br from-red-50 to-orange-50 rounded-xl p-4 shadow-md border-l-4 border-red-500">
    <h3 class="text-xl font-bold text-red-900 mb-3 flex items-center gap-2">
      <span class="text-2xl">⚠️</span> Menaces
    </h3>
    <ul class="space-y-2 text-sm text-gray-800">
      <li class="flex items-start gap-2">
        <span class="text-red-600 font-bold mt-0.5">✗</span>
        <span><strong>Injection SQL</strong></span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-red-600 font-bold mt-0.5">✗</span>
        <span><strong>XSS (Cross-Site Scripting)</strong></span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-red-600 font-bold mt-0.5">✗</span>
        <span><strong>SSRF (Server-Side Request Forgery)</strong></span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-red-600 font-bold mt-0.5">✗</span>
        <span><strong>CSRF (Cross-Site Request Forgery)</strong></span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-green-50 to-emerald-50 rounded-xl p-4 shadow-md border-l-4 border-green-500">
    <h3 class="text-xl font-bold text-green-900 mb-3 flex items-center gap-2">
      <span class="text-2xl">🛡️</span> Protections
    </h3>
    <ul class="space-y-2 text-sm text-gray-800">
      <li class="flex items-start gap-2">
        <span class="text-green-600 font-bold mt-0.5">✓</span>
        <span><strong>Requêtes préparées, ORM</strong></span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-green-600 font-bold mt-0.5">✓</span>
        <span><strong>strip_tags, HTML Purifier, CSP</strong></span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-green-600 font-bold mt-0.5">✓</span>
        <span><strong>Validation rigoureuse des URL</strong></span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-green-600 font-bold mt-0.5">✓</span>
        <span><strong>SameSite cookies, Referer, POST</strong></span>
      </li>
    </ul>
  </div>
</div>

<div class="mt-3 grid grid-cols-2 gap-4">
  <div class="bg-gradient-to-r from-red-100 to-orange-100 rounded-lg p-3 shadow-md border-l-4 border-red-500">
    <div class="text-center">
      <div class="font-bold text-red-800 text-base">⚠️ Ne jamais faire confiance aux données entrantes</div>
      <div class="text-sm text-gray-700 mt-1">60% des entreprises victimes ferment sous 18 mois</div>
    </div>
  </div>

  <div class="bg-gradient-to-r from-blue-100 to-indigo-100 rounded-lg p-3 shadow-md border-l-4 border-blue-500">
    <div class="text-center">
      <div class="font-bold text-blue-800 text-base mb-1">📚 Sources de référence</div>
      <div class="text-sm text-gray-700">OWASP Top 10 • ANSSI • CERT • Mozilla Observatory</div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-3 h-full flex flex-col">

<div class="flex items-start gap-6 mb-3">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/laetitia-avrot.png" alt="Lætitia Avrot" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Lætitia AVROT</div>
  </div>
  <div class="flex-1">
    <h1 class="text-3xl font-bold text-gray-800 mb-1">SQL vs Les Préjugés</h1>
    <p class="text-base text-gray-600">SQL a évolué, pas les formations</p>
  </div>
</div>

<div class="grid grid-cols-2 gap-2.5 flex-1">
  <div class="bg-gradient-to-br from-purple-50 to-indigo-50 rounded-lg p-2.5 shadow-md border-l-4 border-purple-500">
    <div class="font-bold text-purple-900 text-xs mb-1">🔗 JOIN LATERAL <span class="text-xs text-gray-600">(top 3 par client)</span></div>
    <pre class="text-xs bg-white p-1.5 rounded leading-tight"><code>SELECT c.name, o.total
FROM customers c
LEFT JOIN LATERAL (
  SELECT total FROM orders
  WHERE customer_id = c.id
  ORDER BY total DESC LIMIT 3
) o ON true;</code></pre>
  </div>

  <div class="bg-gradient-to-br from-green-50 to-emerald-50 rounded-lg p-2.5 shadow-md border-l-4 border-green-500">
    <div class="font-bold text-green-900 text-xs mb-1">↩️ RETURNING <span class="text-xs text-gray-600">(depuis 2006 !)</span></div>
    <pre class="text-xs bg-white p-1.5 rounded leading-tight"><code>INSERT INTO order (customer_id, total)
VALUES (42, 1599.99)
RETURNING id, order_number,
          created_at, status;</code></pre>
  </div>

  <div class="bg-gradient-to-br from-blue-50 to-cyan-50 rounded-lg p-2.5 shadow-md border-l-4 border-blue-500">
    <div class="font-bold text-blue-900 text-xs mb-1">📊 LAG() <span class="text-xs text-gray-600">(croissance mois/mois)</span></div>
    <pre class="text-xs bg-white p-1.5 rounded leading-tight"><code>SELECT month, sales,
  LAG(sales) OVER (ORDER BY month)
    AS previous_month
FROM monthly_sales
WHERE year = 2025;</code></pre>
  </div>

  <div class="bg-gradient-to-br from-orange-50 to-amber-50 rounded-lg p-2.5 shadow-md border-l-4 border-orange-500">
    <div class="font-bold text-orange-900 text-xs mb-1">🏆 PARTITION BY <span class="text-xs text-gray-600">(top 3 par catégorie)</span></div>
    <pre class="text-xs bg-white p-1.5 rounded leading-tight"><code>WITH ranked AS (
  SELECT *, ROW_NUMBER() OVER (
    PARTITION BY category_id
    ORDER BY sales DESC
  ) AS rank FROM product
) SELECT * FROM ranked
WHERE rank <= 3;</code></pre>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-4">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/laetitia-avrot.png" alt="Lætitia Avrot" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Lætitia AVROT</div>
  </div>
  <div class="flex-1">
    <h1 class="text-4xl font-bold text-gray-800 mb-2">SQL vs Les Préjugés</h1>
    <p class="text-lg text-gray-600">SQL a évolué, pas les formations</p>
  </div>
</div>

<div class="flex-1 space-y-3">

<div class="bg-gradient-to-r from-blue-100 to-indigo-100 rounded-xl p-3 shadow-lg border-l-6 border-blue-500">
  <div class="text-lg font-bold text-blue-900">🚀 SQL a énormément évolué</div>
  <div class="text-sm text-gray-700">Window functions, CTEs, JOIN LATERAL, RETURNING...</div>
  <div class="text-xs text-gray-600 mt-0.5">Fonctionnalités puissantes disponibles depuis des années</div>
</div>

<div class="bg-gradient-to-r from-orange-100 to-red-100 rounded-xl p-3 shadow-lg border-l-6 border-orange-500">
  <div class="text-lg font-bold text-orange-900">📚 Les formations sont restées figées</div>
  <div class="text-sm text-gray-700">L'enseignement SQL n'a pas suivi l'évolution du langage</div>
  <div class="text-xs text-gray-600 mt-0.5">On continue d'enseigner SQL comme dans les années 90</div>
</div>

<div class="bg-gradient-to-r from-red-100 to-pink-100 rounded-xl p-3 shadow-lg border-l-6 border-red-500">
  <div class="text-lg font-bold text-red-900">🤖 Les LLM perpétuent le problème</div>
  <div class="text-sm text-gray-700">Entraînés sur du code obsolète et des requêtes peu qualitatives</div>
  <div class="text-xs text-gray-600 mt-0.5">Ils reproduisent et amplifient les mauvaises pratiques</div>
</div>

</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/felix-eymonot.png" alt="Félix Eymonot" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Félix EYMONOT</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Sous le capot de Composer</h1>
    <p class="text-xl text-gray-600">Comprendre l'outil qu'on utilise tous les jours</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">📦</span> Installation
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Résout les dépendances</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Reproductibilité garantie</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Vérification d'intégrité</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🔧</span> Autoloading
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">PSR-4</div>
        <div class="text-sm">Bien pour le développement</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">Classmap & APCu</div>
        <div class="text-sm">Optimisé pour la production</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Commandes utiles</div>
        <div class="text-sm">why, why-not, depends --tree</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/kevin-dunglas.png" alt="Kévin Dunglas" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Kévin DUNGLAS</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">FrankenPHP, en dehors des sentiers battus</h1>
    <p class="text-xl text-gray-600">Le serveur d'application PHP moderne écrit en Go</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">⚡</span> Fonctionnalités avancées
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Early Hints (103) pour précharger les assets</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Intégration native de Mercure</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Standalone binary tout-en-un</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Worker mode pour performances optimales</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🚀</span> Puissance de Go
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">Go Extensions</div>
        <div class="text-sm">Multi-thread, accès aux librairies Go</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">Concurrent</div>
        <div class="text-sm">Go Workers pour parallélisation</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Déploiement simple</div>
        <div class="text-sm">Un seul exécutable avec tout intégré</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/felix-eymonot.png" alt="Félix Eymonot" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Félix EYMONOT</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Symfony UX Live Component</h1>
    <p class="text-xl text-gray-600">Construire un tableau de bord interactif sans JS</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">✨</span> Fonctionnalités
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Zéro ligne de JavaScript écrite</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>LiveProp : propriétés réactives</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Polling natif avec data-poll</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>URL synchronisée avec url_true</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🎯</span> Cas d'usage
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-green-700 mb-1">✅ Parfait pour</div>
        <div class="text-sm">Tableaux de bord, CRUD, équipes back-end</div>
      </div>
      <div>
        <div class="font-semibold text-orange-700 mb-1">⚠️ Moins adapté</div>
        <div class="text-sm">Applications ultra temps réel, beaucoup d'animations</div>
      </div>
      <div>
        <div class="font-semibold text-blue-700 mb-1">Débogage</div>
        <div class="text-sm">Web Profiler Symfony comme avec les contrôleurs</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/benjamin-rambaud.png" alt="Benjamin Rambaud" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Benjamin RAMBAUD</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Overcoming our Primitive Obsessions</h1>
    <p class="text-xl text-gray-600">Bonnes pratiques de programmation orientée objet</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🔍</span> Code Smells
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Types primitifs vs objets métier</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Exemple : prix en "string" dans Product</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Détection des anti-patterns</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">⚖️</span> Équilibre
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">🎯 Juste milieu</div>
        <div class="text-sm">Trouver le bon équilibre selon le projet</div>
      </div>
      <div>
        <div class="font-semibold text-orange-700 mb-1">⚠️ Attention</div>
        <div class="text-sm">Trop d'objets métier génère de la complexité</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">✅ Objectif</div>
        <div class="text-sm">Code lisible et maintenable</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/pascal-martin.png" alt="Pascal Martin" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Pascal MARTIN</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Quatre patterns avancés</h1>
    <p class="text-xl text-gray-600">Pour améliorer la résilience d'une application</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🔄</span> Gestion des charges
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Random Jitter : aléatoire pour lisser les requêtes</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Exponential Backoff : délais croissants</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Constant Work : nombre fixe de traitements</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🏗️</span> Architecture
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">Cell-based Architecture</div>
        <div class="text-sm">Réduire le rayon d'explosion, isoler les cellules</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">Shuffle Sharding</div>
        <div class="text-sm">Distribution optimisée des ressources</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Objectif</div>
        <div class="text-sm">Robustesse et stabilité en production</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/olivier-openclassrooms.png" alt="Olivier" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Olivier</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">10 ans de Clean Architecture</h1>
    <p class="text-xl text-gray-600">chez OpenClassrooms : le rêve, la réalité, les leçons</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">📖</span> Le parcours
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Métier au centre : game changer pour l'évolution</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Tests : de 30 minutes à quelques secondes</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>12 ans sans refonte majeure</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">💡</span> Leçons apprises
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">Pragmatisme vs dogmatisme</div>
        <div class="text-sm">Simplification progressive de l'architecture</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">Cohésion</div>
        <div class="text-sm">Regrouper ce qui change pour les mêmes raisons</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Évolution</div>
        <div class="text-sm">L'architecture doit s'adapter au contexte</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/nicolas-grekas.png" alt="Nicolas Grekas" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Nicolas GREKAS</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Perf et injection de dépendances</h1>
    <p class="text-xl text-gray-600">Êtes-vous suffisamment paresseux·ses ?</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🔧</span> Attributs utiles
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Autowire, AutoConfigureTag, AutowireIterator</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>AsAlias, AsDecorator, AsTaggedItem</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>AutowireInline, AutowireCallable, AutowireMethodOf</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">⚡</span> Performance
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">SOLID</div>
        <div class="text-sm">Structurer le code pour permettre le changement</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">#Lazy</div>
        <div class="text-sm">Casser les chaînes de dépendance avec closures</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Compile vs Runtime</div>
        <div class="text-sm">Optimiser l'injection de dépendances</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/baptiste-langlade.png" alt="Baptiste Langlade" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Baptiste LANGLADE</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">180 000 requêtes par seconde</h1>
    <p class="text-xl text-gray-600">Expliqué simplement</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🚀</span> Le challenge
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Exécuter un maximum de requêtes à un serveur</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Parallélisation des requêtes</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Utilisation de cURL sans librairie</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">⚡</span> Optimisations
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">Busy Looping</div>
        <div class="text-sm">HTTP version, TCP/UDP optimisés</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">Multi-thread</div>
        <div class="text-sm">Shared memory pour performances</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Résultat</div>
        <div class="text-sm">180 000 req/s : une prouesse technique</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/edouard-courty.png" alt="Edouard Courty" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Edouard COURTY</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Créer un serveur MCP avec Symfony</h1>
    <p class="text-xl text-gray-600">Le Model Context Protocol pour l'interaction avec les IA</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🔧</span> Intégration Symfony
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Plusieurs bundles disponibles dans l'écosystème</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Attributs : tools, resource, prompt</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Support Symfony UX</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🎯</span> Points clés
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-purple-700 mb-1">Cas d'usage</div>
        <div class="text-sm">Chatbot e-commerce : commandes, support client</div>
      </div>
      <div>
        <div class="font-semibold text-orange-700 mb-1">⚠️ Limitations</div>
        <div class="text-sm">Dépendance au prompt, risques de sécurité</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">🚀 État actuel</div>
        <div class="text-sm">Technologie récente en évolution rapide</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/clement-talleu.png" alt="Clément Talleu" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Clément TALLEU</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Créer un RAG en PHP</h1>
    <p class="text-xl text-gray-600">Démystifier l'IA avec les bonnes pratiques</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">📚</span> Qu'est-ce qu'un RAG ?
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Génération augmentée par la récupération</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Base documentaire indexée ajoutée au contexte LLM</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Base de données vectorielle (pgvector)</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Support Doctrine disponible</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🔧</span> Mise en œuvre
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">Chunking</div>
        <div class="text-sm">Découpage sémantique du texte</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">API externe ou locale</div>
        <div class="text-sm">OpenAI, Mistral ou Ollama</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Cas d'usage</div>
        <div class="text-sm">Chatbot règlement RH, documentation</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/francois-zaninotto.png" alt="François Zaninotto" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">François ZANINOTTO</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">L'évaluation des IAs</h1>
    <p class="text-xl text-gray-600">La recette secrète des agents pas trop bêtes</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">⚠️</span> Le défi
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Résultat d'un agent est imprévisible</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Comment s'assurer qu'il ne se trompe pas ?</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Tester avec toutes les configurations</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Multiplication des IA augmente la probabilité de failure</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">✅</span> Bonnes pratiques
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">Pattern Strategy</div>
        <div class="text-sm">Choisir le bon pattern pour le contexte</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">Métriques</div>
        <div class="text-sm">Quelques métriques à la fois, attention écart-type</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Outils Eval</div>
        <div class="text-sm">Librairies dédiées, graphiques, conservation</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/xavier-leune.png" alt="Xavier Leune" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Xavier LEUNE</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Comment être un bon dév à l'heure de l'IA ?</h1>
    <p class="text-xl text-gray-600">Impact de l'IA générative sur notre métier</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">💼</span> Enjeux du marché
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Les entreprises IA vampirisent la croissance US</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Coûts colossaux des datacenters</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Risque de bulle économique</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">📊</span> Productivité
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-green-700 mb-1">✅ Juniors</div>
        <div class="text-sm">Gain de delivery constaté</div>
      </div>
      <div>
        <div class="font-semibold text-orange-700 mb-1">⚠️ Seniors</div>
        <div class="text-sm">Impact cognitif plus important (review)</div>
      </div>
      <div>
        <div class="font-semibold text-blue-700 mb-1">🎓 Conseil</div>
        <div class="text-sm">Formez-vous le plus tôt possible</div>
      </div>
    </div>
  </div>
</div>

</div>
