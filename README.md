# Planning des formations — JFN Center · Session 2026-2027

Planning détaillé des 11 formations du JFN Center, séance par séance,
du **lundi 26 octobre 2026** au **vendredi 23 avril 2027**.

- 78 séances par formation, les lundi, mercredi et vendredi
- Chaque jour de cours est donné deux fois : **présentiel 08:30 – 12:30**, **en ligne 18:30 – 21:30**
- Page unique, autonome : le logo est intégré, aucune ressource externe n'est chargée

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | la page complète du planning |
| `vercel.json` | configuration d'hébergement (pas d'indexation par les moteurs de recherche) |

## Mise en ligne sur Vercel

1. Sur [vercel.com/new](https://vercel.com/new), choisir **Import Git Repository** et sélectionner ce dépôt.
2. Laisser les réglages par défaut : *Framework Preset* = **Other**, pas de commande de build, répertoire de sortie vide.
3. Cliquer **Deploy**.

Chaque `git push` sur la branche principale redéploie le site automatiquement.

## Nom de domaine

Dans **Settings → Domains**, ajouter par exemple `planning.jfn-academy.com`,
puis créer l'enregistrement CNAME correspondant chez le registrar du domaine.

## Confidentialité

`vercel.json` demande aux moteurs de recherche de ne pas indexer la page,
mais l'URL reste accessible à toute personne qui la possède.
Pour un accès réellement restreint : **Settings → Deployment Protection → Password Protection**.

## Mise à jour

Remplacer `index.html`, puis `git commit` et `git push`. L'URL reste la même.

---

JFN Center · Technology Training · *Learn. Innovate. Excel.*
