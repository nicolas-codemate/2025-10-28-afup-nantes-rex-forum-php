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
- ⏱️ **+20 ans d'expérience en PHP**
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
- **👥** Plus de 700 participants
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

<!--
**Mise en scène** : Lætitia habillée en avocate, plaidoirie pour SQL

**Griefs courants** : lenteur, complexité, verbosité, pas moderne, dépassé par les ORM, dépassé par le NoSQL, performances douteuses

**Démonstration** : Comparaison scripts PHP multi-requêtes vs query SQL unique - meilleures performances
-->

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
        <span>Reproductibilité garantie (composer.lock)</span>
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
        <pre class="text-xs bg-white p-1.5 rounded mt-1 leading-tight"><code>composer install --no-dev \
  --optimize-autoloader \
  --apcu-autoloader</code></pre>
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

<div class="px-8 py-4 h-full flex flex-col">

<div class="flex items-start gap-6 mb-4">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/kevin-dunglas.png" alt="Kévin Dunglas" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Kévin DUNGLAS</div>
  </div>
  <div class="flex-1">
    <h1 class="text-4xl font-bold text-gray-800 mb-2">FrankenPHP, en dehors des sentiers battus</h1>
    <p class="text-lg text-gray-600">Le serveur d'application PHP moderne soutenu par la PHP Foundation</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-4">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-4 shadow-md border-l-4 border-blue-500">
    <h3 class="text-xl font-bold text-blue-900 mb-3 flex items-center gap-2">
      <span class="text-2xl">⚡</span> Fonctionnalités avancées
    </h3>
    <ul class="space-y-1.5 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-0.5">▸</span>
        <span>Early Hints (103) pour accélérer le chargement</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-0.5">▸</span>
        <span>Intégration de Mercure pour le temps réel</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-0.5">▸</span>
        <span>Worker mode pour performances optimales</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-0.5">▸</span>
        <span>Packaging en un seul binaire sans dépendances</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-4 shadow-md border-l-4 border-purple-500">
    <h3 class="text-xl font-bold text-purple-900 mb-3 flex items-center gap-2">
      <span class="text-2xl">🚀</span> Extensions et Workers en Go
    </h3>
    <div class="space-y-2 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-0.5">Exemples concrets</div>
        <div class="text-sm">Transport Symfony Messenger, WebSocket, gRPC</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-0.5">Haute performance</div>
        <div class="text-sm">PHP délègue les tâches lourdes à Go</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-0.5">Écosystème unifié</div>
        <div class="text-sm">Accès aux librairies Go sans quitter PHP</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-6">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/felix-eymonot.png" alt="Félix Eymonot" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Félix EYMONOT</div>
  </div>
  <div class="flex-1">
    <h1 class="text-4xl font-bold text-gray-800 mb-2">Symfony UX Live Component</h1>
    <p class="text-lg text-gray-600">Construire un tableau de bord interactif sans JS</p>
  </div>
</div>

<div class="flex-1 flex flex-col">

<div class="grid grid-cols-2 gap-4 mb-2">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-4 shadow-md border-l-4 border-blue-500">
    <h3 class="text-xl font-bold text-blue-900 mb-2 flex items-center gap-2">
      <span class="text-2xl">⚡</span> Temps réel en quelques attributs
    </h3>
    <ul class="space-y-1.5 text-sm text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-0.5">▸</span>
        <span><strong>data-model</strong> : liaison bidirectionnelle + debounce auto</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-0.5">▸</span>
        <span><strong>data-action</strong> : actions déclenchées au clic (tri)</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-0.5">▸</span>
        <span><strong>data-poll</strong> : rafraîchissement automatique</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-0.5">▸</span>
        <span><strong>update_from_parent</strong> : synchro Chart.js</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-0.5">▸</span>
        <span><strong>url_true</strong> : filtres sauvegardés dans l'URL</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-4 shadow-md border-l-4 border-purple-500">
    <h3 class="text-xl font-bold text-purple-900 mb-2 flex items-center gap-2">
      <span class="text-2xl">🎯</span> Fonctionnalités implémentées
    </h3>
    <div class="space-y-2 text-sm text-gray-700">
      <div>
        <div class="font-semibold text-blue-700">🔍 Recherche interactive avec debounce automatique</div>
      </div>
      <div>
        <div class="font-semibold text-green-700">📊 Graphique Chart.js synchronisé avec les filtres</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700">⬆️⬇️ Tri dynamique sur les colonnes</div>
      </div>
      <div>
        <div class="font-semibold text-orange-700">🔗 Filtres (statut, période) avec URL partageable</div>
      </div>
      <div>
        <div class="font-semibold text-indigo-700">🔄 Rafraîchissement automatique toutes les 10s</div>
      </div>
    </div>
  </div>
