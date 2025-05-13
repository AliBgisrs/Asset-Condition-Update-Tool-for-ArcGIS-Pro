# Asset-Condition-Update-Tool-for-ArcGIS-Pro


This ArcGIS Pro Python Toolbox automates the integration of inspection data with spatial asset layers and generates a summary of asset conditions for infrastructure management. Designed for use by GIS professionals in public works, utilities, and smart city planning.

## 📌 Features

- 🔄 Join inspection data with asset feature layers using a common field (e.g., `AssetID`)
- 🛠 Update asset condition fields based on the most recent inspection
- 📊 Generate a summary table of condition categories for reporting and planning
- 📍 Compatible with point, line, or polygon asset layers
- 🧩 Designed for integration in enterprise asset management workflows


### ✅ Requirements

- ArcGIS Pro 2.8 or later
- Python 3.x (bundled with ArcGIS)
- ArcPy library (automatically included with ArcGIS Pro)

### 🔧 Usage

1. Open **ArcGIS Pro** and load your project.
2. Right-click **Toolboxes** → Add Toolbox → Navigate to the tool
3. Double-click the tool and provide:
   - Asset feature layer (with `AssetID`)
   - Inspection table (with `AssetID` and `Condition` fields)
   - Output location for updated features and summary table
4. Run the tool.

---

## 📈 Example Use Case

You're managing water hydrants across a city. Inspectors submit inspection data with hydrant IDs and condition scores. This tool will:
- Join the inspection results to the hydrants layer
- Update the `Condition` field in the hydrants dataset
- Provide a report of how many hydrants fall into each condition class

---

## 🧠 Technical Overview

- Joins based on a user-defined key field (e.g., `AssetID`)
- Supports numeric or categorical condition fields
- Outputs include:
  - Updated feature class
  - Optional condition frequency summary (as a table)

---

## 📜 License

MIT License © 2025 Aliasghar bazrafkan

---

## 👤 Author

**Aliasghar Bazrafkan**  
PhD in Precision Agriculture, Remote Sensing, and GIS  
📍 Fargo, ND | 🌐  
✉️ aliasghar.bazrafkan@ndsu.edu
