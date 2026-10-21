# yyang.kohii Adoptable Tracker

A lightweight, personal-use tracker for recording adoptable sales and generating receipts.

## Features
- Records adoptable name/number and buyer name or username
- Tracks price, currency, payment status and method, selling type (set price, bidding, offer-based, or flat price), purchase type, and ownership/resale details
- Optional adoptable file name or link
- Multiple proof-of-purchase attachments (images and PDFs, up to 8 MB per file)
- Automatically generated receipt preview, print/save as PDF, and downloadable receipt HTML
- Profile picture upload with square crop and zoom controls
- Clearly labeled light and dark themes with a saved preference
- Small interaction refinements, keyboard-friendly focus styles, Escape/backdrop modal closing, and removable pending attachments
- Search, filters, JSON backup/restore, and CSV export
- About section with feature list and Carrd feedback link
- Device/browser-local storage; no account or server required

## Storage note
Records, settings, profile picture, and proof attachments are stored locally in the browser on the device in use. They do not automatically sync between devices. Clearing browser/site data, resetting or uninstalling the browser, or losing the device may result in data loss. Export a JSON backup regularly. The JSON backup includes attached proof files when available.

## Personal-use notice
Personal use only. Redistribution or commercial use of this tracker is strictly prohibited. If sharing records publicly, do not expose proof of purchase containing private client information.

## Run or publish
Open `index.html` in a modern browser, or upload the files to a GitHub repository and enable GitHub Pages. Keep `index.html` at the repository root for the simplest setup.
