# 🔒 Sécurité de votre compte Qlub

Ce guide vous explique comment sécuriser et gérer votre compte Qlub.

## 🔑 Mise à jour de votre mot de passe

Pour garantir la sécurité de votre compte :

1. Connectez-vous à votre compte
2. Accédez aux "Paramètres" > "Compte" > "Paramètres du compte"
3. Entrez votre mot de passe actuel
4. Créez un nouveau mot de passe fort et confirmez-le
5. Cliquez sur "Enregistrer les modifications"

Conseils pour un bon mot de passe :
- Minimum 12 caractères
- Mélangez lettres, chiffres et symboles
- Évitez les informations personnelles
- Utilisez une phrase secrète facile à retenir mais difficile à deviner
- Ne réutilisez pas vos anciens mots de passe ou des mots de passe utilisés sur d'autres sites

## 🔐 Authentification à deux facteurs (2FA)

L'authentification à deux facteurs (parfois appelée "Autorisation à deux facteurs") ajoute une couche de sécurité cruciale en demandant une deuxième forme de vérification lors de la connexion.

### Activation
1. Allez dans "Paramètres" > "Compte" > "Authentification à deux facteurs"
2. Cliquez sur "Mise en place"
3. Balayez le code QR ou entrez le code secret dans votre application TOTP
4. Entrez le code généré par votre application
5. Cliquez sur "Activer"

### Codes de secours
- Après l'activation, **sauvegardez vos codes de secours**
- Conservez-les dans un endroit très sûr (gestionnaire de mots de passe, document chiffré, impression papier sécurisée)
- Ces codes vous permettront d'accéder à votre compte si vous perdez l'accès à votre méthode 2FA
- Ne les partagez jamais

## 📱 Sessions d'utilisation

Gérez et surveillez les appareils connectés à votre compte.

### Visualiser les sessions
1. Accédez à "Paramètres" > "Compte" > "Sessions"
2. Consultez la liste des sessions actives
3. Vérifiez les informations pour chaque session :
   - Navigateur/Application
   - Adresse IP approximative et localisation
   - Date et heure de la dernière activité

### Gérer les sessions
- Si vous voyez une session que vous ne reconnaissez pas ou qui est suspecte, cliquez sur "Révoquer" à côté de celle-ci pour déconnecter cet appareil
- Il est recommandé de révoquer régulièrement les sessions anciennes ou inactives

## 🔌 Applications autorisées

Contrôlez les applications tierces qui ont accès à votre compte Qlub.

### Gestion des accès
1. Allez dans "Paramètres" > "Compte" > "Applications autorisées"
2. Examinez la liste des applications connectées
3. Pour chaque application, vérifiez :
   - Le nom de l'application
   - Les permissions accordées (par exemple, lire les données, publier en votre nom)
   - La date d'autorisation

### Révoquer l'accès
- Si vous n'utilisez plus une application ou si vous ne lui faites plus confiance, cliquez sur son nom, puis sur "Révoquer l'accès"
- Vérifiez régulièrement cette liste et supprimez les accès inutiles

## 👤 Vérification de votre profil

Qlub utilise un système de vérification décentralisé basé sur les liens croisés pour prouver que vous êtes bien propriétaire des liens dans votre profil.

### Comment vérifier votre profil

1. Accédez à "Paramètres" depuis le menu principal
2. Sélectionnez "Profil" dans la liste des options
3. Dans la section "Métadonnées du profil", ajoutez votre site web personnel avec un lien HTTPS
4. Sur votre site web, ajoutez un lien retour vers votre profil Qlub avec l'attribut `rel="me"`, par exemple :
   ```html
   <a href="https://qlub.social/@username" rel="me">Mon profil Qlub</a>
   ```
   Ou dans l'en-tête de votre page :
   ```html
   <link href="https://qlub.social/@username" rel="me">
   ```
5. Une fois la vérification croisée effectuée, une coche de vérification apparaîtra à côté du lien dans vos métadonnées

## ❌ Supprimer son compte

Si vous souhaitez définitivement quitter Qlub, vous pouvez supprimer votre compte.

**Attention : La suppression est irréversible. Toutes vos données, publications, et informations de profil seront définitivement effacées.**

### Procédure de suppression
1. Accédez à "Paramètres" > "Compte" > "Suppression du compte"
2. Lisez attentivement les avertissements concernant la suppression
3. Confirmez votre mot de passe actuel
4. Cliquez sur le bouton "Supprimer le compte définitivement"

## ➡️ Guide suivant

Découvrez comment gérer vos notifications sur Qlub :
[🔔 Notifications](notifications.md)

---

[🏠 Retour à l'accueil](../index.md)
