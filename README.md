# tecknologiks_website

Site de tecknologiks.com : page d'accueil qui renvoie vers le site de chaque application, mentions légales et `app-ads.txt` (AdMob).

Site statique publié avec GitHub Pages (workflow `.github/workflows/pages.yml`, à chaque push sur `main`). Réglage à faire une fois sur GitHub : Settings → Pages → Source : « GitHub Actions ». Le domaine est donné par `CNAME`.

| Fichier | Rôle |
| --- | --- |
| `index.html`, `fr/index.html` | Accueil (anglais, français) : liens vers trente30.tecknologiks.com et tapnrepeat.tecknologiks.com |
| `legal.html`, `fr/mentions-legales.html` | Mentions légales |
| `app-ads.txt` | Vendeurs autorisés AdMob, servi à la racine du domaine |

Le site ne charge aucune ressource externe et ne dépose aucun cookie.
