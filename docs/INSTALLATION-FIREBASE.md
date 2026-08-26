# Activation des comptes SPN

La page `compte.html` est prête à être reliée à un projet Firebase.

1. Dans [Firebase Console](https://console.firebase.google.com/), crée un projet, ajoute une application Web, puis active **Authentication > E-mail/mot de passe** et crée une base **Firestore Database** en mode production.
2. Copie la configuration Web Firebase dans `firebase/firebase-config.js` (les six champs). Ces valeurs sont destinées à être présentes dans le site Web.
3. Dans Firestore, publie les règles de `firebase/firebase-rules.txt`. Après avoir créé ton premier compte, ouvre `users`, sélectionne le document portant son UID et ajoute le champ `role` avec la valeur `admin`. Ce compte verra alors l’espace de gestion des cups.

Ensuite, publie l’intégralité du dossier `SPN-Esport-propre` sur ton hébergement.
