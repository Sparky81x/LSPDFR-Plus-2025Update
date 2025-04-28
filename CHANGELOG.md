# Changelog - LSPDFR+ 2025 Court System Realism Update

---

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
