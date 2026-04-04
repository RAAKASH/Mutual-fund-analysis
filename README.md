# MF Analytica — NAV Dashboard

**MF Analytica** is a high-performance, client-side web application designed to process Mutual Fund NAV (Net Asset Value) data. It allows users to visualize investment performance, compare multiple funds, and calculate key financial metrics directly in the browser using Excel uploads or API integrations.

## 🚀 Features

* **NAV excel file processsing**: Upload and parse NAV Excel files locally.
* **Performance Metrics**: Calculate and verify financial indicators like **XIRR**, total returns, and redemption values.
* **Direct API Integration**: Add favorite funds directly via Mutual Fund APIs to fetch real-time or historical data.
* **Mutual Fund Data Export**: Generate and download raw NAV data or export processed verification sheets back to Excel format.
* **Portfolio projection**:Load your existing portfolio, project expected portfolio values based on historic performance.

## 📖 How to Use

1.  **Load Data**: Click **"↑ Load NAV File"** to upload your historical NAV Excel sheet or use the **"+ MF API"** button to search and add funds from the web.
2.  **Select Funds**: Use the left sidebar to toggle visibility for different funds. Each fund is assigned a unique color code for easy identification in charts.
3.  **Analyze**: 
    * **Time Series**: Switch between different time slices (e.g., 1Y, 3Y, 5Y) to see historical trends.
    * **Verification**: Check the "VERIFICATION" section to see tool-computed XIRR vs. manual Excel formula calculations.
4.  **Export**: Use the **"↓ NAV Data"** or **"Export"** buttons to save your processed analysis.

---
*Note: This application operates entirely on the client side. No financial data is uploaded to a server.*
