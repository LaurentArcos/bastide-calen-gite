# La Bastide Calen – site vitrine de démonstration

Démo d'un site pour une maison d'hôtes **fictive** du Var (massif des Maures).

## Contenu

- Grand visuel et barre de recherche façon site d'hôtel
- Galerie des quatre chambres
- Alentours (Collobrières, chartreuse de la Verne, Hyères, Porquerolles)
- **Réservation en direct** : calendrier de disponibilités par chambre (dates déjà prises barrées, impossible de chevaucher une nuit réservée), calcul des nuits et du total, demande de réservation. Prévu pour être synchronisé avec Airbnb et Booking (iCal) et relié à un workflow n8n (blocage des dates, lien de paiement de l'acompte)

## Technique

HTML, CSS et JavaScript sans framework ni étape de build, responsive et accessible (calendrier navigable au clavier, contrastes AA). Déployé sur Vercel.

Les éléments entre crochets (`[PRIX]`, `[ADRESSE]`…) et les avis sont des emplacements à remplacer par les informations réelles du client. Les prix affichés sont fictifs.

Photos d'illustration : [Pexels](https://www.pexels.com).

---

Conçu et réalisé par [Laurent Arcos](https://cv-interactif-laurentarcos.vercel.app). Maison fictive : toute ressemblance avec un établissement existant serait fortuite.
