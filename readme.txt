# CardsManager

CardsManager is a Windows desktop application designed to automate and simplify the management of Pokémon TCG screenshots, trades, and account XML files.  
It provides structured workflow for organizing screenshots, locating account files, and configuring paths through a dedicated Settings tab.

---

## ✨ Features


## 📂 Founded Accounts Tab
Search and extract XML account files based on screenshot names.

**Capabilities:**
- Enter 1–10 screenshot names.
- Auto‑generated textboxes based on selected amount.
- Validates input before processing.
- Searches the Saved Folder for matching XML files.
- Copies found XML files into the *Founded Accounts* output folder.
- Includes:
  - **Find XML and Copy**
  - **Open Founded Folder**
  - **Clear Founded Folder**

---

## 🖼️ Organized Screenshots Tab
Organize screenshots using CSV trade data.

**Capabilities:**
- Reads the Trades CSV file.
- Matches screenshot names with CSV entries.
- Organizes screenshots into structured folders.
- Includes:
  - **Organize Screenshots**
  - **Open Organized Folder**
  - **Clear Organized Folder**

---

## ⚙️ Settings Tab
Configure all folder paths used by the application.

### Editable fields:
- **Trades CSV Path**
- **Trades Folder**
- **Screenshots Folder**
- **Output Founded Accounts**
- **Output Organized Screenshots**
- **Saved Folder**


## 📁 Required Setup

Before using CardsManager, you **must** configure your folder paths in the **Settings** tab.

### Update the following fields:

#### 1. Trades CSV Path
Path to your `Trades_Database.csv`.

#### 2. Trades Folder
Folder containing all trade-related files.

#### 3. Screenshots Folder
Folder where your Pokémon TCG screenshots are stored.

#### 4. Output Founded Accounts
Folder where XML files will be copied.

#### 5. Output Organized Screenshots
Folder where organized screenshots will be saved.

#### 6. Saved Folder
Folder containing your saved XML account files.

---

## 🛠️ Installation

1. Clone or download the repository.
2. Ensure the `Assets` folder is placed next to the executable.
3.RUN EXE

---

## 📦 Technologies Used
- **C# WinForms**
- **.NET**
- **Newtonsoft.Json**
- **Custom UI styling**
- **Splash screen with embedded assets**