</div>

<div class="bg-gradient-to-r from-green-100 to-emerald-100 rounded-lg p-2.5 shadow-md border-l-4 border-green-500">
  <div class="text-lg font-bold text-green-900 text-center">
    🚀 Résultat : Zéro ligne de JS, toutes les fonctionnalités temps réel en ~2h30 !
  </div>
</div>

</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 135px;">
    <img src="/img/benjamin-rambaud.png" alt="Benjamin Rambaud" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight" style="font-size: 0.7rem;">Benjamin RAMBAUD</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">Overcoming our Primitive Obsessions</h1>
    <p class="text-xl text-gray-600">Bonnes pratiques de programmation orientée objet</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🔍</span> L'obsession des primitives
    </h3>
    <div class="space-y-2 text-base text-gray-700">
      <div class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span><strong>Primitives</strong> : string, int, float, bool, array</span>
      </div>
      <div class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span><strong>Obsession</strong> : utilisation excessive de ces types basiques</span>
      </div>
      <div class="bg-white rounded p-2 text-sm mt-2">
        <div class="text-red-600 mb-1">❌ <code>private string $price; // "19.99€"</code></div>
        <div class="text-green-600">✅ <code>private Price $price;</code></div>
      </div>
      <div class="flex items-start gap-2 mt-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Code difficile à comprendre et à maintenir</span>
      </div>
    </div>
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

<div class="px-8 py-4 h-full flex flex-col">

<div class="flex items-start gap-6 mb-4">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/pascal-martin.png" alt="Pascal Martin" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Pascal MARTIN</div>
  </div>
  <div class="flex-1">
    <h1 class="text-4xl font-bold text-gray-800 mb-2">Quatre patterns avancés pour améliorer la résilience d'une application</h1>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-4">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-4 shadow-md border-l-4 border-blue-500">
    <h3 class="text-xl font-bold text-blue-900 mb-3 flex items-center gap-2">
      <span class="text-2xl">☕</span> Gestion du cache
    </h3>
    <div class="text-sm text-gray-700 space-y-2">
      <div>
        <div class="font-semibold text-blue-700">Préparer les cafés en avance</div>
        <div class="text-xs">Générer les réponses avant la demande, mise en cache</div>
      </div>
      <div class="bg-orange-50 p-2 rounded border-l-2 border-orange-400">
        <div class="text-xs text-orange-700">
          <span class="font-bold">⚠️ Warning :</span> Ne pas vider tous les caches en même temps pour éviter la régénération massive
        </div>
      </div>
    </div>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-4 shadow-md border-l-4 border-purple-500">
    <h3 class="text-xl font-bold text-purple-900 mb-3 flex items-center gap-2">
      <span class="text-2xl">🔁</span> Exponential Backoff
    </h3>
    <div class="text-sm text-gray-700 space-y-2">
      <div>
        <div class="font-semibold text-purple-700">Espacer les retry</div>
        <div class="text-xs">Attendre de plus en plus longtemps : 1s, 2s, 4s, 8s, 16s...</div>
      </div>
      <div class="bg-orange-50 p-2 rounded border-l-2 border-orange-400">
        <div class="text-xs text-orange-700">
          <span class="font-bold">⚠️ Warning :</span> Mieux vaut éviter les retry (failed query)
        </div>
      </div>
    </div>
  </div>

  <div class="bg-gradient-to-br from-amber-50 to-orange-50 rounded-xl p-4 shadow-md border-l-4 border-amber-500">
    <h3 class="text-xl font-bold text-amber-900 mb-3 flex items-center gap-2">
      <span class="text-2xl">⚙️</span> Constant Work
    </h3>
    <div class="text-sm text-gray-700 space-y-2">
      <div>
        <div class="font-semibold text-amber-700">Nombre fixe de traitements</div>
        <div class="text-xs">La machine prépare toujours le même nombre de cafés, quitte à en préparer des fictifs</div>
      </div>
      <div class="text-xs text-gray-600 italic">
        Pas de variabilité = robustesse et stabilité
      </div>
    </div>
  </div>

  <div class="bg-gradient-to-br from-green-50 to-emerald-50 rounded-xl p-4 shadow-md border-l-4 border-green-500">
    <h3 class="text-xl font-bold text-green-900 mb-3 flex items-center gap-2">
      <span class="text-2xl">🏗️</span> Cell-based Architecture
    </h3>
    <div class="text-sm text-gray-700 space-y-2">
      <div>
        <div class="font-semibold text-green-700">Découper, isoler</div>
        <div class="text-xs">Réduire le rayon d'explosion d'une application</div>
      </div>
      <div class="text-xs text-gray-600">
        Cellules = sous-éléments indépendants et isolés
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-4 h-full flex flex-col">

