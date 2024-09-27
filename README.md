# Restaurant-Staffing---Cost-Saving-Analysis

This project analyzes the staffing adequacy and profitability of two restaurant locations: Stavanger and Sandnes. The primary goal is to help the restaurant management evaluate whether the restaurants are appropriately staffed and identify opportunities for cost savings. The project also provides an analysis of product profitability and low-margin products to suggest potential cost-cutting measures.

## Data Source
The data used in this analysis was obtained from a job assessment.

## Datasets

The following sheets of the Excel file are included in the project:
- `Sales`: Includes sales information for the restaurant's products.
- `Timesheet`: Contains employee shift data for the Stavanger and Sandnes locations.
- `dimEmployee`: Contains IDs and names of employees.
- `dimProduct`: Contains product names and IDs.

## Project Workflow

### 1. **Required Libraries**
Install the dependencies
All necessary dependencies are listed in the requirements.txt file. You can install them by running:

pip install -r requirements.txt

### 2. **Key Analysis Areas**
- **Staffing Analysis**: I analyzed employee shifts for each location, calculate average shifts per employee, and categorize employees for either additional training or termination based on performance.
- **Profitability Analysis**: The profitability of each product is calculated. Products with low profit margins are flagged, and recommendations for cost savings are made.
- **Branch-Specific Insights**: A comparison between the two restaurant locations, including staffing adequacy and profit margins, with specific emphasis on understaffing in Stavanger and overstaffing trends in Sandnes.

### 3. **Final Deliverables**
- Insights into overall staffing adequacy across the two branches.
- List of employees requiring further training or termination based on shift performance.
- Product-wise profit margin analysis, identifying 37 low-margin products for potential elimination.

### 4. **Project Findings**
- Stavanger is a new and highly profitable branch but significantly understaffed.
- Sandnes, though less profitable, often faces overstaffing.
- A set of 37 low-margin products were identified, which can be removed to improve profitability.

### 6. **Visualization**
- Various plots and charts are included to visualize staffing and profitability trends.

---
