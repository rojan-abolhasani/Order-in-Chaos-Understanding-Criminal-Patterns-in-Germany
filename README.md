# Order in Chaos: Understanding Criminal Patterns in Germany

Crime prevention and criminal justice are pressing concerns in contemporary society. This project delves into police crime statistics from 2002 to 2022, obtained from the [*Bundeskriminalamt*](https://www.bka.de/EN/CurrentInformation/Statistics/PoliceCrimeStatistics/policecrimestatistics_node.html). Our analysis focuses on predicting future case numbers, understanding frequent offenses, age distribution of suspects, and changes in clearance rates. We employ statistical methods and visualizations to enhance comprehension of underlying patterns.


## Project Structure

- **dat**: Includes datasets, notably our crime statistics datasets obtained from [*Bundeskriminalamt*](https://www.bka.de/EN/CurrentInformation/Statistics/PoliceCrimeStatistics/policecrimestatistics_node.html). For detailed information on the datasets, refer to the [Datasets](#datasets) section below.
- **exp**: Includes Jupyter notebooks for detailed experiments.
  - `exp_ALL_BasicDataAnalysis.ipynb`: Some simple analysis to understand the provided datasets better.
  - `exp_DM_BS_AgeGroupAnalysis.ipynb`: Analysis of suspect ages and permutation test.
  - `exp_DM_PredictingCaseNumbersWithModels.ipynb`: Prediction of the total number of cases for 2023 (not yet officially available) with regression models.
  - `exp_RA_TimeSeriesAnalysis.ipynb`: Time series analysis and forcasting
  - `exp_DM_RA_ClearanceRateAnalysis.ipynb`: Analysis of the clearance rates for each year, comparing it to the total number of cases and grouped by categories of offenses.
- **doc**: Stores papers and figures related to the project.
  - `InOrderChaos`: A directory for our paper.
    - `paper.tex`: LaTeX source file for the paper.
  - `fig`: Contains Python scripts and PDF files for shared figures.
    - `introduction_plot.pdf`: Generated figure displaying the main data from the files (Total number of cases, suspect numbers, victim numbers and clearance rates).
    - `prediction_models.pdf`: Generated figure showing the performance of different regression models fitted to the total case numbers.
    - `age_group_distribution.pdf`: Generated figure displaying the distribution of suspect ages.
    - `clearance_rate_heatmap.pdf`: Generated heatmap showing the clearance rates for each offence between 2014 and 2022.
    - `top_5_offences_among_non_germans.pdf`: Generated figure depicting the top 5 offences among non-German suspects in years 2014-2022.


## Datasets

For this project, we used multiple datasets obtained from [*Bundeskriminalamt*](https://www.bka.de/EN/CurrentInformation/Statistics/PoliceCrimeStatistics/policecrimestatistics_node.html). These datasets cover police crime statistics spanning from 2002 to 2022 and are stored in various formats.

- **2002 to 2013**: Data for these years is stored in PDF files, offering a concise overview of crime trends. Key features include the offence key, offence category name, number of recorded cases, change in the number of recorded cases compared to the previous year, and clearance rates in percentage. We extracted this data into Excel files (Cases20**.xlsx).

- **2014 to 2022**: Data for these years is stored in Excel files, providing more detailed information. The files are categorized into three tables:

  - **Case Basic Table**: Includes the offence key, offence category name, number of recorded cases, distribution of crime scenes according to the number of inhabitants in the area, clearance rate in percentage, and the number of non-German suspects.

  - **Suspects**: Provides information on suspects, including their sex and their number per offence distinguished by age categories.

  - **Victims**: Provides information on victims, including their sex and their number per offence distinguished by age categories.
 

## Reproducing the Analysis

To reproduce the analysis and explore the findings in your own environment, follow these steps:

1. **Clone this repository** to your local machine by running the following command in your terminal:

    ```bash
    git clone https://github.com/rojan-abolhasani/Order-in-Chaos-Understanding-Criminal-Patterns-in-Germany.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd Order-in-Chaos-Understanding-Criminal-Patterns-in-Germany
    ```

3. **Open the notebook** (e.g., `exp_ALL_BasicDataAnalysis.ipynb`) in a Jupyter environment. If you prefer, you can use platforms like Google Colab for easy cloud-based notebook execution.


4. **Download datasets** from the *dat* directory in this repository and upload them to your analysis environment (e.g., Google Colab). Ensure that the notebook cells loading data reference the correct names, making modifications if using different names from the originals.

Remember to run the notebook cells sequentially.


Feel free to reach out if you encounter any issues or have questions. 

 




