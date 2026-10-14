# DMS Enhancer

A lightweight, feature-rich browser extension designed to streamline document processing, previewing, and dark theme customization on the **DILG Document Management System (DMS)** (`https://dms.dilg.gov.ph/`).

Developed by **[lstvelasco](https://luisitovelasco.netlify.app/)**

---

## 🚀 Features

* 🌙 **Full Site-Wide Dark Mode:** Custom-tailored dark theme for all pages across the DMS portal (Dashboard, Incoming, Received, Pending, Reports, User Profile Settings, etc.).
* ⚡ **Automated Bulk Actions:**
  * **Incoming Documents:** Select multiple items and perform **Bulk Accept** in one click.
  * **Received & Pending Documents:** Execute **Bulk Route Internal (Beta)** (mass route to Divisions, Sections, or Action Officers) or **Bulk Complete**.
  * **Completed Documents:** Perform **Bulk Mark as Incomplete** to revert documents.
* 👁️ **Instant PDF Previews:**
  * **Table Quick Previews:** View attached PDF documents directly in a floating pop-up modal without leaving the current list view.
  * **Document Details View:** Instant modal PDF inspection replacing redundant browser tab creation.
* 🛡️ **Safe Batch Processing:** Limits processing to 15 items per execution batch to ensure server reliability and smooth routing.
* 🎛️ **Toolbar Popup & In-Page Bar:** Toggle extension features or Dark Mode anytime directly from your browser's extension toolbar.

---

## 📌 Pin the Extension for Quick Access

To quickly switch Dark Mode or toggle features while using DMS:

1. Click the **Extensions icon (🧩 Puzzle piece)** on the top-right toolbar of Microsoft Edge or Google Chrome.
2. Locate **DMS Enhancer**.
3. Click the **Pin icon (📌)** (or eye icon) to keep it permanently visible on your browser header.

---

## 🛠️ How to Install in Your Browser

### Option A: Install via Microsoft Edge Add-ons Store
1. Open **Microsoft Edge**.
2. Search for **DMS Enhancer** on the **Microsoft Edge Add-ons Store**.
3. Click **Get** to install automatically.

### Option B: Manual Installation (Developer / Unpacked Mode)
1. **Download the Release:**
   * Download the latest `dms-enhancer.zip` release from the [Releases Page](https://github.com/lstvelasco/dms-bulk-complete-release).
2. **Extract the Archive:**
   * Unzip the downloaded file to a local folder (e.g., inside `Documents`).
3. **Open Browser Extension Settings:**
   * **Microsoft Edge:** Open `edge://extensions/`
   * **Google Chrome:** Open `chrome://extensions/`
4. **Enable Developer Mode:**
   * Toggle on **Developer mode** (left sidebar in Edge, or top-right toggle in Chrome).
5. **Load Unpacked Extension:**
   * Click **Load unpacked** and select the extracted extension folder containing `manifest.json`.
6. **Ready to Use:**
   * Navigate to `https://dms.dilg.gov.ph/` and enjoy automated workflows!

---

## 🔒 Usage Note & Disclaimer

This extension is developed for authorized internal productivity enhancement. Users remain strictly responsible for verifying that all processed documents comply with office routing policies, proper recipient assignments, and internal procedures.