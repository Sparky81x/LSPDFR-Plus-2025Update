# 📦 Changelog

## [8.0.2] – 2025-05-19

### 🧾 Menu Rework & Behavioral Alignment

- Reverted the on-foot menu to match the original intent of LSPDFR+ by Albo1125
- Removed “Ask for ID” from the Shift + Q menu
  - Players should now use LSPDFR’s built-in E menu for ID checks and interactions
- On-foot menu now handles **only citation and summons actions**
- Cleaned up ped interaction logic to prevent conflicts with LSPDFR’s PedStop system

### 🔧 Stability & Compatibility

- Improved ped behavior after issuing citations on foot
- Ensured menu actions no longer interfere with LSPDFR-controlled NPCs

---

✅ Fully compatible with:
- LSPDFR 0.4.9
- Traffic Policer 2025
- Arrest Manager 2025
- PoliceSmartRadio 2025

## [8.0.1] – 2025-05-18

### 🆕 Improvements
🆕 You can now ask for ID during on-foot stops via the LSPDFR+ ticket menu (Shift + Q).
This allows you to avoid using the default E menu, which can overlap with LSPDFR+ menus.

Use E once to stop the ped

Then switch to Shift + Q for all ticketing and interaction via LSPDFR+

### 🧠 Behavior Enhancements
- ID check on foot now displays the ped’s name via an in-game notification, consistent with vehicle stops

### 🔧 Stability
- Fixed a null reference crash caused by incorrect AskForID menu binding
- Verified controller and keyboard compatibility

✅ This is a non-breaking patch update. Now using **semantic versioning**

LSPDFR+ 2025 Update - Version 1.9.0.3 2025-05-17
-------------------------------------

🔧 General Compatibility
- Updated for GTA V version 1.0.3521.0
- Verified compatibility with LSPDFR 0.4.9 and RagePluginHook >= 0.51
- Requires Albo1125.Common.dll v6.6.4.0 (included)

🛠 Fixes & Stability
- Resolved crash issues when switching tabs in the Court System menu
- Improved fallback handling for missing or placeholder court entries
- Fixed offence category logic to avoid null list crashes

🧩 Restored Features
- Full court, ticket, and pursuit menus operational again
- CourtsMenu tab switching, case population, and placeholder UI fallback restored
- F9 hotkey and CourtsMenu UI refresh now fully functional and crash-resistant

🧪 Backend Improvements
- Improved logging and dependency validation in Main.cs and Functions.cs
- Full dependency check integration with Albo1125.Common
- Cleaned up redundant update logic and stabilized mod initialization

Thank you to the LSPDFR community for your continued support!
This update is maintained by Sparky81x as an unofficial restoration and enhancement.

## [1.9.0.2] – 2025-04-30

### Added
- ✅ Shift+Q ticket menu now supports Court Summons
- ✅ Delayed court case creation after animation (1–7 min realism)
- ✅ Court Summons popup appears after processing
- ✅ Unified experience with E menu (traffic stop)
- ✅ Fully compatible with Albo1125's original plugins

### Fixed
- 🛠 Summons no longer bypass animation or cause duplicate cases
- 🛠 Ticket stat tracking and menu behavior preserved

### Notes
- 🔓 Source code released under GNU-GPLv3 per original license
- 🧠 Prepared for future Arrest ➝ Court integration

## [2025-04-27] - First Public Release

### ✨ New Features

- **Dynamic Verdict Generation:**  
  Court Summons now result in real Guilty or Not Guilty verdicts after the scheduled hearing time passes.

- **Realistic Fine Calculations:**  
  Minor traffic offences dynamically generate fine amounts based on ticketed offences.

- **Dynamic Jail Sentences:**  
  Major felony offences (Drug Trafficking, Assaulting an Officer, Attempted Murder) now trigger randomized jail sentences between 2–10 years.

- **Expanded Offences List:**  
  Added serious felony crimes to the American.xml database to fully support realism in Court outcomes.

- **Background Court Processing:**  
  Court paperwork now happens seamlessly in the background after stops without freezing player gameplay.

- **Popup Notifications:**  
  Players are notified automatically of finalized court case verdicts — including fines or jail time.

- **Full API Compatibility:**  
  No breaking changes to the original LSPDFR+ or Albo1125.Common API.  
  Backward-compatible with all dependent mods and savegames.

---

### 🛠 Improvements

- Cleaned up CourtCase logic to properly handle Pending and Published verdicts.
- Fixed infinite "Pending Verdict" cases that were stuck in older LSPDFR+ versions.
- Smarter GuiltyChance logic randomized at verdict time.
- Improved player experience with smoother UI notifications and verdict progression.

---

### 🔥 Planned Future Enhancements

- Potential integration of player monetary fine deductions.
- Expanded serious crime tracking for deeper penalties (license suspensions, probation outcomes).
- Future optional API hooks for mod developers to extend court behaviors dynamically.

---

## 📜 Credits

- Original Development: **Albo1125**  
- 2025 Court System Overhaul and Modernization: **Sparky**

---

# 📣 Protect and Serve — now with real consequences. 🚓
