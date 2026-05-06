---
title: NotePatch Politique de Confidentialité
---

# NotePatch — Politique de Confidentialité

**Date d'entrée en vigueur :** 2026-04-07
**Dernière mise à jour :** 2026-05-06

La présente Politique de Confidentialité décrit comment NotePatch (« nous » ou « l'app ») traite les informations lorsque vous utilisez l'application NotePatch pour iOS.

## Notre position sur la vie privée

NotePatch est conçu pour être **privé par défaut**. Les fonctions principales — scan, recadrage, masquage et impression — fonctionnent entièrement hors ligne, sans compte. Nous ne collectons, ne transmettons ni ne partageons aucune donnée personnelle, sauf si vous choisissez d'utiliser une fonction qui le nécessite.

## Informations que nous ne collectons PAS

- Nous ne collectons **aucun** identifiant personnel (nom, e-mail, numéro de téléphone, identifiant de compte).
- Nous ne collectons **aucun** identifiant d'appareil (IDFA, IDFV, identifiant publicitaire).
- Nous ne suivons **pas** votre utilisation de l'app.
- Nous n'utilisons **aucun** service d'analyse, de rapport de plantage ni de télémétrie.
- Nous n'incluons **aucun** SDK publicitaire ou de suivi.
- Nous n'accédons **pas** à vos contacts, calendrier, localisation, microphone ni à aucune donnée sans rapport avec les fonctions principales.

## Informations que vous fournissez à l'app (stockage local uniquement)

Pour fonctionner, NotePatch a besoin d'accéder à certaines fonctions de l'appareil. Toutes les données restent exclusivement sur votre appareil :

| Autorisation | Utilité | Destination des données |
|---|---|---|
| **Appareil photo** | Scanner des notes manuscrites ou des pages avec le scanner de documents | Traitées sur l'appareil. Jamais téléversées. |
| **Photothèque (lecture)** | Importer des photos et captures existantes pour créer des patches | Seul l'identifiant de la ressource dans la photothèque est référencé. |
| **Photothèque (écriture)** | (Optionnel) Enregistrer les patches traités dans la photothèque | Uniquement lorsque vous déclenchez l'exportation. |
| **Imprimante (AirPrint)** | Envoyer le PDF généré vers une imprimante à proximité via le réseau local | Envoyé uniquement à l'imprimante que vous sélectionnez. |

## Reconnaissance de texte Smart Text

NotePatch propose deux modes de reconnaissance de texte :

### OCR sur l'appareil

L'OCR sur l'appareil utilise le framework Vision d'Apple pour extraire du texte des images. Tout le traitement a lieu localement. **Aucune donnée n'est transmise.**

### Reconnaissance IA (y compris Smart Fix)

Lorsque vous choisissez la reconnaissance IA — ou que vous utilisez Smart Fix pour relancer la reconnaissance d'une source avec un indice — l'image sélectionnée est envoyée vers une API cloud sécurisée tierce pour l'extraction de texte. Les utilisateurs gratuits disposent d'un quota à vie de reconnaissances IA gratuites ; les abonnés Pro y ont un accès illimité.

- **Ce qui est envoyé :** L'image que vous avez sélectionnée pour la reconnaissance. Lorsque vous utilisez Smart Fix, l'indice optionnel que vous fournissez (une étiquette courte comme « ceci est une formule mathématique », ou l'un des choix prédéfinis comme « 🎨 L'image entière est une illustration ») est envoyé en même temps que l'image.
- **Mode de traitement :** L'image et tout indice fourni sont utilisés uniquement pour l'extraction de texte.
- **Conservation des données :** Le fournisseur de l'API **ne stocke pas, n'enregistre pas et n'utilise pas l'image ni l'indice pour l'entraînement de modèles**.
- **Quand cela se produit :** Uniquement lorsque vous appuyez sur l'option de reconnaissance IA ou que vous sélectionnez / saisissez un indice Smart Fix. Cela ne se produit jamais automatiquement ni en arrière-plan.

L'app n'effectue aucune autre requête réseau. NotePatch fonctionne normalement en mode avion — la reconnaissance IA affiche simplement un message hors ligne.

## Abonnement et facturation

Les abonnements NotePatch Pro sont gérés entièrement par Apple via l'App Store. Nous ne collectons pas et n'avons pas accès à vos informations de paiement, données de carte bancaire ni Apple ID.

## Comment nous stockons vos données

- Toutes les notes, patches, historiques de modification et préférences sont stockés **uniquement sur votre appareil**, en utilisant les frameworks de stockage local d'Apple (SwiftData et UserDefaults).
- Les données ne quittent votre appareil que lorsque :
  - Vous imprimez vers une imprimante sélectionnée (envoi par réseau local uniquement).
  - Vous partagez un PDF via la fonction de partage iOS.
  - Vous utilisez la reconnaissance IA (Pro), qui envoie l'image sélectionnée vers une API cloud.

## Vie privée des enfants

NotePatch ne collecte sciemment aucune information de quiconque, y compris des enfants de moins de 13 ans. L'app est adaptée à tous les publics.

## Vos droits

Étant donné que NotePatch ne collecte ni ne stocke de données personnelles de notre côté, il n'y a aucune donnée que nous puissions consulter, exporter, corriger ou supprimer. La suppression de l'app de votre appareil efface tout le contenu NotePatch stocké localement.

## Modifications de cette politique

Si nous modifions la façon dont l'app traite les données, nous mettrons à jour cette politique avec une nouvelle date de « Dernière mise à jour ». Les changements importants seront reflétés dans les notes de mise à jour de l'App Store.

## Contact

Pour toute question concernant cette politique de confidentialité, contactez-nous à :

**E-mail :** ai.neocai@gmail.com

---

*Les fonctions principales de NotePatch restent entièrement hors ligne et privées. Les données ne quittent votre appareil que lorsque vous choisissez d'imprimer, de partager ou d'utiliser la reconnaissance IA.*

[← Retour à NotePatch](./) · [foxineo Legal](../)
