# orfo-brand — assets publics de marque ORFO

Repo **public** hébergeant les logos ORFO servis en ligne (notamment pour les
signatures email, via le CDN jsDelivr).

> Ce dépôt ne contient que des assets destinés à être publics. Le système de
> génération des signatures et les fiches membres restent dans le repo privé
> `OrfoBe/Synorfo` (`apps/email-signatures/`).

## Logos disponibles

| Fichier | Marque | Fond | Usage |
| --- | --- | --- | --- |
| `orfo-logo.png` | ORFO (générique) | noir | signatures email (fond clair) |
| `orfo-studio-logo.png` | ORFO Studio | noir | signatures email (fond clair) |
| `orfo-labs-logo.png` | ORFO Labs | noir | signatures email (fond clair) |
| `orfo-studio-blanc.png` | ORFO Studio | transparent (glyphes blancs) | configurateur de plans (bandeau sombre) |
| `orfo-signature.png` | ORFO | cadre noir, logo ivoire | signatures email depuis le 2026-11-23 |
| `orfo-show-signature.png` | ORFO Show | cadre noir, logo ivoire | signatures email depuis le 2026-11-23 |
| `orfo-labs-signature.png` | ORFO Labs | cadre noir, logo ivoire | signatures email depuis le 2026-11-23 |
| `orfo-leds-signature.png` | ORFO LEDs | cadre noir, logo ivoire | signatures email depuis le 2026-11-23 |
| `orfo-store-signature.png` | ORFO Store | cadre noir, logo ivoire | signatures email depuis le 2026-11-23 |

Noms volontairement génériques (pas de suffixe `-signature`) pour les quatre premiers : ces logos peuvent
servir à autre chose que les signatures email. Les fichiers `*-signature.png` suivent la charte du
2026-11-23 (logo ivoire dans un cadre noir aux coins ORFO) et ne servent qu'aux signatures ;
ils sont générés par `apps/email-signatures/scripts/make-logo.js` du dépôt privé `Synorfo`.

⚠️ `orfo-studio-blanc.png` est **blanc sur transparent** : lisible uniquement sur
fond sombre. Pour un fond clair, utiliser `orfo-studio-logo.png`.

## Exports complets de la charte (`exports/`)

Le dossier [`exports/`](exports/) contient le jeu complet des exports de logos
fournis par le design (toutes marques ORFO / Studio / Labs / LEDS / Store, plus
l'icône), dans leurs déclinaisons couleur × fond, sous leurs noms d'origine
(codes `A1`, `B1`, `C2`… de la charte). Source de référence pour piocher une
variante ; les fichiers à la racine ci-dessus sont ceux réellement servis en
production.

## URL publique (jsDelivr)

Les logos sont servis via jsDelivr, un CDN gratuit adossé à GitHub :

```
https://cdn.jsdelivr.net/gh/OrfoBe/orfo-brand@main/orfo-logo.png
https://cdn.jsdelivr.net/gh/OrfoBe/orfo-brand@main/orfo-studio-logo.png
```

- `@main` sert toujours la dernière version (cache CDN ~7 j).
- Pour figer une version, créer un tag git (`vX`) et utiliser `@vX` dans l'URL.

Ces logos sont exportés en 2× (retina) : les afficher à la moitié de leurs
dimensions réelles.
