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

## Data Storage

VERITY uses browser-based IndexedDB for storing election information, voter records, candidates, votes and audit data.

**Note:** The current implementation stores data locally in the browser and does not use a centralized backend server. Data does not automatically synchronize between different devices or browsers.

## Project Objective

To demonstrate how digital technologies can support an accessible, transparent and auditable election-management workflow through a modern web-based application.

---

**VERITY – Transparency. Integrity. Democracy.**
