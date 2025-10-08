# 🌿 ELEVATE Academic
**Multi-agentní AI mentorský ekosystém pro vzdělávání, výzkum a profesní rozvoj**

> 🚀 **Nová hlavní verze (v2.0)** přináší modulární architekturu založenou na workflows a specializovaných agentech – ELEVATE, STEP, ARIS a DIANA.

---

## ✨ Novinky oproti v1.1.1
- 🟩 **Multi-agentní architektura:** samostatné role s jasnými schopnostmi a workflow.
- 📚 **Znalostní báze + knihovna snippetů:** snadnější údržba.
- 📝 **Session Journal Template:** sjednocený formát zápisů a exportů.
- 🔐 **Vylepšená bezpečnost & governance:** hierarchie autority, ochrana identity, meta-awareness.
- 🤝 **Integrace s CustomGPT / Dify.ai:** čistší onboarding, možnost orchestrací.
- 🧩 **Rozšiřitelnost:** jednodušší přidávání dalších služeb a rituálů.
- 🆙 Kompletně revidovaná dokumentace a Wiki.

---

## 🧠 Architektura a Hlavní Agenti
| Agent | Účel |
|-------|------|
| **ELEVATE** | Hlavní akademická mentorka pro studenty – učení, brainstorming, kritická oponentura, exekuce. |
| **STEP** | AI partnerka pro pedagogy a rodiče – praktická podpora, reflexe a tipy pro praxi. |
| **ARIS** | Výzkumná a rešeršní agentka – hloubková rešerše s citacemi a vícefázovým procesem. |
| **DIANA** | Diagnostická a empatie-mentorship agentka – bezpečný prostor pro sebereflexi či porozumění dítěti. |

> ⚙️ **Poznámka k architektuře:**  
> - ELEVATE 2.0 využívá *workflow-driven multi-persona* přístup.  
> - V prostředí **CustomGPT** běží všechny role nad jedním LLM a agentní chování je dosaženo pomocí striktně oddělených workflow a snippetů – tedy jde o **simulovaný agentní systém**, nikoli o samostatné kontejnery nebo více modelů.  
> - Díky tomu je možné jej nasadit i v hostingu, který nepodporuje nativní orchestraci agentů (CustomGPT, běžné chat-LLM).
> - 🗂 Každý agent má vlastní **workflow manual** a sdílí společnou **knowledge-base** a **snippet knihovnu**.

---

## ⚡ Rychlý Start (Quick Start)
1. Naklonuj repozitář nebo stáhni ZIP.  
2. Pro nasazení do **CustomGPT / jiného LLM-hostingu** použij jako hlavní **system prompt** soubor `elevate.txt`.  
3. Ostatní soubory (`ELEVATE_KB.md`, workflows, snippety) slouží k dokumentaci a údržbě.  
4. Chceš-li plně využít **Session Journal**, nahraj při startu chat-sezení šablonu `SESSION_JOURNAL_TEMPLATE.md`.  
5. Více detailů → [📖 Wiki / Getting Started](https://github.com/painter99/ELEVATE-Academic/wiki).

---

## 📘 Dokumentace & Wiki
- **Overview:** koncepce ekosystému a principy.  
- **Agents & Workflows:** detailní manuály ELEVATE / STEP / ARIS / DIANA.  
- **Session Journal:** struktura a práce s deníkem.  
- **Governance & Safety:** hierarchie autority, meta-awareness, ochrana identity.  
- **Upgrade Guide v1.1.1 → v2.0:** migrační poznámky.  

👉 Vše najdeš ve [📖 Wiki](https://github.com/painter99/ELEVATE-Academic/wiki).

---

## 🔐 Licence
Zůstává kompletně pod [`MIT LICENSE`](./LICENSE.md).  

---

> © 2025 Pavel Mareš (alias painter99) – ELEVATE Academic Framework
