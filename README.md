# 3WVKV.github.io

Site public de **Quiz TikTok Studio**, servi à la racine du domaine
`https://3wvkv.github.io/`.

| Fichier | Rôle |
|---|---|
| `index.html` | page vitrine — l'adresse à donner au portail TikTok dans « official website » |
| `callback.html` | page de retour OAuth : elle affiche le code d'autorisation à reporter dans l'application. Elle n'émet **aucune requête réseau** — le code ne quitte pas le navigateur |
| `privacy.html` | politique de confidentialité |
| `terms.html` | conditions d'utilisation |

## Pourquoi la racine du domaine, et non un dépôt de projet

TikTok vérifie la propriété d'un domaine en demandant d'y déposer un fichier
**à la racine** (`https://3wvkv.github.io/tiktok<...>.txt`). Seul le dépôt de site
utilisateur — celui qui porte le nom du compte — sert cette racine ; un dépôt de projet
sert `https://3wvkv.github.io/<projet>/`, où le fichier ne serait pas trouvé.

Le fichier de vérification se dépose donc ici, à côté de `index.html`, puis se pousse
comme le reste.