<div class="flex items-start gap-6 mb-4">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/olivier-openclassrooms.png" alt="Olivier Mairet" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Olivier MAIRET</div>
  </div>
  <div class="flex-1">
    <h1 class="text-4xl font-bold text-gray-800 mb-2">10 ans de Clean Architecture</h1>
    <p class="text-lg text-gray-600">chez OpenClassrooms : le rêve, la réalité, les leçons</p>
  </div>
</div>

<div class="grid grid-cols-2 gap-4">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-4 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-3 flex items-center gap-2">
      <span class="text-3xl">✨</span> Le rêve
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Métier au centre, indépendant du framework</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Tests : de 30 minutes à quelques secondes</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>12 ans sans refonte majeure</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>600 UseCases aujourd'hui</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-orange-50 to-red-50 rounded-xl p-4 shadow-md border-l-4 border-orange-500">
    <h3 class="text-2xl font-bold text-orange-900 mb-3 flex items-center gap-2">
      <span class="text-3xl">😱</span> La réalité
    </h3>
    <div class="space-y-2 text-base text-gray-700">
      <div class="bg-white rounded p-2 border-l-2 border-red-400">
        <div class="font-semibold text-red-700 mb-1 text-base">Hyper complexe</div>
        <div class="text-sm">20 à 30 classes pour une route GET 🤯</div>
      </div>
      <div>
        <div class="font-semibold text-orange-700 mb-1 text-base">Simplifications nécessaires</div>
        <div class="text-sm">• Contrôleur unique pour tous les UseCases</div>
        <div class="text-sm">• Retrait de certaines interfaces</div>
        <div class="text-sm">• Hydratation au lieu d'assembleurs</div>
      </div>
    </div>
  </div>
</div>

