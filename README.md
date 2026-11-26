# tecknologiks_website

Site de tecknologiks.com : page d'accueil qui renvoie vers le site de chaque application, mentions légales et `app-ads.txt` (AdMob).

Site statique publié avec GitHub Pages (workflow `.github/workflows/pages.yml`, à chaque push sur `main`). Réglage à faire une fois sur GitHub : Settings → Pages → Source : « GitHub Actions ». Le domaine est donné par `CNAME`.

| Fichier | Rôle |
| --- | --- |
| `index.html`, `fr/index.html` | Accueil (anglais, français) : liens vers le site de chaque app (trente30, tapnrepeat, cp, reverse, drive, verbes, tdm `.tecknologiks.com`) ; icônes dans `assets/` |
| `legal.html`, `fr/mentions-legales.html` | Mentions légales |
| `tiktok-terms.html`, `tiktok-privacy.html` | CGU et politique de confidentialité de l'appli TikTok `viede-dev-stats` (exigées par la revue TikTok for Developers) |
| `tiktok*.txt` | Fichier de vérification du préfixe d'URL `https://tecknologiks.com/` pour TikTok for Developers (ne pas supprimer) |
| `app-ads.txt` | Vendeurs autorisés AdMob, servi à la racine du domaine |

Le site ne charge aucune ressource externe et ne dépose aucun cookie.
