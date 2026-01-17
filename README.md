# Project-Title-Heritage-Site-Preservation-Project
This Python program evaluates the physical condition of historical monuments using a mathematical decay model. It calculates a decay rate based on age, erosion, and human impact, providing a status report and visiting recommendations to assist in conservation efforts.
📌 Project Overview
The Heritage Site Preservation Project is a Python-based tool designed to assess the physical health of historical monuments. By applying a mathematical decay model, the script calculates a "Decay Rate" based on the age of the site and environmental factors, providing a status report and visitor guidelines.
🧮 The Mathematical Model
The project utilizes a simple linear function to determine the rate of deterioration:
Where:
 * D = Decay Rate
 * A = Age of the monument (in years)
 * E = Natural Erosion Factor (Scale 1–5)
 * H = Human Impact Factor (Scale 1–5)
🚀 Features
 * Decay Calculation: Computes a numerical value representing the cumulative wear on a site.
 * Status Categorization: Uses conditional logic to classify sites into Good, Moderate, or Critical condition.
 * Public Safety/Conservation Advice: Dynamically suggests the best time for tourists to visit based on the site's stability.
💻 How to Use
 * Run the script: Ensure you have Python installed.
 * Input Data: Provide the name, age, and environmental factors when prompted.
 * Read the Report: The script will output a formatted preservation report.
Example Input/Output
| Input Field | Value |
|---|---|
| Monument Name | Taj Mahal |
| Age | 392 |
| Erosion Factor | 0.2 |
| Human Impact | 5.0 |
Resulting Decay Rate: 83.4 (Moderate Condition)
🛠 Future Enhancements (Mathematics Integration)
As you progress in your Mathematics DC course, this model could be enhanced by:
 * Exponential Decay: Using e (Euler's number) to model non-linear degradation over centuries.
 * Statistical Analysis: Integrating data sets of multiple monuments to calculate mean decay rates across regions.
 * Weighted Averages: Assigning higher importance to "Human Impact" versus "Natural Erosion" based on urban density.
