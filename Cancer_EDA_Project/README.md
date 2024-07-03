
# Cancer Dataset Analysis -EDA Project🔬🔥

---

## Executive Summary:

In this project, performed an Exploratory Data Analysis (EDA) on the **Cancer.csv** dataset using Python.<br> 
- **Objective:** To examine the features of **benign** and **malignant** cells and determine the structural similarities and differences between these tumour cells.<br>
- **Dataset:** Each sample belongs to a patient and includes various biopsy measurements that provide information about the characteristics of the tumour cells.<br>
- **Methodology:** Data cleaning, preprocessing, visualization, and analysis to gain insights into the dataset and provide recommendations for further research and potential applications in cancer diagnosis.<br>



### Problem: How do benign cells differ from malignant cells?
Cancer remains one of the most critical health challenges worldwide.
- Cancer is a disease characterized by the uncontrolled growth and spread of abnormal cells in the body (metastasize).
- Cancer can be caused by genetic mutations that can be inherited or acquired due to environmental factors.
- However, it is curable if detected in its early stages as a non-metastatic disease, highlighting the importance of early detection and the need for continued research in this area.

![image](https://github.com/Duygu-Jones/EDA_Projects/assets/141514497/951e195d-f6cf-4909-a214-cd770cc62595)


For more information:
- [The Difference Between Normal and Cancer Cells](https://drjockers.com/cancer-cells/)   
- [Cancer Cells vs Normal Cells](https://www.technologynetworks.com/cancer-research/articles/cancer-cells-vs-normal-cells-307366)



### About the Cancer Dataset: 

Structural Analysis;
- **Dataset**: Cancer.csv
- **Number of Rows**: 569
- **Number of Columns**: 31   
        
   - *Columns between [0-9] represent the **mean** in the measurements of various tumour characteristics.*
   - *Columns between [10-19] represent the **error rates** (std) in the measurements of various tumour characteristics.*
   - *Columns between [20-29] represent the **mean of the 3 worst (largest) values** in the measurements of various tumour characteristics.*
   - *The column [30] represents:* **target**: Type of tumor cell (**1: benign, 0: malignant**).




### Methodology:

1. Data Extraction and Cleaning:
   - Extracted and cleaned the data from the Cancer dataset using Pandas.
   - Handled missing values and ensured data consistency.
2. Data Preprocessing:
   - Transformed and standardized the data to prepare it for analysis.
   - Created new features and engineered existing ones to enhance the analysis.
3. Exploratory Data Analysis:
   - Performed statistical analysis and visualized the data using Matplotlib and Seaborn.
   - Examined the relationships between different features and their impact on tumour classification.




### Skills:

- **Python**: Pandas, Matplotlib, Seaborn, Numpy, data cleaning, data visualization, statistical analysis.
- **Data Analysis**: Exploratory Data Analysis (EDA), handling missing values, descriptive statistics.
- **Data Visualization**: Creating plots and charts to visualize data insights.



### Conclusion:

Creating detailed visualizations and performing statistical analysis provided insights into the characteristics of tumour cells.<br>
The visualizations highlighted key differences between benign and malignant cells, which could inform future predictive modelling efforts. 



### Next Steps:

1. By focusing on key features, develop effective predictive models and diagnostic tools to aid early detection and enhance patient outcomes.
2. Explore additional features and interactions between features to improve model accuracy.
3. Validate the findings with a larger and more diverse dataset to ensure generalizability.

---

*For more details about the analysis and the visualisation, check out the notebook.*

- **Notebook:** [Cancer_Dataset_Analysis_EDA_Project.ipynb]([path/to/your/notebook](https://github.com/Duygu-Jones/EDA_Projects/blob/main/Cancer_Dataset_Analysis_EDA_Project/Cancer_Dataset_Analysis_EDA_Project.ipynb))
- **Download the Dataset:** [Cancer.csv]([path/to/your/dataset](https://github.com/Duygu-Jones/EDA_Projects/blob/main/Cancer_Dataset_Analysis_EDA_Project/cancer.csv))


*To view the notebook online, visit my Kaggle profile. Don't forget to join the discussion!*

- **Kaggle Nootebook**: [Cancer Dataset Detailed EDA Project](https://www.kaggle.com/code/duygujones/cancer-dataset-detailed-eda-project)
- **Find the Dataset on Kaggle:** [Cancer.csv](https://www.kaggle.com/datasets/duygujones/cancer-dataset-csv)

---


## 🤝Contributing

Contributions are welcome! If you have any improvements, suggestions, or additional datasets and EDA projects to share, please fork the repository and create a pull request.

<br>

## 🌱About Me 

I'm Duygu Jones, a Data Scientist, passionate about data visualization, analysis, and machine learning. 

♻️ You can find more about me and my work through the following links:

- **Linkedin**: [Linkedin/duygujones](https://www.linkedin.com/in/duygujones/)
- **Website**: [duygujones.com](https://duygujones.vercel.app/)
- **Kaggle**: [kaggle.com/duygujones](https://www.kaggle.com/duygujones)
- **GitHub**: [github.com/Duygu-Jones](https://github.com/Duygu-Jones)
- **Medium**: [medium.com/@duygujones](https://medium.com/@duygujones)
- **Tableau Public**: [Duygu Jones on Tableau Public](https://public.tableau.com/app/profile/duygu.jones/vizzes)

🌐Feel free to connect with me!

<br>

🎯 Boost your exploratory data analysis skills,<br>
💡 Share your insights with the community,<br>
✨ If you find this repository helpful, don't forget to give it a ⭐ star.<br>

Code with joy! 👩‍💻✨

---



##### 📜 License

##### This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
