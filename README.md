# 🌐 Furnality — Site Officiel

Auteur : **DarkofTime**

Dev : **Z-Kirby90**

> © 2018 Furnality — All rights reserved. Redistribution prohibited.
> <br> © 2025 Office BroadCaster (OBC) — owned by Furnality. All rights reserved. Redistribution prohibited.
> <br> © 2026 Furnality Zapping — owned by Furnality. All rights reserved. Redistribution prohibited.
> <br> © 2026 Furnality news — owned by Furnality. All rights reserved. Redistribution prohibited.
> <br> Any reproduction, distribution, or commercial use without written permission from DarkeofTime is strictly prohibited.

---

## 📁 Architecture du Projet

Le projet utilise une structure monorepo centralisée où chaque sous-dossier correspond à une sous-page ou à un module spécifique du réseau :

```text
furnality/
├── css/
│   └── global.css            # Styles partagés (importé ou synchronisé)
├── js/
│   └── global.js             # Script global (API Worker + Lucide + Menus)
├── Zapping/
│   └── index.html            # Rediffusions & Extraits (furnality.pages.dev/Zapping)
├── news/
│   └── index.html            # Actualités du Studio (furnality.pages.dev/news)
├── index.html                # Page d'accueil principale (furnality.pages.dev)
└── README.md
