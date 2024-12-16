# **Automated Data Analysis with GPT Integration**

## **Overview**
This project automates the process of data analysis, visualization, and insight generation using Python. By integrating with a Large Language Model (LLM), it performs detailed statistical analysis, creates insightful visualizations, and generates comprehensive reports in Markdown format. Designed to handle CSV datasets, the system is capable of delivering detailed insights and actionable recommendations from any dataset.

## **Key Features**
- **Automated Data Analysis**: Performs in-depth summary statistics, missing value detection, anomaly identification, and correlation analysis.
- **Dynamic Visualizations**: Generates high-quality, customized visualizations such as heatmaps and bar plots based on dataset characteristics.
- **Narrative Insights**: Uses GPT-4o-Mini to craft detailed reports, providing context and recommendations based on the analysis.
- **Optimized LLM Usage**: Efficiently queries the LLM to maximize token usage while maintaining high analytical precision.

## **Workflow**
1. **Data Preprocessing**: The script reads and processes the input CSV file, extracting metadata and identifying potential issues like missing data or anomalies.
2. **Exploratory Data Analysis (EDA)**: Generates statistical summaries, correlation matrices, and performs clustering analysis.
3. **LLM Integration**: Sends data insights to GPT-4o-Mini to generate detailed analysis and recommendations.
4. **Visualization Creation**: Creates relevant visualizations (e.g., heatmaps and bar charts) and saves them as PNG files.
5. **Report Generation**: Combines analysis results and visualizations into a Markdown report.

## **Usage**
1. Clone the repository and navigate to the project directory:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Set up your environment variable for authentication:
   ```bash
   export AIPROXY_TOKEN=your-token-here
   ```

3. Run the script with a CSV dataset:
   ```bash
   python autolysis.py dataset.csv
   ```

4. The script generates:
   - `README.md`: The main analysis report.
   - `*.png`: Visualization files.

## **Sample Datasets**
The system has been tested with datasets such as:
- **goodreads.csv**: Information about 10,000 books.
- **happiness.csv**: Data from the World Happiness Report.
- **media.csv**: Faculty evaluations of movies, TV shows, and books.

## **Licensing**
This project is licensed under the MIT License. Please refer to the LICENSE file for more details.

---

This revised README description is brief yet informative and provides all the essential details for users to get started. Let me know if you need any further adjustments!
