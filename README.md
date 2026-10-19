# NexusOrion
*NexusOrion** est un navigateur web léger et rapide pour Linux, construit avec **GTK3** et **WebKitGTK**.  Il fait partie de l'écosystème **Nexus**, conçu pour offrir une alternative indépendante aux navigateurs basés sur Chromium.  ### Pourquoi NexusOrion ?  - **Indépendant** de Chromium et Google - **Léger** : construit en C, sans Electron -
# 🌐 NexusOrion

> Navigateur web indépendant basé sur WebKitGTK — construit par Aissa Mohammedi.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Linux%20Mint-green.svg)
![Language](https://img.shields.io/badge/language-C-orange.svg)

---

## 📖 Qu'est-ce que NexusOrion ?

**NexusOrion** est un navigateur web léger et rapide pour Linux, construit avec **GTK3** et **WebKitGTK**.

Il fait partie de l'écosystème **Nexus**, conçu pour offrir une alternative indépendante aux navigateurs basés sur Chromium.

### Pourquoi NexusOrion ?

- **Indépendant** de Chromium et Google
- **Léger** : construit en C, sans Electron
- **Rapide** : démarrage instantané
- **Open source** : code lisible, pas de bloat
- **Simple** : barre d'adresse, navigation, c'est tout

---

## 🚀 Installation

### Prérequis

- Linux Mint 21+ (ou Ubuntu 22.04+)
- GTK3
- WebKitGTK 4.1 (ou 4.0)

### Installation rapide

```bash
git clone https://github.com/aissa-mohammedi/nexusorion.git
cd nexusorion
chmod +x install.sh
./install.sh

Installation manuelle
sudo apt update
sudo apt install -y build-essential pkg-config libgtk-3-dev libwebkit2gtk-4.1-dev
gcc src/nexus_browser.c -o nexus_browser $(pkg-config --cflags --libs gtk+-3.0 webkit2gtk-4.1)
./nexus_browser


🎮 Utilisation
Action Raccourci
Charger une URL Entrée dans la barre d'adresse
Retour Bouton ←
Avancer Bouton →
Rafraîchir Bouton ↻



📸 Captures d'écran

docs/screenshot.png

🛠️ Compilation

Build script
cd build
./build.sh

Build manuel
gcc src/nexus_browser.c -o nexus_browser \
$(pkg-config --cflags --libs gtk+-3.0 webkit2gtk-4.1)


🗺️ Roadmap
[x] Barre d'adresse fonctionnelle
[x] Boutons Retour / Avancer / Rafraîchir
[x] Vue WebKit complète
[ ] Gestion des onglets
[ ] Marque-pages
[ ] Historique
[ ] Mode navigation privée
[ ] Support des extensions
[ ] Thème sombre
[ ] Version Windows

📜 Licence

MIT License — voir LICENSE.

👤 Auteur

Aissa Mohammedi
• Écosystème : Nexus
• Protocole : Code Nametron 3 Lara
• GitHub : @aissa-mohammedi

🙏 Remerciements
• L'équipe WebKitGTK
• La communauté GTK
• Tous les contributeurs open source

NexusOrion — Le navigateur qui ne dépend de personne.
