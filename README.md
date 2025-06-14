# 🏆 FC 25 - ICÔNES Injection Pack (Live Editor) | Dual Language (FR/EN)

> 🔗 Basé sur le travail original de [xAranaktu - FC 25 Live Editor](https://github.com/xAranaktu/FC-25-Live-Editor)

![FIFA FC25 ICONS](https://img.shields.io/badge/LiveEditor-Compatible-green?style=flat-square)  ![Status](https://img.shields.io/badge/Ready_For_Use-FC25-blue?style=flat-square) [![Latest Release](https://img.shields.io/github/v/release/ITRecords38/fc25-icons-injection?label=Latest%20Release)](https://github.com/ITRecords38/fc25-icons-injection/releases/latest)

> Créez / Inject automatically all ICON players into FC25 using **Live Editor**.

---

## ✨ Fonctionnalités | Features

* Injection automatique de tous les joueurs ICÔNES (Base, TOTY, FUT Birthday, etc.)
  Auto injection of all ICON players (Base, TOTY, FUT Birthday, etc.)
* Scripts classés par **version/révision**
  Scripts sorted by **version/revision**
* Statistiques et styles de jeu complètement renseignés
  Full stats and playstyles populated
* Test préalable de la présence avec `PlayerExists()`
  Checks player existence using `PlayerExists()`
* Aucun remplacement automatique, pas de conflit
  No overwriting, no conflict with existing players

---

## 📁 Structure

```
scripts/
└ icons/
  ├─ main.lua
  ├─ README_ICONS_FC25.txt
  └─ icons_lua_playerexists_by_version/
      ├─ Base/
      ├─ TOTY/
      ├─ FUT_Birthday/
      └─ ...
```

---

## 📆 Installation

1. Extraire ce dépôt dans le dossier :
   Extract this repo into:

   ```
   FIFA Live Editor/scripts/icons/
   ```

2. Lancer Live Editor et exécuter :
   Launch Live Editor and run:

   ```lua
   dofile("scripts/icons/main.lua")
   ```

3. Les joueurs ICÔNES seront ajoutés automatiquement.
   All ICON players will be injected with logs confirming status.

---

## 🌐 Sources des données | Data Sources

* Données issues des fichiers extraits de FC25 (squadfiles)
  Data from FC25 squadfiles
* Nationalités, stats et styles via `players.txt` enrichi
  Nationality, stats, styles via enriched `players.txt`

---

## ✍️ Auteur | Author

Projet construit par **Fabrice** 💻
Built by **Fabrice** 💻
Pour toute suggestion, ouvrez une issue ou PR.
Feel free to open issues or PRs.

---

## 🎨 Aperçu (optionnel) | Preview (optional)

![preview](https://imgur.com/k5SRKnQ.png)

---

## 🔗 Licence | License

Ce pack est fourni à des fins non commerciales. Tous les droits relatifs à FC25 appartiennent à EA SPORTS.
This pack is for non-commercial use only. All rights to FC25 belong to EA SPORTS.
