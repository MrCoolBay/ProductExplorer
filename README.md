# Product Explorer

Application Android (Jetpack Compose) servant de base aux TP du bloc 2.

## TP4 : Écran de détail produit

Ce TP construit un écran de détail produit avec les composants fondamentaux de Compose :
`Text`, `Button`, `Icon`, `Image`, `Card`, `TextField` et `Preview`.

### Déroulé (un commit par étape)

| Étape | Contenu |
|---|---|
| 1 | Data class `ProductUi` |
| 2 | Produit d'exemple `sampleProduct()` |
| 3 – 4 | Premier `ProductDetailScreen` dans le `Scaffold` |
| 5 | Preview de l'écran |
| 6 | Extraction de `ProductHeader` |
| 7 | Typographie `MaterialTheme.typography` |
| 8 | Carte prix `ProductPriceCard` |
| 9 | Image produit `ProductImage` |
| 10 | Note avec icône `ProductRating` (+ dépendance `material-icons-extended`) |
| 11 | Carte `ProductAvailabilityCard` |
| 12 | Section `ProductDescription` |
| 13 | `ProductWarrantyField` (OutlinedTextField en lecture seule) |
| 14 | Bouton réutilisable `AddToCartButton` |
| 15 | Nettoyage de `ProductDetailScreen` |
| 16 | Deuxième preview (produit en rupture de stock) |

## TP5 : Écran d'accueil

Ce TP ajoute l'écran d'accueil `ProductHomeScreen`, affiché au lancement, avec les layouts Compose :
`Column`, `Row`, `Box`, `Spacer` et `Surface`. L'écran détail reste disponible dans le code.

### Déroulé (un commit par étape)

| Étape | Contenu |
|---|---|
| 1 – 2 | `ProductHomeScreen` affiché depuis `MainActivity`, structure en `Column` |
| 3 | En-tête réutilisable `HomeHeader` |
| 4 | Espacement avec `Spacer` |
| 5 | Fausse barre de recherche `SearchPreviewBar` (`Surface`) |
| 6 | Produit mis en avant `FeaturedProductSection` |
| 7 | Ligne prix / note / stock `ProductQuickInfoRow` (`Row` + `weight`) |
| 8 | Catégories `CategoryChip` et `CategoriesSection` |
| 9 | Bloc « Offre du jour » avec badge `DailyOfferBox` (`Box` + `align`) |
| 10 | Écran d'accueil final et preview `ProductHomeScreenPreview` |

## Lancer le projet

Ouvrir le dossier dans Android Studio, laisser Gradle synchroniser, puis lancer la configuration `app`
ou ouvrir les previews de `MainActivity.kt`.

Les tags `tp4-final` et `tp5-final` marquent la fin de chaque TP.
