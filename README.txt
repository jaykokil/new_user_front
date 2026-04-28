SCANNER + DATABASE + WEIGHT PROJECT

Backend API:
VITE_API_URL=https://backend-all-tgww.onrender.com/api

HOW TO RUN:
1. Extract this ZIP
2. Open terminal inside this folder
3. Run:
   npm install
   npm run dev

FLOW:
1. Open in Chrome or Edge
2. Click Connect Devices
3. Select the weighing machine serial port
4. Scan barcode using USB barcode scanner
5. Website fetches bottle data from backend/database
6. Website reads live weight continuously
7. Website locks only one stable weight value
8. Remaining ML is calculated from the locked stable weight

IMPORTANT:
- Bottle barcode must already be added in the Admin Panel/database.
- Weight machine must appear as a serial device.
- Web Serial works only on Chrome/Edge and localhost/HTTPS.
- If you want to take another reading, click Read Weight Again.