<div class="mt-4 grid grid-cols-3 gap-3">
  <div class="bg-gradient-to-r from-green-100 to-emerald-100 rounded-lg p-3 shadow-md border-l-4 border-green-500">
    <div class="font-bold text-green-900 text-center text-sm">✅ Onboarding amélioré</div>
  </div>
  <div class="bg-gradient-to-r from-blue-100 to-indigo-100 rounded-lg p-3 shadow-md border-l-4 border-blue-500">
    <div class="font-bold text-blue-900 text-center text-sm">🎯 Pragmatisme retrouvé</div>
  </div>
  <div class="bg-gradient-to-r from-purple-100 to-pink-100 rounded-lg p-3 shadow-md border-l-4 border-purple-500">
    <div class="font-bold text-purple-900 text-center text-sm">🔗 Cohésion maintenue</div>
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
      <span class="text-3xl">📚</span> Rappels
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">SOLID</div>
        <div class="text-sm">Structurer le code pour permettre le changement</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">Compile vs Runtime</div>
        <div class="text-sm">Optimiser l'injection de dépendances</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">#Lazy</div>
        <div class="text-sm">Casser les chaînes de dépendance avec closures</div>
      </div>
    </div>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-4 shadow-md border-l-4 border-purple-500">
    <h3 class="text-sm font-bold text-purple-900 mb-2 flex items-center gap-1.5">
      <span class="text-base">⚡</span> Astuces de performance
    </h3>
    <div class="space-y-1 text-xs">
      <div class="bg-white p-2 rounded shadow-sm">
        <div class="font-bold text-purple-700 mb-0.5 text-sm">#[Lazy]</div>
        <div class="text-gray-600">Charge le service uniquement si utilisé</div>
      </div>
      <div class="bg-white p-2 rounded shadow-sm">
        <div class="font-bold text-blue-700 mb-0.5 text-sm">#[AutowireInline]</div>
        <div class="text-gray-600">Service anonyme configuré à la volée</div>
      </div>
      <div class="bg-white p-2 rounded shadow-sm">
        <div class="font-bold text-green-700 mb-0.5 text-sm">#[AutowireCallable]</div>
        <div class="text-gray-600">Closure vers une méthode de service</div>
      </div>
      <div class="bg-white p-2 rounded shadow-sm">
        <div class="font-bold text-orange-700 mb-0.5 text-sm">#[AutowireMethodOf]</div>
        <div class="text-gray-600">Syntaxe courte (nom = méthode)</div>
      </div>
      <div class="bg-white p-2 rounded shadow-sm">
        <div class="font-bold text-red-700 mb-0.5 text-sm">#[AutowireServiceClosure]</div>
        <div class="text-gray-600">Lazy instantiation du service</div>
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
        <span>Envoyer des notifications webpush à haute vitesse</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Parallélisation maximale des requêtes</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>cURL natif sans librairie pour contrôle total réseau</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-blue-500 mt-1">▸</span>
        <span>Éviter le busy looping avec curl_multi_select</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6 shadow-md border-l-4 border-purple-500">
    <h3 class="text-2xl font-bold text-purple-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">⚡</span> Techniques avancées
    </h3>
    <div class="space-y-3 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">HTTP/2 multiplexing</div>
        <div class="text-sm">Nombreuses requêtes sur une seule connexion</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">Multi-threading pcntl</div>
        <div class="text-sm">Fork par cœur CPU + shared memory (shmop)</div>
      </div>
      <div>
        <div class="font-semibold text-orange-700 mb-1">DNS round-robin</div>
        <div class="text-sm">Répartition charge sur multiples serveurs</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Résultat final</div>
        <div class="text-sm">180 000 req/s avec PHP 8.4 !</div>
      </div>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-4">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/xavier-leune.png" alt="Xavier Leune" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Xavier LEUNE</div>
  </div>
  <div class="flex-1">
    <h1 class="text-3xl font-bold text-gray-800 mb-2">Dashboard de monitoring temps réel</h1>
    <p class="text-base text-gray-600">
      <a href="https://github.com/xavierleune/180000-rps" class="text-blue-600 hover:underline">github.com/xavierleune/180000-rps</a>
    </p>
  </div>
</div>

<div class="flex-1 flex items-center justify-center">
  <img src="/img/180000-rps-dashboard.png" alt="Dashboard monitoring" class="max-h-full max-w-full object-contain rounded-lg shadow-xl border-2 border-gray-200" />
</div>

</div>

---
layout: default
---

<div class="px-8 py-4 h-full flex flex-col">

<div class="flex items-start gap-6 mb-3">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/edouard-courty.png" alt="Edouard Courty" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Edouard COURTY</div>
  </div>
  <div class="flex-1">
    <h1 class="text-3xl font-bold text-gray-800 mb-1">Créer un serveur MCP avec Symfony</h1>
    <p class="text-base text-gray-600">Le Model Context Protocol pour l'interaction avec les IA</p>
  </div>
</div>

