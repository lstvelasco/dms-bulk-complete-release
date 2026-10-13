# DMS Bulk Actions (Accept & Complete)

A Lightweight Chrome / Microsoft Edge Extension designed to automate repetitive document management tasks on the DILG Document Management System (DMS).

Developed by **[lstvelasco](https://luisitovelasco.netlify.app/)**

---

## 🚀 Features

- **Multi-Page Automation:**
  - **Incoming Documents Page:** Batch selection and 1-click **Bulk Accept** for incoming items.
  - **Pending Documents Page:** Batch selection and 1-click **Bulk Complete** for received items awaiting action.
- **Batch Selection Limit:** Supports up to 15 items per run to prevent server rate-limiting.
- **Server Friendly:** Throttled sequential background requests (400ms delay) with active CSRF token validation.
- **Dynamic Versioning:** Displays active version badge and developer credits directly inside the injected toolbar.

---

## 🛠️ How to Install in Your Browser

1. **Get the Extension Folder:**
   - Extract the received `dms-bulk-helper.zip` file to a permanent folder on your PC (e.g., inside `Documents` or `C:\Extensions`).
2. **Open Extension Management in Browser:**
   - **Google Chrome:** Go to `chrome://extensions/`
   - **Microsoft Edge:** Go to `edge://extensions/`
3. **Enable Developer Mode:**
   - Toggle on **Developer mode** (top-right switch in Chrome, or left sidebar toggle in Edge).
4. **Load the Extension:**
   - Click the **Load unpacked** button.
   - Select the extracted `dms-bulk-helper` folder.
5. **Start Using:**
   - Open **Incoming Documents** to perform Bulk Accept.
   - Open **Pending Documents** to perform Bulk Complete.

---

## 🔒 Security & Policy Note

This extension is intended solely for authorized internal productivity enhancement. Users remain responsible for ensuring that all processed documents have been reviewed and acted upon according to office routing guidelines.