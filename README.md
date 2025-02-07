# IT Asset Management Lab

## Objective:
This project aims to practice IT asset management by creating a simple inventory system for tracking devices (computers, network hardware, peripherals, etc.) using **QR codes** and **barcodes**. The project includes steps for setting up an asset database, generating QR codes for asset tracking, and simulating asset audits.

## Tools & Technologies:
- **Asset Management Tool**: Google Sheets (for simple tracking)
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

3. **Implement Asset Tracking via QR Code**:
   - Attach the QR code to each device.
   
4. **Simulate Asset Audits**:
   - Perform an **inventory audit** by scanning QR codes attached to devices.
   - Check that all assets are accounted for and that the data in the asset database matches the physical devices.

5. **Automating Asset Tracking** (Optional):
   - Write a Python script that automatically generates **QR codes** for new assets and adds them to the inventory database.

## Screenshots:
*Ref 1-2: screen shot of a sample size of 20 for Asset ID,Device Name,Serial Number,Purchase Date,Location,Assigned User,Status. And from there, individually generate QR code for each 20 asset*

![image](https://github.com/user-attachments/assets/65b59260-0000-42d9-b4ed-f916ff1ab67e)

![image](https://github.com/user-attachments/assets/bdd060df-0230-4533-9eff-9b0049c1e03c)

## Challenges Faced:
- Integrating the barcode scanner with the inventory system.
- Ensuring all devices were scanned and status updated correctly.

## Future Enhancements:
- Implement a web interface to update asset statuses.
- Automate inventory reports based on scanning activity.
