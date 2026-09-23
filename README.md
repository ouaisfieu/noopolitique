# Noopolitique

Encyclopédie en ligne consacrée à la **noopolitique** : noosphère, psychopouvoir, gouvernementalité algorithmique, guerre cognitive, doctrines d'influence (RAND, Chine, Russie, UE, France), études de cas (Doppelgänger, VIGINUM), neurotechnologies et neurodroits.

Site : <https://ouaisfieu.github.io/noopolitique/>

## Contenu

| Rubrique | Pages |
| --- | --- |
| Comprendre | `noopolitique/` (article pilier, FAQ) |
| Notions | noosphère, psychopouvoir, gouvernementalité algorithmique, guerre cognitive, neurotechnologies, neurodroits, sécurité épistémique |
| Doctrines | noopolitik (RAND), Trois guerres (Chine), contrôle réflexif (Russie), effet Bruxelles (UE), L2I (France) |
| Études de cas | Doppelgänger, VIGINUM |
| Référence | penseurs, glossaire, chronologie, bibliographie, à propos |

## Technique

- **HTML et CSS purs**, zéro JavaScript, zéro dépendance, zéro cookie ou traceur.
- Une seule feuille de style : `assets/style.css` (thème clair/sombre automatique, responsive, impression).
- **SEO** : balises `title`/`description` uniques, `canonical`, `hreflang`, Open Graph et Twitter Cards, `sitemap.xml`, `robots.txt`, flux Atom (`feed.xml`), `llms.txt`.
- **Web sémantique** : JSON-LD schema.org sur chaque page (`WebSite`, `Organization`, `Person`, `Article`, `BreadcrumbList`, `FAQPage`, `DefinedTermSet`, `ItemList`), liens `sameAs` vers Wikipédia/Wikidata, balisage `dfn`, `cite`, `time`, `abbr`, attributs `lang` sur les termes étrangers.
- Accessibilité : lien d'évitement, fil d'Ariane, repères ARIA, contrastes vérifiés, typographie française (espaces insécables).
- HTML validé avec le Nu HTML Checker (W3C).

## Publication sur GitHub Pages

Dans **Settings → Pages**, choisir *Source : Deploy from a branch*, branche `main`, dossier `/ (root)`. Le fichier `.nojekyll` désactive le traitement Jekyll.

Si le site passe sur un domaine personnalisé, remplacer `https://ouaisfieu.github.io/noopolitique/` dans les balises `canonical`, les JSON-LD, `sitemap.xml`, `robots.txt`, `feed.xml` et `llms.txt`, ainsi que le chemin `/noopolitique/` dans `404.html` et `manifest.webmanifest`.

## Rédaction et licence

Textes rédigés par Claude (IA, Anthropic) à partir de dossiers de recherche fournis par l'éditeur (anonyme), croisés avec des sources publiques vérifiées. Contenu sous licence [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.fr).

Signaler une erreur : ouvrir un ticket (*issue*) sur ce dépôt.
