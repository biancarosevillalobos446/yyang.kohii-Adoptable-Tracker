# yyang.kohii Adoptable Tracker

A lightweight adoptable record tracker with payment tracking and generated receipts.

## Features
- Adoptable name/number and buyer details
- Total or target price, currency, payment status, payment method, selling type, purchase type, and ownership/resale details
- `On hold` records with a required target payment date
- `Partially paid` records with a required amount-paid field and payment-plan date
- Amount-paid input disabled for `On hold`, `Traded`, and `Gifted` ownership states
- Color-coded payment status labels beside adoptable names
- Optional adoptable file name or link
- Multiple proof-of-purchase attachments (images and PDFs, up to 8 MB per file)
- Generated receipt preview, print/save as PDF, and downloadable receipt HTML
- Profile picture upload with zoom and movable crop controls, plus a remove option
- Soft twinkle sound on profile-picture taps and other optional interaction sounds
- Recently Deleted recovery area for records deleted within the last 30 days
- Light/dark themes, search, filters, JSON backup/restore, and CSV export
- Permanent `Made by yyang.kohii ♡` credit
- Device/browser-local storage; no account or server required

## Storage and sharing
Records, settings, profile picture, and proof attachments are stored locally in the browser on the device in use. They do not automatically sync between devices. Clearing browser/site data, resetting or uninstalling the browser, or losing the device may result in data loss. Export a JSON backup regularly. The JSON backup includes attached proof files when available.

Cross-device viewer links, individual six-digit sharing IDs, and a public showcase are not connected in this offline version. The proof-viewing setting is a saved preference only; it does not upload or expose proof files.

## Use and creator credit
You may use the tracker for your own adoptable records and display your own work. Please keep private client information and proof of purchase private unless you have permission to share it. Do not remove the permanent creator credit or present the tracker as your own product.

## Run or publish
Open `index.html` in a modern browser, or upload the files to a web host. Local data is browser-specific even when the same tracker page is hosted online.
