# 📄 CHANGELOG.md

All notable changes to this project will be documented in this file.  
This project follows [Semantic Versioning](https://semver.org/).

---

## [v0.1.0] – 2025-10-01
### Added
- Initial development release
- Main form interface with modular navigation:
  - Category management: Add/Delete up to 12 dynamic fields
  - Record entry form with dynamic field support (1 to 12 fields)
- Record update tools:
  - Search by category and keyword
  - Replace values only when changes are detected
  - Delete selected records from table and preview
- Dynamic ListBox refresh
- Smart prompts for missing data and placeholder guidance
- README documentation included

### Fixed
- Category index not refreshing after deletion; modularized `ListBox_Refresh` and invoked it post-deletion.
- Erroneous Missing Data pop-ups during consecutive searches; added `Refresh_lst_RecordPreview` call before search execution to clear blank rows.