<div class="grid grid-cols-2 gap-4 flex-1">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-3 shadow-md border-l-4 border-blue-500 flex flex-col">
    <h3 class="text-lg font-bold text-blue-900 mb-2 flex items-center gap-2">
      <span class="text-xl">🔧</span> Bundle Symfony : DX optimale
    </h3>
    <div class="space-y-2 text-xs text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">Exposition d'un outil</div>
        <pre class="text-xs bg-white p-2 rounded leading-tight"><code>#[AsTool(
  name: 'read_file',
  description: 'Reads a file...'
)]
class MyTool {
  public function __invoke(
    ReadFileSchema $payload
  ): ToolResult { ... }
}</code></pre>
      </div>
      <div>
        <div class="font-semibold text-purple-700">Gestion automatique</div>
        <div class="text-xs">Transport HTTP / stdio, sérialisation JSON, validation</div>
      </div>
    </div>
  </div>

  <div class="flex flex-col space-y-3">
    <div class="bg-gradient-to-br from-red-50 to-pink-50 rounded-xl p-3 shadow-md border-l-4 border-red-500">
      <h3 class="text-base font-bold text-red-900 mb-2 flex items-center gap-2">
        <span class="text-lg">⚠️</span> Limitations critiques
      </h3>
      <div class="grid grid-cols-2 gap-x-3 text-xs text-gray-700">
        <div class="space-y-0.5">
          <div>• Qualité/sécurité non garantie</div>
          <div>• Mauvais choix d'outil</div>
          <div>• Trop d'outils = IA perdue</div>
        </div>
        <div class="space-y-0.5">
          <div>• Hallucinations LLM</div>
          <div>• Prompt injection</div>
          <div class="text-blue-700 font-semibold">💡 Agent surveillant</div>
        </div>
      </div>
    </div>
    <div class="bg-indigo-50 rounded-xl p-3 shadow-md border-l-4 border-indigo-500">
      <h3 class="text-base font-bold text-indigo-900 mb-2 flex items-center gap-2">
        <span class="text-lg">🚀</span> Écosystème MCP en évolution
      </h3>
      <div class="space-y-1.5 text-xs text-gray-700">
        <div>
          <span class="font-semibold text-indigo-700">Specs en mutation: </span>
          <span>Protocole très récent, changements fréquents</span>
        </div>
        <div>
          <span class="font-semibold text-purple-700">Adoption en cours: </span>
          <span>Intégration progressive dans les outils IA</span>
        </div>
        <div>
          <span class="font-semibold text-blue-700">Initiative PHP: </span>
          <span>SDK officiel disponible</span>
        </div>
        <div>
          <span class="font-semibold text-green-700">symfony/ai: </span>
          <span>Support natif MCP, référence pour l'écosystème Symfony</span>
        </div>
      </div>
    </div>
  </div>
</div>

</div>

<!--
**Note orale - Cas d'usage Chatbot e-commerce** :

Édouard a présenté des démos impressionnantes d'un chatbot e-commerce où l'utilisateur peut :
- Passer une commande en langage naturel ("Je voudrais commander 2 t-shirts bleus")
- Modifier une adresse de livraison ("Change mon adresse pour 10 rue de la Paix, Paris")
- L'IA accède à la base de données et interagit avec elle via les outils mis à disposition sur le serveur MCP
- Conversation naturelle comme avec un agent humain

C'est bluffant mais on voit rapidement apparaître les limites mentionnées : qualité des données non vérifiées, risque de mauvais choix d'outils, etc.
-->

---
layout: default
---

<div class="px-8 py-3 h-full flex flex-col">

<div class="flex items-start gap-6 mb-2">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 110px;">
    <img src="/img/clement-talleu.png" alt="Clément Talleu" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">Clément TALLEU</div>
  </div>
  <div class="flex-1">
    <h1 class="text-4xl font-bold text-gray-800 mb-1">Créer un RAG en PHP</h1>
    <p class="text-base text-gray-600">Rendre accessible une architecture IA puissante</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-2.5">
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-2.5 shadow-md border-l-4 border-blue-500">
    <h3 class="text-lg font-bold text-blue-900 mb-1.5 flex items-center gap-2">
      <span class="text-xl">📚</span> Retrieval-Augmented Generation
    </h3>
    <div class="space-y-1.5 text-sm text-gray-700">
      <div class="bg-white rounded p-1.5 border-l-2 border-blue-400">
        <div class="font-semibold text-blue-700 mb-0.5 text-xs">Objectif</div>
        <div class="text-xs">Éviter les hallucinations en fournissant un contexte fiable extrait de nos propres données</div>
      </div>
      <div class="text-xs text-gray-600 italic">
        Architecture IA puissante qui contextualise les réponses des LLM avec des données vérifiées
      </div>
    </div>
  </div>

  <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-2.5 shadow-md border-l-4 border-purple-500">
    <h3 class="text-lg font-bold text-purple-900 mb-1.5 flex items-center gap-2">
      <span class="text-xl">🔧</span> Le processus en 5 étapes
    </h3>
    <div class="space-y-0.5 text-xs text-gray-700">
      <div class="bg-white p-1.5 rounded shadow-sm border-l-2 border-blue-400">
        <div><span class="font-bold text-blue-700">1. Chunking:</span> Découpage du texte source en petits morceaux</div>
        <div class="text-xs text-orange-700 mt-0.5">⚠️ Utiliser des outils IA spécialisés, pas de découpage manuel ou PHP</div>
      </div>
      <div class="bg-white p-1 rounded shadow-sm">
        <span class="font-bold text-purple-700">2. Embeddings:</span> Transformation en vecteurs mathématiques
      </div>
      <div class="bg-white p-1 rounded shadow-sm">
        <span class="font-bold text-green-700">3. Stockage:</span> PostgreSQL avec extension pg_vector
      </div>
      <div class="bg-white p-1 rounded shadow-sm">
        <span class="font-bold text-orange-700">4. Recherche:</span> Question utilisateur vectorisée, morceaux proches trouvés
      </div>
      <div class="bg-white p-1 rounded shadow-sm">
        <span class="font-bold text-red-700">5. Génération:</span> Morceaux injectés dans le prompt pour réponse précise
      </div>
    </div>
  </div>
