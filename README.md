# Order in Chaos: Understanding Criminal Patterns in Germany

Crime prevention and criminal justice are pressing concerns in contemporary society. This project delves into police crime statistics from 2002 to 2022, obtained from the [*Bundeskriminalamt*](https://www.bka.de/EN/CurrentInformation/Statistics/PoliceCrimeStatistics/policecrimestatistics_node.html). Our analysis focuses on predicting future case numbers, understanding frequent offenses, age distribution of suspects, and changes in clearance rates. We employ statistical methods and visualizations to enhance comprehension of underlying patterns.


## Project Structure

- **src**: we should write if we have sth in src
- **dat**: Includes datasets, notably our crime statistics datasets obtained from the *Bundeskriminalamt* [website](https://www.bka.de/EN/CurrentInformation/Statistics/PoliceCrimeStatistics/policecrimestatistics_node.html). For detailed information on the datasets, refer to the [Datasets](#datasets) section below.
- **exp**: Includes Jupyter notebooks for detailed experiments.
  - `exp_ALL_001_BasicDataAnalysis.ipynb`: 
  - `exp_DM_BS_001_AgeGroupAnalysis.ipynb`:
  - `exp_RA_001_TimeSeriesAnalysis.ipynb`:
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

For this project, we used multiple datasets obtained from the *Bundeskriminalamt* [website](https://www.bka.de/EN/CurrentInformation/Statistics/PoliceCrimeStatistics/policecrimestatistics_node.html). These datasets cover police crime statistics spanning from 2002 to 2022 and are stored in various formats.

- **2002 to 2013**: Data for these years is stored in PDF files, offering a concise overview of crime trends. Key features include the offence key, offence category name, number of recorded cases, change in the number of recorded cases compared to the previous year, and clearance rates in percentage. We extracted this data into Excel files (Cases20**.xlsx).

- **2014 to 2022**: Data for these years is stored in Excel files, providing more detailed information. The files are categorized into three tables:

  - **Case Basic Table**: Includes the offence key, offence category name, number of recorded cases, distribution of crime scenes according to the number of inhabitants in the area, clearance rate in percentage, and the number of non-German suspects.

  - **Suspects**: Provides information on suspects, including their sex and their number per offence distinguished by age categories.

  - **Victims**: Provides information on victims, including their sex and their number per offence distinguished by age categories.
 




