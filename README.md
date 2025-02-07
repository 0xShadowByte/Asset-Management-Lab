# IT Asset Management Lab

## Objective:
This project aims to practice IT asset management by creating a simple inventory system for tracking devices (computers, network hardware, peripherals, etc.) using **QR codes** and **barcodes**. The project includes steps for setting up an asset database, generating QR codes for asset tracking, and simulating asset audits.

## Tools & Technologies:
- **Asset Management Tool**: Google Sheets (for simple tracking) / Snipe-IT (open-source solution)
- **Programming Language**: Python
- **QR Code Generator**: Online tool for generating QR codes
- **Barcode Scanner**: Mobile app or physical barcode scanner for tracking
- **Operating System**: Windows / Linux (Kali Linux)

## Steps to Set Up:
1. **Create Asset Database**:
   - Use a Google Sheets template to create an asset database with the following columns:
     - Asset ID
     - Device Name
     - Serial Number
     - Purchase Date
     - Location (Physical/Department)
     - Assigned User
     - Status (In-use, in-repair, retired)

2. **Generate QR Codes for Assets**:
   - For each device in your inventory, generate a QR code linked to the **Asset ID**.
   - Example: A laptop with **Asset ID: 001** will have a QR code linked to that ID.
   - You can generate these using [QR Code Generator](https://www.qr-code-generator.com/).

3. **Implement Asset Tracking via QR Code**:
   - Attach the QR code to each device.
   - Use a barcode scanner app (e.g., **QR Code Reader**) to scan the QR code and update the status in your asset management system.
   
4. **Simulate Asset Audits**:
   - Perform an **inventory audit** by scanning QR codes attached to devices.
   - Check that all assets are accounted for and that the data in the asset database matches the physical devices.

5. **Automating Asset Tracking** (Optional):
   - Write a Python script that automatically generates **QR codes** for new assets and adds them to the inventory database.

