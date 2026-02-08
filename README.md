# WCodeReader v1.0 / v1.1 / v1.2

**WCodeReader** is a fast and reliable Android app to **scan barcodes and QR codes**, manage products, and work with CSV/JSON databases — all directly on your mobile device.

It features a clean **Material Design** interface, works fully **offline**, and supports both **Normal Mode** (simple scanning) and **Advanced Mode** (detailed product tracking with alerts).

---

## Features

### v1.0 (Initial Release)
- Scan **barcodes and QR codes** using the device camera.
- **Create or upload** a product database (CSV/JSON).
- Automatically **load product names** from the database.
- **Manual product addition** if not found.
- **Delete scanned items** individually.
- Color-coded scan list:
  - **Green**: exists in database  
  - **Red**: not in database  
  - **Blue**: manually added
- **Export scanned products** to CSV.
- Toolbar with **Close button**.
- Works **offline**, no internet required.
- Built using **CameraX**, **ML Kit**, and **Material Design**.

---

### v1.1 (Advanced Mode)
- Track **Buying & Selling prices**.
- Record **Manufacture & Expiry dates**.
- **Expiry alerts** for expired and soon-to-expire products.
- Load CSV/JSON databases with **advanced fields**.
- Switch between **Normal Mode** and **Advanced Mode**.
- **Update and sync** database from scanned products.
- Enhanced CSV export including advanced data.

---

### v1.2 (Dual Quantity Tracking & Enhanced Inventory Control)
- **Dual Quantity System**:
  - **Scanned Quantity**: Tracks number of times each item is scanned
  - **Database Quantity**: Imports expected stock from inventory database
  - **Quantity Comparison**: Automatically detects mismatches between scanned and database quantities
- **Enhanced Alert System**:
  - **Stock Level Alerts**: Low stock, critical stock, out-of-stock warnings
  - **Expiry Alerts**: Expired products & expiring soon (3/7 days) notifications
  - **Quantity Mismatch Alerts**: Highlights differences between actual scans and expected inventory
- **Smart Quantity Management**:
  - **Effective Quantity Display**: Shows accurate stock (prioritizes database quantity when available)
  - **Quantity Adjustment**: Edit both scanned and database quantities separately
  - **Mismatch Resolution**: Batch operations to fix quantity discrepancies
- **Improved Database Handling**:
  - **Separate Quantity Columns**: Import/export with dedicated scanned/database quantity fields
  - **Quantity Statistics**: Real-time total quantities and mismatch counts
  - **Enhanced CSV Export**: Includes quantity differences and detailed status information
- **Enhanced User Interface**:
  - **Quantity Breakdown Display**: Shows both quantities side-by-side in list view
  - **Color-Coded Mismatch Indicators**: Purple highlights for quantity discrepancies
  - **Real-time Toolbar Updates**: Shows total items and total quantity
  - **Visual Status Badges**: Improved stock level indicators with emojis
- **Advanced Scanning Features**:
  - **Quantity-aware Scanning**: Increments scanned count with each scan
  - **Smart Database Matching**: Preserves database quantities during scanning
  - **Mismatch Detection**: Real-time comparison during scanning operations

---

## Usage

1. Open the app on your Android device.
2. *(Optional)* Import a CSV or JSON product database.
3. Scan a **barcode or QR code**.
4. If found, product data loads automatically.
5. If not found, add it manually or delete the scan.
6. Enable **Advanced Mode** to:
   - Manage prices, quantities, and dates
   - Receive stock and expiry alerts
   - Track both scanned and database quantities
   - Monitor quantity mismatches
7. Export products or update the database to CSV.
8. Use the toolbar **Close button** to exit.

---

## Screenshots (v1.1)

<p align="center">
  <img src="https://github.com/user-attachments/assets/725fa869-144f-4a8e-b4d5-f43b76b92b89" width="200" />
  <img src="https://github.com/user-attachments/assets/1058870d-9f65-4f50-b258-64119fffb78b" width="200" />
  <img src="https://github.com/user-attachments/assets/259ddc57-e7fe-4f85-b813-a1aa88b6a415" width="200" />
</p>

---

## Screenshots (v1.2)

<p align="center">
  <img src="https://github.com/user-attachments/assets/93b8bddd-ec72-4251-9e62-6ccd90f653c1" width="200" />
  <img src="https://github.com/user-attachments/assets/1b0c70ac-afdc-4531-8159-0d55d306fb7e" width="200" />
  <img src="https://github.com/user-attachments/assets/258c09a1-3bf5-482a-9193-ce95cdc908a0" width="200" />
  <img src="https://github.com/user-attachments/assets/579190e7-fae8-407b-bd73-bf93045f0a4f" width="200" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0baf3ba3-faf8-4cbe-8990-95f06714b409" width="200" />
  <img src="https://github.com/user-attachments/assets/8361cb0d-8b0f-497e-ab21-72ec6a52ea9f" width="200" />
  <img src="https://github.com/user-attachments/assets/36345775-9e41-4a49-90d8-b0bf9e932ada" width="200" />
  <img src="https://github.com/user-attachments/assets/95ada78c-3bec-477a-8a3d-5be2db8e73c7" width="200" />
</p>

---

## Changelog

### v1.2 – 2026-02-08
- **Dual Quantity Tracking System**: Separate tracking for scanned counts vs database inventory
- **Quantity Mismatch Detection**: Automatic alerts for over-scanned/under-scanned items
- **Enhanced Alert System**: Stock level, expiry, and quantity mismatch notifications
- **Smart Quantity Management**: Edit both quantity types separately with batch operations
- **Improved Database Support**: CSV/JSON import with dedicated quantity columns
- **Enhanced UI**: Quantity breakdown display with color-coded mismatch indicators
- **Advanced Scanning**: Quantity-aware scanning with real-time comparison
- **Better Statistics**: Real-time quantity totals and mismatch counts in toolbar

### v1.1 – 2026-02-05
- Advanced Mode introduced
- Buy/Sell prices
- Manufacture & Expiry dates
- Expiry alerts
- Database update & sync
- Mode switching

### v1.0 – Initial Release
- Barcode & QR scanning
- Manual add/delete
- CSV export
- Offline support

---

## Download

[Download latest APK](https://github.com/Owalid-Mez/WCodeReader-Apk/releases)

---

## License

All Rights Reserved © 2026 Walid Ouadfeul  
This repository contains only the **APK** for **WCodeReader**.  
Source code is **not included**.
