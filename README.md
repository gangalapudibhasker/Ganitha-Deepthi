# 🏫 Ganitha Deepthi 2026–27 Books Distribution & Audit Management System

A client-side single-page dashboard application built to manage and audit the distribution of *Ganitha Deepthi* mathematics books across 28 districts for the 2026–27 academic year.

## 🚀 Key Features

*   **Role-Based Access Control:** Secure portals customized for Final Admin, District Admins, and Distributors.
*   **Live Dashboard Analytics:** Monitor total books indented, completed shipments, pending dispatch status, and real-time activity tracking.
*   **District Wise Summary:** Filter, search, and review detailed book counts, receipts, payments, and entries.
*   **Secure Password Changes:** Users can update their passwords directly from the settings page, which are persisted locally.
*   **Audit Logging:** Automatic recording of updates, additions, and deletions for security verification.
*   **Data Portability:** Download school distribution lists in CSV format for local spreadsheet management.

---

## 🔑 Login Portals & Default Credentials

### 1. Final Admin (System Administrator)
*   **Username:** `admin`
*   **Password:** `APMF-FINAL-2026`
*   *Permissions:* Full system control, reset databases, and view all passwords.

### 2. District Admins (28 Districts)
*   **Username:** `apmf_<district_abbreviation>` (e.g., `apmf_asr` for Alluri Sitharama Raju)
*   **Password:** `APMF@<abbreviation>2026` (e.g., `APMF@ASR2026`)
*   *Permissions:* Add local distribution records, upload receipts, and log payments.

### 3. Books Distributor
*   **Username:** `apmf_distributor`
*   **Password:** `APMF@DIST2026`
*   *Permissions:* Confirm dispatches and book receipts across all districts.

---

## 🛠️ Offline Deployment & Local Run

Since the application is built entirely as a single-page HTML application (`index.html`) using local database storage, you can run and use it instantly without any server setup:

1.  Clone or download this repository.
2.  Double-click `index.html` to open it in any web browser (Chrome, Edge, Firefox, or Safari).
3.  All entered data will remain saved on your device's browser local storage.

---

## 🔒 Security & Data Persistence

*   **Database:** Powered by browser `localStorage`.
*   **Backups:** To prevent data loss when clearing browser cache, utilize the **Download Reception Centers** button in the dashboard to save your offline records.
