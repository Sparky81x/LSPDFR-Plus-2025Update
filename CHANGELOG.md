# 📦 Changelog

## LSPDFR+ 2025 - Version 1.9.0.3 – 2025-05-17

### 🛠 Fixes
- Fixed crash when switching tabs in the Court System UI
- Resolved empty offence list causing placeholder exceptions
- Improved fallback title logic in court result tabs

### 🧩 Features Restored
- Full menu system (Court, Ticket, Pursuit, etc.)
- F9 hotkey toggle with UI rendering
- Stable `CourtsMenu.Update` handling and tab index resets

### 🔧 Backend Improvements
- Refactored `Menus.cs` with safety checks and logging
- Enhanced traffic stop API and court case creation via `Functions.cs`
- Logging support and integration with `CourtSystem.cs`

### ✅ Compatibility
- Supports GTA V version 1.0.3504.0
- Works with LSPDFR 0.4.9 and RagePluginHook 1.9.3
- Requires Albo1125.Common.dll (bundled)

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
