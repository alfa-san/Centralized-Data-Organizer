# 📊 Centralized Data Organizer v0.1.0

Centralized Data Organizer is a macro-enabled Excel tool designed to help users manage dynamic categories and records with ease. Built entirely in VBA, this application provides a user-friendly interface for creating, updating, and organizing structured data—all within Excel.

## 🚀 Features

### 🔧 Category Management
- Add up to 12 custom categories (e.g., Email, City, Phone Number)
- Delete unused or outdated categories
### 📝 Record Entry
- Add new records using a responsive form
- Fields adjust automatically to match current categories
### 🔍 Record Update Tools
- **Search**: Filter records by category and keyword
- **Replace**: Modify field values only when changes are detected
- **Delete**: Remove selected records from both the table and preview list
### 🎯 UX Enhancements
- Prompts for missing data with placeholder guidance
- Auto-clear placeholder text when typing begins

## 📦 File Contents

- `Centralized-Data-Organizer_v0.1.0.xlsm` – Main Excel macro-enabled file
- `README.md` – Project documentation
- `CHANGELOG.md` – Version history and feature log

## 📜 Version History

This project now follows [Semantic Versioning](https://semver.org/).  
See [`CHANGELOG.md`](CHANGELOG.md) for detailed updates.

Current version: `v0.1.0`

## 🧾 Release Notes – v0.1.0

- Modularized ListBox_Refresh logic
- Bug fixes for category index refresh and search pop-up
- Improved record preview logic
- Updated onboarding instructions in README

## 🛠 Requirements

- Microsoft Excel 365 (with macro support enabled)
- VBA enabled (developed using the Microsoft 365 VBA environment)
- No external dependencies

## 📚 Usage

1. **Unblock the file**:  
   After downloading the `.xlsm` file from the internet, right-click the file, select **Properties**, and under the **General** tab, check the **Unblock** box. Click **OK** to apply.

2. **Enable macros**:  
   Open the `.xlsm` file in Microsoft Excel and enable macros when prompted to allow the VBA code to run.

3. **Navigate the Main Form**:  
   Use the built-in interface to access the following modules:
   - **Category Management**: Add or delete up to 12 custom categories.
   - **Record Management**: Add new records, search existing entries, replace values, or delete records.

4. **Exit safely**:  
   Use the **Quit** button to close the form and return to the workbook.



## 👨‍💻 Author

**James A. Sanchez**  
GitHub: [@alfa-san](https://github.com/alfa-san)  
Date Created: October 1, 2025

---

## 📬 Feedback & Contributions

Feel free to fork, improve, or suggest enhancements via GitHub Issues or Pull Requests. This project is designed to be modular and extendable.

