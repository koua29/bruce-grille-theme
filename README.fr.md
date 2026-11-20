# ⬛ Grille — Bruce Theme

<p align="center">🇺🇸 <a href="README.md">English</a> · 🇫🇷 <b>Français</b></p>

[![Bruce firmware](https://img.shields.io/badge/firmware-Bruce-8A2BE2?logo=github)](https://github.com/BruceDevices/firmware) [![Device](https://img.shields.io/badge/device-LilyGO%20T--Embed%20CC1101-1E90FF)](https://github.com/BruceDevices/firmware) [![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

Un thème UI **grille** minimaliste et propre pour le firmware **[Bruce](https://github.com/BruceDevices/firmware)** sur LilyGO T-Embed CC1101 (320×170). Tous les menus affichés d'un coup en **grille 4×4** d'icônes Material pro ; le menu courant est mis en avant — inversé dans un rond plein. Variantes claire et sombre incluses.

![Grille — light & dark](docs/hero.png)

## 🎨 Deux variantes

| Variante | Pictos | Sélection |
|---|---|---|
| **`Grille`** | noir sur blanc | picto **blanc dans un rond noir** |
| **`Grille_Dark`** | blanc sur noir | picto **noir dans un rond blanc** |

| Light | Dark |
|---|---|
| ![light](docs/light.png) | ![dark](docs/dark.png) |

## ✨ Détails

- 🔲 **Grille 4×4** = les 16 entrées du menu visibles en permanence.
- 🎯 Menu courant **surligné** (inversé dans un rond plein) — pas de texte, ultra lisible.
- 🧩 Icônes **[Material Icons](https://github.com/google/material-design-icons)** de Google (style pro) : WiFi, Bluetooth, RF, NRF, LoRa, FM, IR, Ethernet, GPS, RFID, Files, Scripts, Clock, Others, Config, Connect.

## 📦 Contenu

Chaque variante : **4 tailles** × **16 PNG** + `.json`.

| Dossier | Image | Écran cible |
|---|---|---|
| `105px/` | 240×105 | M5StickC Plus (240×135) |
| `140px/` | 320×140 | **T-Embed CC1101 / Cardputer (320×170)** |
| `180px/` | 320×180 | écrans ~320×210 |
| `192px/` | 320×192 | écrans ~320×222 |

> ℹ️ **Barre d'état** — Bruce réserve **30 px en haut**. Taille = hauteur écran − 30 → **T-Embed CC1101 = `140px`**.

## 🚀 Installation

1. Copie **`Grille`** et/ou **`Grille_Dark`** à la racine de la carte SD.
2. Sur l'appareil : **Config → UI Theme → `Grille/140px/Theme_Grille.json`** (ou `Grille_Dark/140px/Theme_Grille_Dark.json`).
3. Via WiFi : **Files → WebUI**, upload le dossier, puis sélectionne le `.json`.

## 🛒 Matériel

*Liens partenaires Amazon : si vous achetez via ces liens, le projet touche une petite commission, sans surcoût pour vous.*

<table>
<tr>
<td align="center" width="33%">
  <a href="https://www.amazon.fr/dp/B0D45MSMJR?linkCode=ll2&amp;tag=koua29bgrilletheme-21&amp;ref_=as_li_ss_tl"><img src="docs/amazon-B0D45MSMJR.jpg" width="200" alt="Batterie Anker 545 (10 000 mAh)"></a><br>
  <b><a href="https://www.amazon.fr/dp/B0D45MSMJR?linkCode=ll2&amp;tag=koua29bgrilletheme-21&amp;ref_=as_li_ss_tl">Batterie Anker 545 (10 000 mAh)</a></b><br><sub>Pour faire tourner le T-Embed loin d'une prise</sub>
</td>
<td align="center" width="33%">
  <a href="https://www.amazon.fr/dp/B0C1FCZM94?linkCode=ll2&amp;tag=koua29bgrilletheme-21&amp;ref_=as_li_ss_tl"><img src="docs/amazon-B0C1FCZM94.jpg" width="200" alt="Antenne SMA 433 MHz (lot de 2)"></a><br>
  <b><a href="https://www.amazon.fr/dp/B0C1FCZM94?linkCode=ll2&amp;tag=koua29bgrilletheme-21&amp;ref_=as_li_ss_tl">Antenne SMA 433 MHz (lot de 2)</a></b><br><sub>Antenne sub-GHz pour la radio CC1101</sub>
</td>
<td align="center" width="33%">
  <a href="https://www.amazon.fr/dp/B0B7NVMBPL?linkCode=ll2&amp;tag=koua29bgrilletheme-21&amp;ref_=as_li_ss_tl"><img src="docs/amazon-B0B7NVMBPL.jpg" width="200" alt="microSD SanDisk 64 Go (lot de 2)"></a><br>
  <b><a href="https://www.amazon.fr/dp/B0B7NVMBPL?linkCode=ll2&amp;tag=koua29bgrilletheme-21&amp;ref_=as_li_ss_tl">microSD SanDisk 64 Go (lot de 2)</a></b><br><sub>Pour les thèmes, scripts et captures Bruce</sub>
</td>
</tr>
</table>

<sub>En tant que Partenaire Amazon, je réalise un bénéfice sur les achats remplissant les conditions requises.</sub>

## 🎨 Crédits

- Thème par **koua29**. Icônes : **[Material Icons](https://github.com/google/material-design-icons)** de Google — licence **Apache 2.0**.
- Tourne sur l'excellent **[Bruce firmware](https://github.com/BruceDevices/firmware)**.

## ☕ Un café ?

<img src="docs/paypal-qr.png" width="180" alt="PayPal" />

## 📄 Licence

Assets du dépôt sous **MIT** (voir [LICENSE](LICENSE)). Icônes Material sous **Apache 2.0**.
