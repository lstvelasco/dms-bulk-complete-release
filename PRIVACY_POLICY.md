# Privacy Policy for DMS Enhancer

**Effective Date:** October 16, 2026  
**Last Updated:** October 16, 2026  

**DMS Enhancer** ("we", "our", or "extension") is committed to protecting user privacy and maintaining complete transparency. This Privacy Policy outlines our data handling practices, permission usage, and security commitments regarding the DMS Enhancer browser extension.

---

## 1. Zero Personal Data Collection

DMS Enhancer operates **100% client-side** directly within your web browser.

- **No Data Collection:** We do **NOT** collect, track, log, store, or transmit any personal information, government credentials, employee details, document logs, or browsing history.
- **No Telemetry or Tracking:** The extension contains no analytics trackers, advertising scripts, or third-party telemetry framework.
- **Direct Local Operations:** All actions—such as document status updates, batch routing requests, and PDF modal previews—are executed directly between your browser and the official DILG Document Management System (`https://dms.dilg.gov.ph/`).

---

## 2. Browser Permissions & Justifications

The extension requests only the absolute minimum permissions required for its core functionality:

- **`activeTab`**: Used strictly to interact with the active DILG DMS tab to inject in-page action toolbars, status indicators, and modal overlays.
- **`storage`**: Used exclusively to save local UI state and user preferences (e.g., Dark Mode status, feature toggles) on your device via `chrome.storage.local`. Stored preference data never leaves your device.
- **Host Permission (`https://dms.dilg.gov.ph/*`)**: Restricted strictly to the official DILG DMS portal to apply custom Dark Mode styling, inject bulk action controls, process authenticated document routing requests, and render attached PDF previews.

---

## 3. Remote Code & External Connections

- **No Remote Code Execution:** DMS Enhancer strictly complies with Manifest V3 security guidelines. It does not execute remote JavaScript, fetch dynamic code from CDNs, or use `eval()`. All code is static, open-source, and bundled inside the extension package.
- **No External Backend:** The extension does not communicate with any external servers, databases, or third-party web services.

---

## 4. Third-Party Links

Optional links embedded within the extension UI or documentation (such as developer portfolio links, GitHub repositories, or Buy Me a Coffee support links) open directly in your default browser tab and are governed by their respective external privacy policies.

---

## 5. Administrative Responsibility & Compliance

DMS Enhancer is an open-source productivity enhancement tool created for authorized internal users of the DILG Document Management System. Users remain fully responsible for ensuring that all bulk document actions and routing processes executed through the tool comply with official administrative regulations and office guidelines.

---

## 6. Changes to This Policy

We may update this Privacy Policy from time to time to maintain alignment with browser store policies or functional updates. Updates will be posted directly to this document within the public GitHub repository.

---

## 7. Contact & Support

If you have questions, feedback, or security concerns regarding DMS Enhancer, you may reach out via:

- **Developer:** Luisito B. Velasco Jr.
- **Portfolio:** [https://luisitovelasco.netlify.app/](https://luisitovelasco.netlify.app/)
- **GitHub Repository:** [https://github.com/lstvelasco/dms-bulk-complete-release](https://github.com/lstvelasco/dms-bulk-complete-release)