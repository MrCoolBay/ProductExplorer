# Product Explorer — TP4 : Écran de détail produit

Application Android (Jetpack Compose) servant de base aux TP du bloc 2.
Ce TP construit un écran de détail produit avec les composants fondamentaux de Compose :
`Text`, `Button`, `Icon`, `Image`, `Card`, `TextField` et `Preview`.

## Déroulé (un commit par étape)

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

## Lancer le projet

Ouvrir le dossier dans Android Studio, laisser Gradle synchroniser, puis lancer la configuration `app`
ou ouvrir les previews de `MainActivity.kt`.
