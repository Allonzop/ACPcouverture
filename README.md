# Maquette — ACP Couverture (Donchery, 08)

Maquette commerciale réalisée par **KRAON** (Pensabene Allonzo, Vrigne-aux-Bois)
pour la prospection d'ACP Couverture, artisan couvreur à Donchery.

## ⚠️ À lire avant de publier

**Le logo et les photos appartiennent à ACP Couverture.** Ils proviennent de la
fiche Google Business publique de l'entreprise et sont utilisés ici pour une
maquette de démonstration, avant toute relation commerciale.

→ **Mettre ce dépôt en privé.** Une maquette au nom d'une entreprise qui n'est pas
encore cliente n'a rien à faire dans un dépôt public.

Le site est également en `noindex` (voir `netlify.toml` et `robots.txt`) pour ne pas
apparaître dans Google et créer un doublon face au vrai site futur.

## Contenu

```
index.html                 le site complet (29 Ko)
photos/                    les 6 photos de l'entreprise
netlify.toml               config Netlify + en-têtes noindex
robots.txt                 blocage de l'indexation
```

Aucune dépendance, aucun build. Les polices sont chargées depuis Google Fonts.

## Mise en ligne

**Option 1 — Netlify Drop (le plus rapide, ~30 secondes)**
1. Aller sur https://app.netlify.com/drop
2. Glisser le dossier entier
3. Récupérer l'URL et la coller dans le mail de prospection

**Option 2 — GitHub + Netlify**
1. Créer un dépôt **privé** et y pousser ces fichiers
2. Sur Netlify : *Add new site → Import an existing project*
3. Publish directory : `.` — pas de commande de build

**Option 3 — GitHub Pages**
Fonctionne aussi (`Settings → Pages → branche main`), mais **impose un dépôt public**
sur le plan gratuit. Déconseillé ici, voir l'avertissement plus haut.

## Ce qui reste à faire pour la version finale

- [ ] Récupérer le logo d'origine (AI, EPS, PDF ou PNG haute définition) — celui du site est une revectorisation faite à partir d'une photo de bâche
- [ ] Confirmer les couleurs exactes auprès de son imprimeur (relevées par temps couvert, ±5 % sur l'orange)
- [ ] Remplacer les 3 avis reformulés par les avis Google d'origine (widget officiel)
- [ ] Obtenir le SIRET et la forme juridique pour les mentions légales
- [ ] Faire valider les fiches chantier (matériaux, communes, durées sont des hypothèses)
- [ ] Réserver le nom de domaine — `acp-couverture.fr` est pris par un homonyme à Salon-de-Provence

## Identité visuelle relevée

| | |
|---|---|
| Anthracite | `#22293A` |
| Orange | `#E08B3A` |
| Bleu clair | `#BFD8E0` |
| Baseline | « L'Artisan qu'il vous faut » |
| Métiers | Couverture · Charpente · Zinguerie · Pose de Velux |
