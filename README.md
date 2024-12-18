# Data Science. Football Transfer Price Prediction - Group 19

![image](https://github.com/user-attachments/assets/d0cf219d-ded3-466a-9e77-923c72ecae1e)
***



## Introduction

In an era where data-driven decisions dominate the sports industry, accurately predicting the market value of football players has become a vital task.

This project represents our team’s initiative to collect and analyze player data to develop a predictive model for estimating football players' market value. By leveraging data scraped from platforms such as **Transfermarkt**, we built a robust machine learning pipeline that emphasizes both accuracy and scalability. 

Our approach integrates **Python** and popular libraries like Pandas, Matplotlib, Seaborns to work with data, and Scikit - learn for machine learning works.

***This project is intended for `educational purposes only`. The model's performance is subject to dataset limitations and does not guarantee accurate prediction. It should not be used as a replacement for professional safety measures or health compliance systems.***
***



## Applications
- Talent scouting and valuation for football clubs.
- Strategic decision-making for player transfers.
- Analytical insights for agents and market analysts.

This project demonstrates the potential of data science in revolutionizing talent valuation in professional football.
***



## Key Features

- **Data Collection and Parsing:** Utilized [Requests](https://docs.python-requests.org/en/latest/) and [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) to scrape and parse football player data, ensuring robust and efficient data extraction.

- **Data Preprocessing and Analysis:** Conducted preprocessing and exploratory data analysis (EDA) using [Pandas](https://pandas.pydata.org/) and [Matplotlib](https://matplotlib.org/). Included data cleaning, feature engineering, and visualization of trends and distributions.

- **Statistical Analysis:** Applied z-score techniques from [SciPy](https://scipy.org/) for outlier detection and normalization methods like StandardScaler and MinMaxScaler from [Scikit-learn](https://scikit-learn.org/stable/) for data scaling.

- **Data Visualization:** Enhanced EDA with advanced visualizations using [Seaborn](https://seaborn.pydata.org/) to identify correlations and patterns in the dataset.

- **Automated Reporting:** Generated detailed profiling reports with [YData Profiling](https://ydata-profiling.github.io/) for a comprehensive summary of dataset statistics and distributions.

- **Model Training and Evaluation:** Prepared data for machine learning by splitting it into training and testing sets using [Scikit-learn](https://scikit-learn.org/stable/) for predictive modeling.

- **Persistence and Deployment:** Saved preprocessed datasets and trained models using [Joblib](https://joblib.readthedocs.io/en/latest/) for efficient reuse in future tasks.
***



## Project Structure

- **build model +checkpoints**:  
   Directory containing trained models and checkpoints saved during the training process.

- **data**:  
   Directory containing raw and preprocessed data files used for training and analysis.

- **README.md**:  
   Main documentation file explaining the project, its features, structure, and usage instructions.

- **data_crawling.ipynb**:  
   Jupyter Notebook for collecting data from external sources and storing it in a structured format.

- **data_visualization.ipynb**:  
   Jupyter Notebook for visualizing and analyzing the data to uncover trends and relationships.

- **exploratory_data_analyst.ipynb**:  
   Jupyter Notebook for **Exploratory Data Analysis (EDA)** to clean, preprocess, and prepare data for model training.
***



## Acknowledgments
This project would not have been possible without the invaluable contributions of several open-source libraries. These robust tools and resources were instrumental in the success of this project.

We extend our heartfelt gratitude to our lecturers, Professor Than Quang Khoat, for assigning us this challenging yet captivating project. It has been an incredible learning opportunity that has significantly enhanced our knowledge and skillset.

Our sincere thanks also go to our professor in the Department for their unwavering support and sharing during the whole course.

Finally, we would like to acknowledge our peers for their indirect contributions, offering both moral and practical support that kept us motivated and
***



## Contributors
- Lưu Thiện Việt Cường - 20225445
- Lại Trí Dũng - 20225486
- Đỗ Đình Hoàng - 20225445
- Bùi Văn Huy - 20225497
- Trịnh Huynh Sơn - 20225526
***



## License
This project is licensed under the [MIT License](LICENSE).
