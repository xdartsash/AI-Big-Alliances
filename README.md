<div align="center">

# AI BIG ALLIANCES

**Smarter alliances. Better diplomacy. Smoother gameplay.**

A game AI modification that brings more strategic alliance decisions and performance improvements.

[![Version 2.4](https://img.shields.io/badge/Version-2.4-2563EB?style=for-the-badge)](https://github.com/xdartsash/AI-Big-Alliances/releases/tag/aibigalliances2.4)
[![Download](https://img.shields.io/badge/Download-mod.zip-16A34A?style=for-the-badge)](https://github.com/xdartsash/AI-Big-Alliances/releases/download/aibigalliances2.4/mod.zip)
[![Downloads](https://img.shields.io/github/downloads/xdartsash/AI-Big-Alliances/aibigalliances2.4/total?style=for-the-badge&color=64748B)](https://github.com/xdartsash/AI-Big-Alliances/releases/tag/aibigalliances2.4)

[Features](#features) · [Download](#download) · [Editions](#editions) · [Installation](#installation) · [Русский](#русский)

</div>

---

## Overview

AI Big Alliances focuses on strategic diplomacy and alliance behavior. Instead of choosing partners based only on national strength, the improved AI considers the wider diplomatic and geographic situation.

Version 2.4 also introduces map loading and turn-processing optimizations, plus configurable AI behavior for individual campaigns.

## Features

The following features are documented in the existing [2.4 release notes](https://github.com/xdartsash/AI-Big-Alliances/releases/tag/aibigalliances2.4).

### Strategic alliance AI

- **Intelligent partner selection** — evaluates shared threats, proximity, diplomatic relations and usefulness to the alliance.
- **Alliance compatibility** — considers existing members and the risk of becoming involved in unrelated wars.
- **Multiple invitations** — up to three per selection cycle by default, subject to available candidates, slots and diplomatic points.
- **Optional smart invitations** — switch back to the previous invitation logic through the pre-game settings.

### Performance improvements

- Faster loading of large maps, particularly on HDDs.
- Reusable map file cache that reduces repeated small-file reads.
- Reduced end-of-turn microstutters through distributed map-data updates.
- Adjusted background turn-processing priorities.
- Optional performance diagnostics.

### Campaign settings

| Setting | Available options |
| :--- | :--- |
| Smart alliance invitations | On / Off |
| AI support | On / Off |
| Support frequency | Normal / Frequent |

Settings are stored separately for each campaign. Older saves without the new settings use the current pre-game defaults. Support frequency is remembered even when AI support is disabled.

## Download

| Release | File | Published |
| :--- | :--- | :--- |
| **AI Big Alliances 2.4** | [mod.zip](https://github.com/xdartsash/AI-Big-Alliances/releases/download/aibigalliances2.4/mod.zip) · 52.2 MB | October 14, 2026 |

[**Release notes and downloads →**](https://github.com/xdartsash/AI-Big-Alliances/releases/tag/aibigalliances2.4)

## Editions

| | Workshop Lite | Full |
| :--- | :--- | :--- |
| Modification method | gameValues only | Modified game.jar |
| Full-version AI improvements | Not included | Included |
| Full-version engine optimizations | Not included | Included |
| Game JAR modification | Not required | Required |

> The improvements described above require the Full version with a modified game.jar. They are not included in the gameValues-only Workshop Lite version.

## Installation

1. Check the release page and confirm compatibility with your game version.
2. Back up your original game files and campaign saves.
3. Download the archive from the release page.
4. Extract the archive and inspect its contents before applying the mod.

Exact destination paths and supported base-game versions are not documented here. Do not overwrite files until you have confirmed the correct installation procedure.

## Community & development

[![Issues](https://img.shields.io/github/issues/xdartsash/AI-Big-Alliances?style=flat-square)](https://github.com/xdartsash/AI-Big-Alliances/issues)
[![Stars](https://img.shields.io/github/stars/xdartsash/AI-Big-Alliances?style=flat-square)](https://github.com/xdartsash/AI-Big-Alliances/stargazers)

- [Report a bug or suggest a feature](https://github.com/xdartsash/AI-Big-Alliances/issues/new/choose)
- [Development roadmap](docs/ROADMAP.md)
- [Contributing guide](CONTRIBUTING.md)
- [All releases](https://github.com/xdartsash/AI-Big-Alliances/releases)

This repository contains project documentation; release builds are distributed separately. The roadmap describes proposals, not guaranteed upcoming features.

---

## Русский

**AI Big Alliances** — модификация игрового ИИ, ориентированная на более продуманные союзы, дипломатию и оптимизацию производительности.

### Что нового в 2.4

- Умный выбор союзников с учётом общих угроз, расстояния, отношений и пользы для альянса.
- До трёх приглашений в союз за один цикл по умолчанию.
- Ускоренная загрузка больших карт и кэширование файлов.
- Уменьшение микрофризов в конце хода.
- Настройки умных приглашений, поддержки ИИ и частоты поддержки.
- Индивидуальные настройки кампаний и совместимость старых сохранений с новыми параметрами.

**Full** требует изменённый game.jar. **Workshop Lite** использует только gameValues и не содержит перечисленных Full-улучшений.

[**Скачать AI Big Alliances 2.4 (mod.zip)**](https://github.com/xdartsash/AI-Big-Alliances/releases/download/aibigalliances2.4/mod.zip) · [Список изменений](https://github.com/xdartsash/AI-Big-Alliances/releases/tag/aibigalliances2.4)

Перед установкой сделай резервную копию оригинальных файлов игры и сохранений.

---

<div align="center">

Developed by [xdartsash](https://github.com/xdartsash)

If you enjoy the project, consider giving it a ⭐.

</div>

No project-wide license has been declared. Original game files remain subject to their respective rights and terms.
