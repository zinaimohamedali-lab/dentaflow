# DentaFlow v1.2.0 — Licence par pack de postes 🖥️🖥️🖥️

**Un seul code pour tout le cabinet. 3 postes inclus.**

Vous achetez **un seul code d'activation**, que vous posez sur le PC principal. Les autres postes du cabinet s'activent **tout seuls**, sans code.

---

## 💰 Tarif

| | |
|---|---|
| **Essai gratuit** | **3 jours**, toutes fonctions débloquées |
| **Licence Cabinet** | **12 000 DA à vie** — **3 postes inclus** (Gérant, Assistante, Praticien) |
| **Poste supplémentaire** | **+3 000 DA** par poste, à vie |

> Paiement unique. Pas d'abonnement. Vos données restent chez vous.

---

## 🖥️ Comment ça marche

**Sur le PC principal (le « pilote ») :**
1. Activez-le avec votre code d'activation.
2. **⚙ Paramètres → Dossier de données** : choisissez un dossier et **partagez-le** sur le réseau.

**Sur chaque autre poste :**
1. Installez DentaFlow.
2. Fenêtre d'activation → **« Ce poste rejoint un cabinet déjà équipé »** → **📁 Parcourir** → sélectionnez le dossier partagé → **🔗 Rejoindre le cabinet**.
3. Terminé. Le poste s'active seul et partage les mêmes données (patients, agenda, caisse…).

> ℹ️ **Le PC pilote doit rester allumé.** S'il est éteint, les autres postes fonctionnent encore **72 heures** (week-end, panne, redémarrage), puis se bloquent jusqu'à son retour.

---

## 🆕 Nouveautés de cette version

- **Nombre de postes inscrit dans le code d'activation** — votre licence sait combien de postes elle couvre.
- **Gestion des sièges** — chaque poste occupe un siège sur le réseau ; un siège inutilisé pendant 72 h est **automatiquement libéré** (poste remplacé, PC changé : rien à faire).
- **Messages clairs** — si un poste ne peut pas rejoindre le cabinet, DentaFlow explique précisément pourquoi (pilote éteint, hors réseau, postes épuisés…).
- **Licences existantes conservées** — les codes émis précédemment continuent de fonctionner et couvrent 3 postes.

---

## 🔐 Sécurité

- Le pilote publie un **battement de cœur signé** (ECDSA P-256) ; sa clé privée est **chiffrée par son empreinte matérielle** et ne quitte jamais le poste.
- Un poste secondaire n'accepte de s'activer que si **tout** est vérifié : code portant la **signature de l'éditeur**, identité du pilote **cohérente avec le matériel encodé dans le code**, signature du battement **valide**, battement **frais** (≤ 72 h), pilote sur une **adresse IP privée**, et **siège disponible** dans le pack.
- **Anti-recul d'horloge** sur les postes secondaires.
- Copier le dossier partagé vers un autre cabinet ne donne au mieux que **72 h**, puis tout s'arrête.

---

## 🖥️ Installation

1. Téléchargez **`DentaFlow-Setup.exe`** ci-dessous.
2. Double-cliquez et suivez l'assistant (2 minutes, aucun droit administrateur requis).
3. Lancez DentaFlow → **essai de 3 jours** automatique.

**Configuration :** Windows 10 / 11 (64 bits) · ~56 Mo · .NET inclus.

> ℹ️ Windows SmartScreen peut afficher un avertissement au premier lancement (éditeur non encore reconnu par une autorité mondiale). Cliquez sur **« Informations complémentaires » → « Exécuter quand même »**. Le fichier est signé au nom de **DentaFlow DZ**.

---

## 📞 Nous contacter

**📱 WhatsApp / Téléphone : [+213 676 53 88 03](https://wa.me/213676538803)**

---

*DentaFlow — Algérie · © 2026 · Tous droits réservés.*
