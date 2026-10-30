# VERITY – Tamil Nadu Legislative Assembly Election 2026

A digital election management and voting platform designed for the Tamil Nadu Legislative Assembly Election 2026. Built using HTML, CSS and JavaScript, with a focus on secure voter workflows, transparent election management, and verifiable voting records.

## Project Overview

VERITY is a web-based election portal that provides separate interfaces for voters and administrators. It supports voter registration, digital ballot casting, constituency-wise candidate management, election monitoring, public results, and an auditable vote ledger.

## Main Modules

- **Voter Portal** – Voter registration, identity verification and voter dashboard.
- **Digital Voting** – Interactive ballot with candidate selection and NOTA support.
- **Admin Dashboard** – Manage elections, candidates, political parties and voter records.
- **Constituency Management** – Constituency-wise candidate management and election monitoring across Tamil Nadu.
- **Election Results** – Live vote monitoring, constituency-wise results, party standings and result publication.
- **Verifiable Vote Ledger** – Hash-chained voting records with public ledger verification.
- **Audit Management** – Track administrator activities and important election operations.
- **Digital Voter Slip** – Generate and download digital voting receipts as PDF.
- **Data Backup & Recovery** – Separate voter, administrator and complete database backup and restoration.

## Key Features

- Separate voter and administrator portals
- OTP-based voter verification
- Administrator two-factor authentication (TOTP)
- Constituency-scoped returning officer accounts
- One-vote-per-registered-voter workflow
- Candidate and political party management
- Anonymous vote ledger and verification
- Live election statistics and analytics
- Tamil and English language support
- Dark mode, larger text and high-contrast accessibility options
- QR code and PDF-related utilities
- Backup restoration for recovering previously saved election data

## Technologies Used

- HTML5
- CSS3
- JavaScript
- IndexedDB
- Web Crypto API
- QR Code JavaScript Library
- jsPDF
- html2canvas

## How to Run

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Open the `Verity — Tamil Nadu Legislative Assembly Election.html` file.
4. Run the application using the Live Server extension.
5. Open the generated localhost URL in your browser.

## First-Time Administrator Login & Setup

When opening VERITY for the first time, follow these steps:

1. Open the application.
2. Select the **Administrator Portal**.
3. Enter the default bootstrap password:

   **Default Password:** `admin123`

4. After successful login, the application displays a password-change option.
5. Enter a new password of your choice and complete the password change.
6. After changing the password, you can access the Administrator Dashboard.

**Important:** The default password is intended only for initial setup. Change it immediately and do not share it.

**Returning Officer Access:** For the normal administrator workflow described here, use the Administrator Portal and its administrator password. You do not need to enter the Returning Officer area.

## Backup Restoration – Important

If the application opens but previously saved voter, candidate, election or other records do not appear, restore the provided backup file.

**Backup file name:**

`verity-full-backup-2026-10-09-07-24-00 (1)`

Follow these steps:

1. Open the **Administrator Portal**.
2. Log in using the administrator password.
3. If this is an empty administrator setup, use the default bootstrap password `admin123` and change it when prompted.
4. Open the **Data Backup & Recovery** section.
5. Select the backup restoration option.
6. Choose the provided file `verity-full-backup-2026-10-09-07-24-00 (1)`.
7. Complete the restoration process.
8. Check that the previously saved election data is visible in the application.
9. Log out of the Administrator Portal.

**Note:** Restore the backup only when the required data is missing. Make sure you select the correct backup file before starting restoration. Follow the application's confirmation prompts carefully.

## Voter Login & Voting Process

After the administrator has completed the initial setup and restored the required data, voters can use the Voter Portal.

1. First, ensure that the required election data is available.
2. Log out of the Administrator Portal.
3. Open the **Voter Portal**.
4. Complete the voter login and identity-verification process.
5. Access the digital ballot.
6. Select the preferred candidate or NOTA.
7. Follow the on-screen instructions to complete the voting process.
8. The application will process the vote according to its one-vote-per-registered-voter workflow.

**Recommended order:** Administrator Login → Password Change (if required) → Backup Restoration (if data is missing) → Verify Data → Administrator Logout → Voter Portal Login → Cast Vote.

## Data Storage

VERITY uses browser-based IndexedDB for storing election information, voter records, candidates, votes and audit data.

**Important:** The current implementation stores data locally in the browser and does not use a centralized backend server. Data does not automatically synchronize between different devices or browsers.

If the required data is missing, use the supplied backup file and the restoration procedure described above.

## Project Objective

To demonstrate how digital technologies can support an accessible, transparent and auditable election-management workflow through a modern web-based application.

---

**VERITY – Transparency. Integrity. Democracy.**
