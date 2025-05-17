# 📦 Changelog

Traffic Policer 2025 - Version 7.0.0.0
--------------------------------------

🚨 Full Compatibility Update
- Updated for GTA V v1.0.3521.0
- Fully compatible with LSPDFR 0.4.9 and RagePluginHook v0.51+
- Now requires Albo1125.Common.dll v6.6.4.0

🛠️ Plugin Core Updates
- Refactored plugin initialization (Main.cs) for stability and clean logging
- Ensured clean vehicle unlock behavior when plugin unloads
- Integrated version and dependency validation using Albo1125.Common

🔈 Audio & File Checks
- Added integrity check for required audio files (Traffic Policer Audio)
- Ensures files like `OTHER_UNIT_TAKING_CALL_01.wav` and `CRIME_DUI_01.wav` are present
- Conflicting plugins now flagged automatically (e.g., BreathalyzerRAGE, SpeedRadar)

📌 Notes
- This update focuses on modernization, compatibility, and loading stability
- All original gameplay and traffic enforcement features are intact
- Maintained and released by Sparky81x as an unofficial community-supported version

Thanks for supporting the Traffic Policer community revival!

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
