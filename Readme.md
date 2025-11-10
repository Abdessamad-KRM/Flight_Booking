# Flight Booking app

![Static Badge](https://img.shields.io/badge/Langage-Kotlin-blueviolet?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Platform-Android-green?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/UI-XML_Layouts-blue?style=for-the-badge)

Un projet de concept d'interface utilisateur (UI) pour une application Android de réservation de billets d'avion.

Ce projet démontre une interface utilisateur réactive (responsive) qui s'adapte à différentes tailles d'écran (téléphones, tablettes) et à différentes orientations (portrait, paysage).

## 📖 Table des matières

* [📱 Aperçus](#-aperçus)
* [✨ Fonctionnalités](#-fonctionnalités)
* [🛠️ Technologies et Outils](#️-technologies-et-outils)
* [🚀 Lancer le projet](#-lancer-le-projet)
* [📜 Licence](#-licence)

---

## 📱 Aperçus

L'application gère les configurations portrait et paysage pour les téléphones et les tablettes, en utilisant des layouts et des ressources distincts.

<table>
  <tr>
    <td align="center"><b>Téléphone (Portrait)</b></td>
    <td align="center"><b>Téléphone (Paysage)</b></td>
  </tr>
  <tr>
    <td><img src="./screenshots/phone_portrait.png" alt="Phone Portrait" width="250"></td>
    <td><img src="./screenshots/phone_landscape.png" alt="Phone Landscape" width="450"></td>
  </tr>
  <tr>
    <td align="center"><b>Tablette (Portrait)</b></td>
    <td align="center"><b>Tablette (Paysage)</b></td>
  </tr>
  <tr>
    <td><img src="./screenshots/tablet_portrait.png" alt="Tablet Portrait" width="300"></td>
    <td><img src="./screenshots/tablet_landscape.png" alt="Tablet Landscape" width="500"></td>
  </tr>
</table>

---

## ✨ Fonctionnalités

* **Interface Réactive :** Les layouts s'adaptent automatiquement aux écrans de téléphone et de tablette.
* **Gestion de l'orientation :** Des vues optimisées pour les modes portrait et paysage.
* **Ressources visuelles :** Inclut des icônes personnalisées (avion, ticket, personne) et des logos de compagnies aériennes (Emirates, IndiGo, SpiceJet, Vistara).
* **Structure de projet propre :** Organisation claire des ressources `drawable` et `layout`.

---

## 🛠️ Technologies et Outils

* **Langage :** Kotlin
* **UI :** Android XML Layouts
* **Build :** Gradle (avec Kotlin DSL `.kts`)