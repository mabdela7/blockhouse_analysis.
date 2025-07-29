
# Blockhouse Market Impact & Optimal Allocation Project

This project provides advanced quantitative analysis for modeling temporary market impact and optimizing order allocation strategies. The goal is to minimize trading costs by understanding and predicting the price impact of large orders and formulating optimal execution algorithms.

## Project Structure

- `blockhouse_analysis.py`: Main Python script for data loading, impact modeling, and optimal execution.
- `impact_modeling_analysis.ipynb`: Jupyter Notebook with detailed analysis and visualizations.
- `output/`: Generated plots and analysis results.
- `docs/`: Interactive HTML dashboard and supplementary PDF documents.

## Key Features

- **Data Processing:** Load and preprocess market data for multiple stocks and time intervals.
- **Temporary Impact Modeling:** Linear and non-linear (power-law) models for temporary market impact `g_t(x)`.
- **Optimal Order Allocation:** Mathematical framework and algorithm to determine optimal order allocation (`x_i`) over time intervals (`t_i`) to minimize trading costs, ensuring `Σx_i = S` (total shares).
- **Visualization:** Professional plots to visualize impact models and optimal allocation strategies.
- **Interactive Dashboard:** Modern HTML dashboard (`docs/index.html`) for easy navigation of analysis, plots, and documents.
- **Comprehensive Documentation:** Detailed explanations in PDF format and interactive HTML report.

## How to Run

1. **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd blockhouse_analysis-main
    ```
2. **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scipy notebook nbconvert
    ```
3. **Run the analysis script:**
    ```bash
    python blockhouse_analysis.py
    ```
    This script processes data, fits models, and generates output plots in the `output/` directory.
4. **View the detailed analysis (Jupyter Notebook):**
    ```bash
    jupyter notebook impact_modeling_analysis.ipynb
    ```
    Or view the HTML version directly: `docs/impact_modeling_analysis_output.html`
5. **Access the Interactive Dashboard:**
    Open `docs/index.html` in your web browser to explore the analysis report, plots, and supplementary documents.

## Deliverables

- **Interactive Analysis Report:** `docs/impact_modeling_analysis_output.html`
- **Modeling the Temporary Impact Function g_t(x):** `docs/Modeling_the_Temporary_Impact_Function_g_t_x.pdf`
- **Mathematical Framework for Optimal Order Allocation:** `docs/Mathematical_Framework_for_Optimal_Order_Allocation.pdf`
- **Modeling Temporary Impact and Optimal Order Allocation (Presentation):** `docs/Modeling_Temporary_Impact_and_Optimal_Order_Allocation.pdf`
- **Generated Plots:** Located in the `output/` directory and linked in `docs/index.html`.

## Contact

For any questions or further discussion, please contact [Your Name/Email/LinkedIn].


