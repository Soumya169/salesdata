# Salesdata Insight
# Tableau Dashboard 
# Tableau Profile Link : [Tableau Public](https://public.tableau.com/app/profile/soumya.ranjan.maharana/vizzes)

This project contains HTML code snippets that embed various Tableau dashboards into a web page. It allows users to view interactive Tableau visualizations directly from Tableau Public.

## 📊 Dashboards Embedded

1. **Sales Insight Dataset**
   - Embedded via: `<div id="viz1746332804710">`
   - Dashboard URL: [Tableau Public](https://public.tableau.com/views/G7DPC9GDH)

2. **Sales Dataset Insight (Story View)**
   - Embedded via multiple divs:
     - `viz1746337649939`
     - `viz1746337851043`
     - `viz1746338000712`
   - Dashboard URL: [Tableau Public](https://public.tableau.com/views/SalesDataInsight_17388622420110/Story1)

## 🛠️ How It Works

Each embedded visualization uses Tableau's JavaScript API to load and render the dashboard within a specific `<div>` container. Key components:
- `<div class='tableauPlaceholder'>`: Placeholder for embedding.
- `<object class='tableauViz'>`: Contains embed parameters.
- `viz_v1.js`: Tableau's official JS library for rendering.

## 🧩 Usage Instructions

1. Open the HTML file in a browser.
2. Dashboards are automatically loaded based on the `<script>` provided for each.
3. Adjust `width` and `height` in the script for responsive design if necessary.

## 📦 File Structure

- `index.html` – HTML file containing embedded Tableau dashboards.
- `README.md` – Project explanation and usage guide.

## 📎 Notes

- Make sure you have an active internet connection, as Tableau loads assets from its public CDN.
- You can replace the URLs to use your own Tableau Public dashboards.
- All dashboards are read-only for viewers unless editing permissions are provided on Tableau.

## ✍️ Author

Created for Tableau visualization integration demonstration by Soumya Ranjan Maharana.