</div>

<div class="mt-2">
  <div class="bg-gradient-to-r from-green-100 to-emerald-100 rounded-lg p-2 shadow-md border-l-4 border-green-500">
    <div class="font-bold text-green-900 text-sm mb-1">🛠️ Outils de l'écosystème PHP</div>
    <div class="text-xs text-gray-700">
      <span class="font-semibold">LLPhant</span> : librairie PHP pour manipuler les embeddings • <span class="font-semibold">Symfony AI</span> : initiative pour faciliter l'intégration IA
    </div>
  </div>
</div>

</div>

---
layout: default
---

<!--
**Note présentateur** : Histoire d'un POC en IA générative qui développe une app de recettes de cuisine à partir d'une photo. Un utilisateur s'est empoisonné en ajoutant une limace qu'il avait cru reconnaître, et ça lui semblait logique car lu dans un livre (Harry Potter). Cela illustre parfaitement le danger de baser un produit sur une technologie qui peut halluciner.
-->

<div class="px-8 py-6 h-full flex flex-col">

<div class="flex items-start gap-6 mb-8">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-2 shadow-md text-center" style="width: 130px;">
    <img src="/img/francois-zaninotto.png" alt="François Zaninotto" class="rounded-full w-14 h-14 object-cover mx-auto mb-1.5 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.7rem;">François ZANINOTTO</div>
  </div>
  <div class="flex-1">
    <h1 class="text-5xl font-bold text-gray-800 mb-3">L'évaluation des IAs</h1>
    <p class="text-xl text-gray-600">La recette secrète des agents pas trop bêtes</p>
  </div>
</div>

<div class="flex-1 grid grid-cols-2 gap-6">
  <div class="bg-gradient-to-br from-red-50 to-orange-50 rounded-xl p-6 shadow-md border-l-4 border-red-500">
    <h3 class="text-2xl font-bold text-red-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">⚠️</span> Le problème
    </h3>
    <ul class="space-y-2 text-base text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-red-500 mt-1">▸</span>
        <span>Les agents IA <strong>pilotés par du texte</strong>, pas du code</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-red-500 mt-1">▸</span>
        <span>Résultats <strong>imprévisibles et hallucinations</strong></span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-red-500 mt-1">▸</span>
        <span>Impossible de garantir qu'ils seront dans le vrai</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-red-500 mt-1">▸</span>
        <span class="bg-orange-100 px-2 py-1 rounded">Votre application <strong>va forcément planter</strong> un jour</span>
      </li>
    </ul>
  </div>

  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-6 shadow-md border-l-4 border-blue-500">
    <h3 class="text-2xl font-bold text-blue-900 mb-4 flex items-center gap-2">
      <span class="text-3xl">🧪</span> La solution
    </h3>
    <div class="space-y-2 text-base text-gray-700">
      <div>
        <div class="font-semibold text-blue-700 mb-1">Benchmarks complets</div>
        <div class="text-sm">Brute force de tous les modèles, températures, tailles...</div>
      </div>
      <div>
        <div class="font-semibold text-purple-700 mb-1">Agent de test</div>
        <div class="text-sm">Utiliser un LLM pour évaluer les réponses avec données de test humaines</div>
      </div>
      <div>
        <div class="font-semibold text-green-700 mb-1">Métriques multiples</div>
        <div class="text-sm">Justesse, format de sortie, rapidité, prix</div>
      </div>
    </div>
  </div>
</div>

