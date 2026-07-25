# DentaFlow v1.1.0 — Licence de cabinet 🖥️🖥️🖥️

**Une seule licence. Tous les postes de votre cabinet.**

Jusqu'ici, chaque poste demandait son propre code d'activation. Désormais, vous achetez **un seul code** et **tous les autres postes du cabinet s'activent automatiquement**, sans code, sans surcoût.

---

## 💰 Nouveau tarif

| | |
|---|---|
| **Essai gratuit** | **3 jours**, toutes fonctions débloquées |
| **Licence Cabinet** | **9 000 DA / cabinet, à vie** — **postes illimités** sur votre réseau local |

---

## 🖥️ Comment ça marche

**Sur le PC principal (le « pilote ») :**
1. Activez-le avec votre code d'activation.
2. **⚙ Paramètres → Dossier de données** : choisissez un dossier et **partagez-le** sur le réseau.

**Sur chaque autre poste :**
1. Installez DentaFlow.
2. Dans la fenêtre d'activation → **« Ce poste rejoint un cabinet déjà équipé »** → **📁 Parcourir** → sélectionnez le dossier partagé → **🔗 Rejoindre le cabinet**.
3. Terminé. Le poste s'active seul et partage les mêmes données (patients, agenda, caisse…).

> ℹ️ **Le PC pilote doit rester allumé.** S'il est éteint, les autres postes continuent de fonctionner **72 heures** (week-end, panne, redémarrage), puis se bloquent jusqu'à son retour.

---

## 🔐 Sécurité

La licence de cabinet est protégée par plusieurs verrous cumulés :

- Le pilote publie un **battement de cœur signé** (ECDSA P-256) dans le dossier partagé ; sa clé privée est **chiffrée par son empreinte matérielle** et ne quitte jamais le poste.
- Un poste secondaire n'accepte de s'activer que si **tout** est vérifié : code portant la **signature de l'éditeur**, identité du pilote **cohérente avec le matériel encodé dans le code**, signature du battement **valide**, battement **frais** (≤ 72 h), et pilote sur une **adresse IP privée** (vrai réseau local, pas Internet).
- **Anti-recul d'horloge** sur les postes secondaires.
- Copier le dossier partagé vers un autre cabinet ne donne donc au mieux que **72 h**, puis tout s'arrête.

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
