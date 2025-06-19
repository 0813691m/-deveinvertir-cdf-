# 📱 Deveinvestir CDF

Une application mobile et plateforme web créée pour le développement numérique et l’investissement participatif en RDC.

## ✨ Fonctionnalités
- Connexion avec Firebase Auth
- Gestion des utilisateurs (agents/admin)
- Intégration Firebase App Check
- Tableau de bord sécurisé
- API REST (Java/Retrofit)
- Publication dynamique des projets

## 🔗 Technologies
- Java (Android) / Firebase
- Firestore / AppCheck / Hosting
- GitHub / Render / Play Store

## 🛠️ Instructions pour clonerDeveinvestir-cdf/
│
├── app/                      # Code source (Android ou WebApp)
│   ├── src/
│   │   ├── main/             # Fichiers principaux
│   │   │   ├── java/com/deveinvestircdf/
│   │   │   │   └── MainActivity.java (ou index.js si web)
│   │   │   └── res/          # Layouts, assets
│   ├── build.gradle
│   └── proguard-rules.pro
│
├── firebase/                 # Configuration Firebase
│   ├── firebase.json
│   ├── firestore.rules
│   ├── .firebaserc
│   └── hosting/
│       └── index.html        # Pour Firebase Hosting
│
├── public/                   # Pour site web (si tu as React/HTML)
│   └── index.html
│
├── README.md                 # Présentation du projet
├── .gitignore
└── LICENSE
