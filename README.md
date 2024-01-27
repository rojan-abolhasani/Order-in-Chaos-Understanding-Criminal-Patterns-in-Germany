# Order in Chaos: Understanding Criminal Patterns in Germany

Crime prevention and criminal justice are pressing concerns in contemporary society. This project delves into police crime statistics from 2002 to 2022, obtained from the [*Bundeskriminalamt*](https://www.bka.de/EN/CurrentInformation/Statistics/PoliceCrimeStatistics/policecrimestatistics_node.html). Our analysis focuses on predicting future case numbers, understanding frequent offenses, age distribution of suspects, and changes in clearance rates. We employ statistical methods and visualizations to enhance comprehension of underlying patterns.


## Project Structure

- **src**: we should write if we have sth in src
- **dat**: Includes datasets, notably our crime statistics datasets obtained from [*Bundeskriminalamt*](https://www.bka.de/EN/CurrentInformation/Statistics/PoliceCrimeStatistics/policecrimestatistics_node.html). For detailed information on the datasets, refer to the [Datasets](#datasets) section below.
- **exp**: Includes Jupyter notebooks for detailed experiments.
  - `exp_ALL_001_BasicDataAnalysis.ipynb`: 
  - `exp_DM_BS_001_AgeGroupAnalysis.ipynb`:
  - `exp_RA_001_TimeSeriesAnalysis.ipynb`: Time series analysis and forcasting
- **doc**: Stores papers and figures related to the project.
  - `neurips2015`: A directory for our paper.
    - `paper.tex`: LaTeX source file for the paper.
  - `fig`: Contains Python scripts and PDF files for shared figures.
    - `fig_name1.py`: Python script for generating ...
    - `fig_name2.py`: Python script for generating ...
    - `fig_name3.py`: Python script for generating ...
    - `fig_name1.pdf`: Generated ... figure.
    - `fig_name2.pdf`: Generated ... figure.
    - `fig_name3.pdf`: Generated ... figure.


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

3. **Open the notebook** (e.g., `exp_ALL_001_BasicDataAnalysis.ipynb`) in a Jupyter environment. If you prefer, you can use platforms like Google Colab for easy cloud-based notebook execution.


4. In the notebook, there are sections where you need to load specific datasets. To do this:

   a. If you are running the analysis in your own environment (e.g., Google Colab), download the datasets from the `dat` directory in this repository and upload them to your analysis environment.

   b. Alternatively, if you prefer to download the data yourself, visit [*Bundeskriminalamt*](https://www.bka.de/EN/CurrentInformation/Statistics/PoliceCrimeStatistics/policecrimestatistics_node.html) and download the datasets relevant to the notebook. Ensure that you use the original names provided on the website and that they match the names used in the reading parts of the notebooks. All files should be in the Excel format. You can use ................ to extract data from PDFs in the excel format

   c. After uploading the datasets, modify the notebook cells that load data to ensure they reference the correct names. If the names you are using differ from the original names, make the necessary modifications in the notebook to reflect the uploaded dataset names.

Remember to run the notebook cells sequentially.


Feel free to reach out if you encounter any issues or have questions. 

 




