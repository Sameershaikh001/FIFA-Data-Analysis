# FIFA Data Analysis

Explore FIFA player data using Python and enhance your data science skills. This repository highlights:

## Key Features
- **Data Preprocessing**: Cleaning and preparing datasets for robust analysis.
- **Exploratory Data Analysis (EDA)**: Gaining insights through statistical analysis and visualizations.
- **Advanced Visualizations**: Presenting data trends effectively using modern tools.

## Dataset
The dataset used for this analysis was sourced by scraping FIFA player statistics from [Sofifa](https://sofifa.com/players?offset=). The cleaned data is also available as a CSV file in the `data/` directory.

## Project Workflow

1. **Data Collection**: 
   - Web scraped player data using `requests` and `BeautifulSoup` libraries.
   - Converted the scraped data into a Pandas DataFrame and saved it as an Excel sheet.

2. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables.
   - Normalizing and scaling features.

3. **Exploratory Data Analysis (EDA)**:
   - Summary statistics.
   - Correlation matrix.
   - Key player attributes by position.

4. **Visualization**:
   - Player distribution by overall rating.
   - Top players by market value.
   - Skill comparison across player positions.

## Usage

1. Open and run the Jupyter Notebook provided:
   ```bash
   jupyter notebook FIFA.ipynb
   ```
2. Follow the step-by-step code to preprocess the data, perform EDA, and generate visualizations.

## Requirements
- Python 3.7+
- Pandas
- NumPy
- BeautifulSoup
- Requests
- Matplotlib
- Seaborn
- Jupyter Notebook

## Contribution
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## License
This project is licensed under the [MIT License](LICENSE).

## Who is it for?
Football enthusiasts, analysts, and developers eager to explore FIFA statistics and apply data science techniques.
