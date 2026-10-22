# Yyang Kohii Adoptable Tracker

Offline-first adoptable record tracker for personal use.

## Payment form behavior
- The form begins with adoptable name, buyer, total/target price, currency, payment method, payment status, and contact platform/date.
- **Amount received** appears only when **Partially paid** is selected, and is required for that status unless ownership is Gifted or Traded.
- **Target/payment-plan date** appears and becomes required only for **On hold** or **Partially paid**.
- Gifted and Traded ownership hide the amount-received field entirely.
- Choosing **Resold** reveals and requires the resale price.

## Record editing
- Editing an existing record appends a timestamp to its edit history. The edit history appears on its receipt and is retained with the record.
- Deleted records go to Recently Deleted for 30 days and can be restored before expiry.

## Data and privacy
Records, settings, profile picture, and record metadata are saved in the current browser on this device. Proof attachments are stored in the browser's local IndexedDB. They do not sync to another device or publish online. Export JSON backups regularly, including proof attachments, and keep those backups private.

The visibility-record setting has been removed. Public showcase links and cross-device viewing are not implemented in this offline version.

## How to use
1. Extract this ZIP.
2. Open `index.html` in a modern browser.
3. Enter a record, choose a payment status, and check that only the relevant payment fields appear.
4. Export a JSON backup regularly.

## Important
This is a local record-keeping tool, not a tax invoice or payment processor. Test your workflow with sample records before relying on it for important records.

Permanent creator credit: **Made by yyang.kohii ♡**
