# orfo-brand — assets publics de marque ORFO

Repo **public** hébergeant les logos ORFO servis en ligne (notamment pour les
signatures email, via le CDN jsDelivr).

> Ce dépôt ne contient que des assets destinés à être publics. Le système de
> génération des signatures et les fiches membres restent dans le repo privé
> `OrfoBe/orfo-email-signatures`.

## Logos disponibles

| Fichier | Marque |
| --- | --- |
| `orfo-logo.png` | ORFO (générique) |
| `orfo-studio-logo.png` | ORFO Studio |

Noms volontairement génériques (pas de suffixe `-signature`) : ces logos peuvent
servir à autre chose que les signatures email.

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
