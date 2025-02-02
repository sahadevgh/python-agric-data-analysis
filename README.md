# Agricultural Data Analysis System

## Assignment Details
**Institution:** Ghana Communication Technology University (GCTU)  
**Faculty:** Faculty of Computing and Information Systems (FoCIS)  
**Department:** Computer Science (CS)  
**Program:** MSc/MPhil Computer Science  
**Course:** CSSD 601 - Advanced Computation and Programming Using Python  
**Assessment:** Application of Python Programming Assessment  

## Features
- Perform irrigation analysis based on soil moisture levels.
- Generate a summary of soil moisture distribution.
- Analyze rainfall impact on soil moisture.
- Visualize soil moisture trends over time.

## Installation
Clone this repository in a Jupyter Notebook terminal:
```bash
git clone https://github.com/sahadevgh/agriculture-data-analysis.git
```

## Usage
1. Use the available dataset for testing (e.g., `soil_moisture_data.csv`), or place your own dataset in the project folder.
   - The dataset should contain columns for `Date`, `Soil Moisture (%)`, and `Rainfall (mm)`.
2. Run the Jupyter Notebook file:
   ```bash
   jupyter notebook agriculture-data-analysis.ipynb
   ```
3. View the output, including:
   - Irrigation recommendations based on soil moisture thresholds.
   - Statistical summaries of soil moisture and rainfall data.
   - Visualizations of soil moisture trends and rainfall impact on irrigation decisions.

## Results
- **Irrigation Recommendations:** Classified as *Irrigation Required* or *No Irrigation Needed*.
- **Soil Moisture Distribution:** Visualized as a histogram.
- **Rainfall Impact Analysis:** Analyzed through scatter plots.
- **Trends Over Time:** Displayed using time-series graphs.

## Example Output
```plaintext
Irrigation Recommendations:
---------------------------
Date         | Soil Moisture (%) | Recommendation
------------------------------------------------
2025-01-01   | 25               | Irrigation Required
2025-01-02   | 40               | No Irrigation Needed
```

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions.

