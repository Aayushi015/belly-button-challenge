# Belly button challenge


**📌 Project Overview**

This project is an interactive dashboard that explores the Belly Button Biodiversity dataset, which catalogs the microbes found in human navels. The dataset highlights that a small group of microbial species (operational taxonomic units, OTUs) are commonly found in more than 70% of individuals, while the rest are relatively rare.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**This dashboard enables users to:**

✅ Visualize microbial diversity through interactive charts.

✅ Select individuals using a dropdown menu to update the data dynamically.

✅ View demographic metadata associated with each individual.


**The application is built using:**

- D3.js for data retrieval and interactivity

- Plotly.js for interactive charts

- GitHub Pages for deployment

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**🚀 Features & Functionalities**

**1️⃣ Fetching Data from JSON**

The dataset is retrieved using the D3.js library from:

samples.json.

**2️⃣ 📊Horizontal Bar Chart**

Displays the Top 10 OTUs found in an individual sample.

X-axis: sample_values (OTU abundance).

Y-axis: otu_ids (OTU labels).

Hover Text: otu_labels (bacterial species).

Dynamically updates when a new sample is selected.

**3️⃣ 🌐Bubble Chart**

Shows the full microbial composition in a sample.

X-axis: otu_ids.

Y-axis: sample_values (abundance).

Bubble Size: sample_values.

Bubble Color: otu_ids (color-scaled).

Hover Text: otu_labels.

Dynamically updates when a new sample is selected.

**4️⃣ Metadata Panel**

Displays demographic information (e.g., age, location) for each sample.

Extracts key-value pairs from the metadata JSON and updates dynamically.

**5️⃣ Dropdown Menu for Sample Selection**

Users can select different samples from the dropdown.

The bar chart, bubble chart, and metadata panel update automatically.

**6️⃣ Deployment & Hosting**

The app is deployed using GitHub Pages for easy public access.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
**🛠 Technologies Used**

-JavaScript (ES6)

-D3.js (for data fetching & selection)

-Plotly.js (for interactive charts)

-HTML5 & CSS3

-GitHub Pages (for deployment)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
**📚 References**

D3.js Documentation: https://d3js.org/

Plotly.js Documentation: https://plotly.com/javascript/

Dataset Source: samples.json

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
**📩 Contact**

<<<<<<< HEAD
For any questions or contributions, feel free to reach out via GitHub Issues. 🚀🎨
=======
For any questions or contributions, feel free to reach out via GitHub Issues. 🚀🎨
>>>>>>> ce38175d261a296daa1b949270732b9e417311ee
