# MF Analytica — NAV Dashboard

**MF Analytica** is a high-performance, client-side web application designed to process Mutual Fund NAV (Net Asset Value) data. It allows users to visualize investment performance, compare multiple funds, and calculate key financial metrics directly in the browser using Excel uploads or API integrations.

## 🚀 Features

* **Excel Data Processing**: Upload and parse NAV Excel files locally using `xlsx.full.min.js`.
* **Interactive Visualizations**: Dynamic charting for fund performance and NAV trends powered by `Chart.js`.
* **Performance Metrics**: Calculate and verify financial indicators like **XIRR**, total returns, and redemption values.
* **Fund Comparison**: Side-by-side analysis of multiple loaded funds with a dedicated "Chart Legend" and multi-select sidebar.
* **Direct API Integration**: Add favorite funds directly via Mutual Fund APIs to fetch real-time or historical data.
* **Data Export**: Generate and download raw NAV data or export processed verification sheets back to Excel format.
* **Responsive Dashboard**: Dark-themed, mobile-responsive UI with a collapsible sidebar and specialized "Snapshot" views for quick performance audits.

## 🛠️ Technical Stack

* **Frontend**: HTML5, CSS3 (using CSS Variables and Flexbox/Grid), and Vanilla JavaScript.
* **Typography**: Syne (Headers) and DM Mono (Data/Metrics).
* **Libraries**:
    * [SheetJS (XLSX)](https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js): For Excel parsing and generation.
    * [Chart.js](https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js): For rendering performance graphs.
    * [Google Fonts](https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Mono:wght@300;400;500&display=swap): For professional financial UI styling.

## 📖 How to Use

1.  **Load Data**: Click **"↑ Load NAV File"** to upload your historical NAV Excel sheet or use the **"+ MF API"** button to search and add funds from the web.
2.  **Select Funds**: Use the left sidebar to toggle visibility for different funds. Each fund is assigned a unique color code for easy identification in charts.
3.  **Analyze**: 
    * **Time Series**: Switch between different time slices (e.g., 1Y, 3Y, 5Y) to see historical trends.
    * **Verification**: Check the "VERIFICATION" section to see tool-computed XIRR vs. manual Excel formula calculations.
4.  **Export**: Use the **"↓ NAV Data"** or **"Export"** buttons to save your processed analysis.

## 📂 File Structure

* `index.html`: The monolithic application file containing the structure, CSS styles (including dark-mode variables), and the JavaScript engine for data processing.

---
*Note: This application operates entirely on the client side. No financial data is uploaded to a server.*