<div class="mt-6 bg-gradient-to-br from-green-50 to-emerald-50 rounded-xl p-4 shadow-md border-l-4 border-green-500">
  <h3 class="text-xl font-bold text-green-900 mb-3 flex items-center gap-2">
    <span class="text-2xl">💡</span> Pro-Tips
  </h3>
  <div class="grid grid-cols-2 gap-4 text-sm text-gray-700">
    <div class="flex items-start gap-2">
      <span class="text-green-500 mt-1">✓</span>
      <span><strong>Outils</strong> : DeepEval, Ragas, LangSmith</span>
    </div>
    <div class="flex items-start gap-2">
      <span class="text-green-500 mt-1">✓</span>
      <span><strong>Stocker</strong> tous les résultats en BDD</span>
    </div>
    <div class="flex items-start gap-2">
      <span class="text-green-500 mt-1">✓</span>
      <span><strong>Inclure</strong> des données de production dans les tests</span>
    </div>
    <div class="flex items-start gap-2">
      <span class="text-green-500 mt-1">✓</span>
      <span><strong>Commencer</strong> avec le meilleur modèle puis affiner</span>
    </div>
  </div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-3 h-full flex flex-col">

<div class="flex items-start gap-4 mb-0.5">
  <div class="flex-shrink-0 bg-gradient-to-br from-blue-100 to-blue-200 rounded-lg p-1.5 shadow-md text-center" style="width: 100px;">
    <img src="/img/xavier-leune.png" alt="Xavier Leune" class="rounded-full w-12 h-12 object-cover mx-auto mb-1 border-2 border-blue-300" />
    <div class="text-xs font-semibold text-blue-900 leading-tight whitespace-nowrap" style="font-size: 0.65rem;">Xavier LEUNE</div>
  </div>
  <div class="flex-1">
    <h1 class="font-bold text-gray-800 mb-0" style="font-size: 1.65rem;">Comment être un bon dév à l'heure de l'IA ?</h1>
    <p class="text-sm text-gray-600">La seule constante dans notre métier, c'est le changement</p>
  </div>
</div>

<div style="display: grid; grid-template-columns: 1fr 1fr; grid-template-rows: auto auto; gap: 0.5rem; flex: 1;">

<div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl p-1.5 shadow-md border-l-4 border-blue-500">
<h3 class="font-bold text-blue-900 mb-1" style="font-size: 1.1rem;">📊 Impact de l'IA</h3>
<div style="display: flex; flex-direction: column; gap: 0.25rem; font-size: 0.65rem;">
<div class="bg-white p-1 rounded text-gray-700">
<div class="font-semibold text-green-700 mb-0.5">✅ Gain de productivité</div>
<div>Toutes les études convergent • 79% des devs l'utilisent</div>
</div>
<div class="bg-white p-1 rounded text-gray-700">
<div class="font-semibold text-red-700 mb-0.5">📉 Baisse des emplois</div>
<div>Tech layoffs depuis 2023 • 40% des licenciements chez MS</div>
</div>
<div class="bg-white p-1 rounded text-gray-700">
<div class="font-semibold text-purple-700 mb-0.5">🔄 Natural Language Devs</div>
<div>Coder en parlant à l'IA, pas en tapant du code</div>
</div>
</div>
</div>

<div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-1.5 shadow-md border-l-4 border-purple-500">
<h3 class="font-bold text-purple-900 mb-1" style="font-size: 1.1rem;">⚡ Nouveaux défis</h3>
<div style="display: flex; flex-direction: column; gap: 0.25rem; font-size: 0.65rem;">
<div class="bg-white p-1 rounded text-gray-700">
<div class="font-semibold text-red-700 mb-0.5">🧠 Charge cognitive accrue</div>
<div>Code plus vite • Plus de review • Charge mentale élevée</div>
</div>
<div class="bg-white p-1 rounded text-gray-700">
<div class="font-semibold text-orange-700 mb-0.5">⚠️ Désappropriation du code</div>
<div>Perte de contrôle • Complexité artificielle • Responsable en prod</div>
</div>
</div>
</div>

<div class="bg-gradient-to-br from-orange-50 to-red-50 rounded-xl p-1.5 shadow-md border-l-4 border-orange-500">
<h3 class="font-bold text-orange-900 mb-1" style="font-size: 1.1rem;">🎭 Mode passagère ?</h3>
<div style="display: flex; flex-direction: column; gap: 0.25rem; font-size: 0.65rem;">
<div class="bg-white p-1 rounded text-gray-700">
<div class="font-semibold text-orange-700 mb-0.5">📜 Déjà vu ?</div>
<div>Visual Basic, Dreamweaver, UML, No-Code...</div>
</div>
<div class="bg-white p-1 rounded text-gray-700">
<div class="font-semibold text-red-700 mb-0.5">💸 Bulle IA ?</div>
<div>Coûts colossaux • 3,69 milliards d'abonnés pour financer les datacenters</div>
</div>
</div>
</div>

