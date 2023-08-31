# NY SPARCS Hospital Discharge - Synthetic Data Generation

Welcome to the repository for synthetic data generation based on [New York's SPARCS Hospital Discharge Records](ttps://health.data.ny.gov/)). Our goal here is to showcase how synthetic data can enhance the capabilities of machine learning models.


## 📌 Motivation

Synthetic data is a game-changer in the realm of machine learning. By generating high-quality synthetic data, we can train large-scale ML systems which, interestingly, can often perform more effectively on real-world data compared to models trained and tested solely on actual data. This approach minimizes overfitting, diversifies the training regime, and can provide robustness to the machine learning systems, making them more adaptable to a variety of scenarios.


## 📘 Contents

- [Notebooks](#notebooks)
- [Data Files](#data-files)
- [License](#license)


## 📔 Notebooks

### [Clean NY Data](synfo-ny-discharge/clean_ny_data.ipynb)
This Jupyter notebook walks you through the initial steps in our data preprocessing pipeline. Here, we detail the process of cleaning the SPARCS Hospital Discharge Records, ensuring data quality and consistency.

### [Encode NY Data](synfo-ny-discharge/encode_ny_data.ipynb)
In this notebook, we delve into encoding techniques tailored for the dataset. Encoding is crucial in preparing the data for synthetic data generation, ensuring that the generated data maintains properties similar to the original.

### [NY Synfo Tutorial](synfo-ny-discharge/ny-synfo-tutorial.ipynb)
A comprehensive guide that takes you step-by-step through the process of synthetic data generation for the NY SPARCS data. Ideal for both beginners and experienced practitioners.


## 📂 Data Files

New York's SPARCS Hospital Discharge Record data from 2009 to 2021 can be obtained from the [Health Data NY Catalog](https://health.data.ny.gov/browse?q=Hospital%20Inpatient%20Discharges%20(SPARCS%20De-Identified)%3A&sortBy=relevance). 

### [2018_I9gem.txt](synfo-ny-discharge/2018_I9gem.txt)
This text file contains [ICD-9 to ICD-10 mappings](https://icd.codes/convert/icd9-to-icd10-cm), an essential tool for understanding the conversion between these medical coding systems.

### [geo-updated.csv](synfo-ny-discharge/geo-updated.csv)
Updated geographical data linked with the NY SPARCS records. This dataset provides details on Operating Certificate Numbers, assisting in the geographic location mapping of hospitals and care facilities.


## 📜 License

This project is licensed, ensuring open source availability while protecting against unauthorized use or modification. Please take a look at the [LICENSE](LICENSE) file for a detailed description of terms and conditions.

---

If you have any questions or suggestions, feel free to contribute to this project or contact our team. We are always eager to enhance and expand upon our work.

We thank the New York State Department of Health for releasing these datasets. **Note**: The New York State Department of Health makes no representation, warranty or guarantee relating to the data or analyses derived from these data.
