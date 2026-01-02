📄 Politique de confidentialité — Session Pêche
1. Introduction

L’application Session Pêche respecte votre vie privée. Cette politique explique quelles données sont collectées, pourquoi, comment elles sont utilisées et protégées, et quels sont vos droits concernant ces informations.

2. Données collectées

L’application peut collecter les informations suivantes :

a) Données d’authentification (via Google Sign-In)

Adresse email

Identifiant utilisateur unique (UID) généré par Firebase

Nom et photo de profil (si autorisés par l’utilisateur)

Ces données sont fournies par Google lors de la connexion et sont stockées dans Firebase Authentication et Firestore dans la collection users/{uid}.

b) Données applicatives stockées dans Firestore

Sessions de pêche créées par l’utilisateur (dates, lieux, notes, espèces ciblées, etc.)

Prises de poissons enregistrées (espèce, poids, taille, photos, conditions, etc.)

Ces données sont stockées uniquement si l’utilisateur les crée dans l’app.

c) Données de localisation (optionnelles)

Si l’utilisateur l’autorise, l’application peut accéder à :

La localisation GPS précise, pour enregistrer le lieu d’une session ou l’afficher sur une carte.

⚠ Ces données ne sont jamais collectées automatiquement, uniquement à l’action explicite de l’utilisateur (ex : "enregistrer ma position").

3. Utilisation des données

Les informations collectées servent uniquement à :

Permettre la connexion sécurisée avec Google

Sauvegarder et synchroniser les données entre les appareils de l’utilisateur

Afficher les sessions et prises dans l’app

Améliorer l’expérience utilisateur (ex : pré-remplir un lieu sur la carte)

L’application ne vend aucune donnée, ne les partage pas avec des tiers publicitaires, et ne les utilise pas à d’autres fins.

4. Partage des données

Les données peuvent être partagées uniquement dans les cas suivants :

À la demande de l’utilisateur (ex : partage d’une session avec un autre utilisateur via une future fonctionnalité)

Si requis par la loi ou pour répondre à une demande légale officielle

5. Stockage et sécurité

Les données sont stockées sur les serveurs sécurisés de :

Google (authentification OAuth)

Firebase / Firestore (base de données et authentification)

Des règles de sécurité Firestore sont appliquées pour garantir que :

Un utilisateur ne peut lire et écrire que ses propres données

L’accès internet est requis uniquement pour la synchronisation avec Firebase.

6. Cookies & identifiants

L’application n’utilise pas de cookies ni d’identifiants de suivi publicitaire.

7. Données sur l’appareil

L’application utilise également Room Database (base locale) pour stocker les sessions hors-ligne, mais :

Ces données restent dans l’appareil de l’utilisateur

Elles ne sont synchronisées dans Firestore que si l’utilisateur est connecté

8. Conservation des données

Les données sont conservées tant que l’utilisateur garde son compte Firebase.

Si l’utilisateur supprime son compte :

Les données associées dans Firebase Authentication et Firestore pourront être supprimées conformément aux mécanismes Firebase.

9. Droits de l’utilisateur

Vous pouvez à tout moment :

Vous déconnecter de votre compte Google

Refuser les permissions (ex : localisation)

Demander des informations sur les données stockées dans votre compte Firebase

10. Contact

Pour toute question concernant vos données ou cette politique, vous pouvez nous contacter à :

📧 Email : support@sessionpeche.app

11. Modifications de cette politique

Cette politique peut être mise à jour pour des raisons légales ou fonctionnelles.
La version mise à jour sera publiée en ligne et dans l’application.
