# DentaFlow v1.3.4

Cette version rassemble tout le travail depuis la v1.2.3. Elle est **recommandée à tous** : elle corrige des blocages au démarrage, rend le kiosque patient réellement utilisable et fait passer tous les documents imprimés au format A5.

---

## 🆕 Nouveautés

### Prise de rendez-vous depuis la fiche patient
La fiche affiche désormais le **prochain rendez-vous** en haut, avec un bouton **📅 Planifier**. Quand vous acceptez une demande venue du kiosque, la fenêtre de planification s'ouvre dans la foulée : plus de patient créé sans date.

### Rendez-vous anciens
Vous pouvez saisir un rendez-vous **daté dans le passé** (rattrapage d'un cahier papier, journée oubliée). Le journal d'activité conserve la **date de frappe réelle**, marquée « saisie rétroactive ».

### Tableau de bord cliquable
Chaque carte ouvre l'écran correspondant, et chaque ligne de rendez-vous ouvre la **fiche du patient**. La navigation respecte les permissions de chaque compte.

### Statistiques par praticien (Gérant)
Chiffre d'affaires, patients vus, rendez-vous, honorés, absents, taux d'absence et actes réalisés sur 6 mois, praticien par praticien.

### Devis
- Acte **« Autre »** : libellé et prix libres, pour tout ce qui n'est pas au catalogue.
- **Validité** saisie devis par devis, imprimée avec sa date d'échéance.

### Journal d'activité exportable
Bouton **⬇ Exporter** dans Paramètres : la totalité du journal dans un fichier lisible par Excel.

---

## 🖨️ Documents imprimés

- **Tout passe en A5** (148 × 210 mm) : devis, ordonnances, certificats, feuilles de soins, fiches patient. Deux fois moins de papier, un format qui tient dans la main du patient.
- **Papeterie du cabinet** : votre logo devient un filigrane transparent en fond de page, et l'en-tête présente le logo encadré d'un filet or avec le nom du cabinet.

---

## 📱 Kiosque patient (QR)

Le QR code de l'onglet « Demandes » **fonctionne enfin**. Il était auparavant lié à un service jamais livré avec l'installateur.

- Le logiciel héberge lui-même le formulaire : le patient scanne, remplit sur son téléphone, la demande arrive dans « Demandes ».
- L'adresse annoncée évite désormais les cartes VPN et machines virtuelles, qui rendaient le QR injoignable.
- Un bouton **« Autoriser le pare-feu »** règle le blocage Windows en un clic.

> Le téléphone doit être sur le Wi-Fi du cabinet.

---

## 🔒 Suppressions et traçabilité

- Le **Gérant** supprime directement rendez-vous et ordonnances ; il peut accorder ce droit aux autres, dont les demandes passent alors par **son approbation**.
- Chaque suppression, approbation et refus est consigné, avec l'auteur et la description de l'élément effacé.
- Les statuts **Labo** (envoyé / reçu / posé) et **Devis** (accepté / refusé / en attente) sont **réversibles** sans autorisation : seule la suppression en demande une.

---

## 🩺 Odontogramme

Silhouettes dentaires anatomiques à la numérotation FDI, **vue de face et vue occlusale** synchronisées : changer l'état d'une dent la met à jour dans les deux vues.

---

## 🖥️ Postes et licence

- **Premier lancement** : vous choisissez si le poste est le **pilote** (code d'activation ou essai 3 jours) ou un **poste secondaire**, qui cherche alors le pilote sur le réseau.
- **Nouveau poste** : il demande un accès, le Gérant lui attribue rôle, identifiant et code PIN réutilisables à chaque connexion.
- Les autres postes trouvent le pilote **automatiquement** sur le réseau local.

---

## 🛠️ Corrections importantes

- **Le logiciel ne s'ouvrait pas après la saisie du code PIN** — corrigé. C'était le défaut le plus grave de la version précédente.
- Les boutons **+ Acte**, **+ Ordonnance**, **+ Ajouter un modèle** et **Sortie de stock** refermaient le panneau en cours — corrigé.
- Icône d'application absente dans l'Explorateur et la barre des tâches — corrigée.
- Barre de navigation de l'agenda illisible (texte blanc sur fond clair) — corrigée.
- Fenêtres Stock et Paramètres : boutons tronqués, fenêtres non redimensionnables — corrigées.
- Champs de saisie sans indication : chaque champ affiche maintenant un exemple.
- **Mise à jour sans perte de données** : un nouveau champ s'ajoute désormais à votre base existante sans la recréer.

---

## 💰 Tarif

| | |
|---|---|
| **Essai gratuit** | **3 jours**, toutes fonctions |
| **Licence Cabinet** | **12 000 DA à vie** — 3 postes inclus |
| **Poste supplémentaire** | **+3 000 DA** à vie |

---

## 📥 Installation

Téléchargez **`DentaFlow-Setup.exe`** ci-dessous, double-cliquez, suivez l'assistant. Aucun droit administrateur requis.

Windows 10 / 11 (64 bits) · ~60 Mo · .NET inclus.

> Au premier lancement, Windows SmartScreen peut afficher un avertissement : **« Informations complémentaires » → « Exécuter quand même »**. Le fichier est signé au nom de **DentaFlow DZ**.

---

**📱 WhatsApp : [+213 676 53 88 03](https://wa.me/213676538803)**