<div class="bg-gradient-to-br from-green-50 to-emerald-50 rounded-xl p-1.5 shadow-md border-l-4 border-green-500">
<h3 class="font-bold text-green-900 mb-1" style="font-size: 1.1rem;">🎯 S'adapter</h3>
<div style="display: flex; flex-direction: column; gap: 0.25rem; font-size: 0.65rem;">
<div class="bg-white p-1 rounded text-gray-700">
<div class="font-semibold text-blue-700 mb-0.5">🎓 Formation continue</div>
<div>Maîtriser les outils IA dès maintenant</div>
</div>
<div class="bg-white p-1 rounded text-gray-700">
<div class="font-semibold text-purple-700 mb-0.5">💡 Rester vigilant</div>
<div>Si bulle éclate : coût tokens ↗ • Arbitrages • Outils restent</div>
</div>
</div>
</div>

</div>

<div class="mt-3 bg-gradient-to-r from-green-100 to-emerald-100 rounded-lg p-1.5 shadow-lg border-l-4 border-green-600">
  <div class="font-bold text-green-900 text-center text-sm">🎓 Formez-vous maintenant • Le plus tôt vous maîtriserez ces outils, le plus employable vous serez</div>
</div>

</div>

---
layout: default
---

<div class="px-8 py-3 h-full flex flex-col">

<h1 class="text-xl font-bold text-gray-800 mb-2 text-center">Pour finir...</h1>

<div class="flex-1 flex flex-col justify-center space-y-2">

<div class="grid grid-cols-2 gap-3">
  <div class="bg-gradient-to-r from-purple-100 to-pink-100 rounded-lg p-2 shadow-md border-l-4 border-purple-500">
    <h2 class="text-sm font-bold text-purple-900 mb-1 text-center">🎭 Les talks "OVNI"</h2>
    <p class="text-xs text-gray-700 text-center mb-1" style="font-size: 0.7rem;">
      Chaque journée se terminait par un talk non-tech
    </p>
    <div class="bg-white rounded p-1.5 shadow-sm">
      <div class="text-xs font-bold text-purple-800 mb-0.5">⭐ Coup de cœur : Thibaut SOULCIÉ</div>
      <div class="text-gray-600 italic mb-0.5" style="font-size: 0.65rem;">"C'est pas très marrant de devoir être drôle tout le temps"</div>
      <div class="text-gray-700" style="font-size: 0.7rem;">
        Dessinateur satirique, un véritable <strong>one man show</strong> plein d'autodérision !
      </div>
    </div>
  </div>

  <div class="bg-gradient-to-r from-blue-100 to-cyan-100 rounded-lg p-2 shadow-md border-l-4 border-blue-500">
    <h2 class="text-sm font-bold text-blue-900 mb-1 text-center">📚 Et bien d'autres talks...</h2>
    <p class="text-gray-700 text-center" style="font-size: 0.7rem;">
      Plus de <strong>40 conférences</strong> sur 2 jours : Symfony 8, PHP 8.5, Laravel, Kubernetes, Security, RGAA...
    </p>
    <div class="mt-1.5 bg-orange-50 rounded p-1.5 border-l-4 border-orange-400">
      <p class="text-xs font-bold text-orange-900 text-center">
        📹 Replays disponibles dès le <strong>1er décembre 2025</strong>
      </p>
      <p class="text-gray-700 text-center" style="font-size: 0.7rem;">
        🎄 Une vidéo par jour, comme un calendrier de l'avent !
      </p>
    </div>
  </div>
</div>

<div class="bg-gradient-to-r from-green-100 to-emerald-100 rounded-lg p-2 shadow-md border-l-4 border-green-500">
  <p class="text-sm font-bold text-green-900 text-center mb-0.5">
    🙏 Merci à l'AFUP pour cette organisation impeccable !
  </p>
  <p class="text-xs text-green-800 text-center">
    👋 Rendez-vous l'année prochaine au Forum PHP 2026 !
  </p>
</div>

</div>

</div>
