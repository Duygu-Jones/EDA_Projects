# Kyphosis Disease Analysis - EDA Project🔬🔥

---

## Executive Summary:

In this project, an Exploratory Data Analysis (EDA) was performed on the **Kyphosis.csv** dataset using Python.<br> 
The analysis will involve data cleaning, processing, visualization, and interpretation of key findings to derive actionable insights.

- **Objective:**
  - To understand the distribution of kyphosis conditions across different vertebra groups.
  - To visualize the range of kyphosis and recovery rates in the dataset.
  - To identify potential patterns or insights to inform further research or medical practices.

- **Methodology:** Data cleaning, preprocessing, visualization, and analysis to gain insights into the dataset and provide recommendations for further research and potential applications in kyphosis diagnosis.<br>


### About the Kyphosis Dataset: 

- **Structural Analysis**  
    - **Dataset**: kyphosis.csv
    - **Number of Rows**: 81
    - **Number of Columns**: 4   

   
INPUTS:  
  1. **Age**: The age of the patient in months (children), 
  2. **Number**: The number of vertebrae involved in the surgery, 
  3. **Start**: The number of the first (top-most) vertebra operated on.
  4. **Kyphosis**: Indicates whether kyphosis was **present** or **absent** after the operation. 
   
OUTPUTS: Represents a factor with variables **present** and **absent** indicating if **kyphosis** (a type of deformation) was present or not after the corrective spinal surgery.


#### Understanding the Anatomy of Vertebrae

![image](https://github.com/Duygu-Jones/EDA_Projects/assets/141514497/8690fc52-43db-4a13-8abd-44e53a412b2e)


##### Groups of Anatomic Vertebrae: 

1. **Cervical Spine (C1-C7)** (Neck)
    - Number of Vertebrae: 7
2. **Thoracic Spine (T1-T12)** (Back)
    - Number of Vertebrae: 12
3. **Lumbar Spine (L1-L5)** (Lower back)
    - Number of Vertebrae: 5
4. **Sacrum (S1-S5, fused)** 
    - Number of Vertebrae: 5
5. **Coccyx (Co1-Co4, fused)**
    - Number of Vertebrae: 4

These groups represent the different sections of the vertebral column, with each section containing a specific number of vertebrae.

  For more information:
  - [Understanding Kyphosis](https://www.healthline.com/health/kyphosis)   
  - [Kyphosis: Causes, Symptoms, and Treatment](https://www.spine-health.com/conditions/spine-anatomy/kyphosis)



#### Feature Engineering: Classifying the 'Start' column in the Dataset to Anatomic Vertebrea Groups

In this Dataset; the **Start** column is the **first** (top-most) vertebra number operated on and contains the numbers between (1-18).

- We categorized the vertebra numbers in the Start column into Anatomical groups, and
- A new column 'Vertebrae Group'  is created to classify the values in the Start column.

    **Vertebrea Groups for the 'Start' column**
    - 1-7: Cervical (C1-C7) (Neck)
    - 8-19: Thoracic (T1-T12) (Back)
    - 20-24: Lumbar (L1-L5) (Lower Back)
    - 25-29: Sacrum (S1-S5) (Sacral)

- We labelled each group of vertebras with a number and created a new column called 'Vertebrae Group Number'.

    **Labels of the Vertebrea Groups**
    - (1) Cervical (C1-C7)
    - (2) Thoracic (T1-T12)
    - (3) Lumbar (L1-L5)
    - (4) Sacrum (S1-S5)
    - (5) Unknown

---

### Methodology:

1. Data Extraction and Cleaning:
   - Extracted and cleaned the data from the Kyphosis dataset using Pandas.
   - Handled missing values and ensured data consistency.
2. Data Preprocessing:
   - Transformed and standardized the data to prepare it for analysis.
   - Created new features and engineered existing ones to enhance the analysis.
3. Exploratory Data Analysis:
   - Performed statistical analysis and visualized the data using Matplotlib and Seaborn.
   - Examined the relationships between different features and their impact on kyphosis classification.

### Skills:

- **Python**: Pandas, Matplotlib, Seaborn, Numpy, data cleaning, data visualization, statistical analysis.
- **Data Analysis**: Exploratory Data Analysis (EDA), handling missing values, descriptive statistics.
- **Data Visualization**: Creating plots and charts to visualize data insights.


### Conclusion:

Creating detailed visualizations and performing statistical analysis provided insights into the characteristics of kyphosis patients.<br>
The visualizations highlighted key differences between patients with and without kyphosis, which could inform future predictive modelling efforts. 


#### Key Takeaways:

  1. **Treatment and Prevention Strategies:**
     - The balanced distribution of kyphosis in the cervical region suggests a need for careful planning of treatment and prevention strategies in this area.
     - The rarity of kyphosis in the thoracic region indicates a different approach may be required for patients in this area.
  
  2. **Attention to Start Vertebra Numbers:**
     - Higher kyphosis presence in specific vertebrae suggests developing special treatment protocols targeting these vertebrae.
  
  3. **Correlation Findings:**
     - The correlation between the number of vertebrae operated on and the start vertebra number can inform surgical planning. Operations starting from certain vertebrae tend to involve more vertebrae.


#### Next Steps:

Further analysis with advanced statistical tests and machine learning models is recommended to better understand and predict kyphosis.

---

*For more details about the analysis and visualisation, check out the notebook.*

- **Notebook:** [Kyphosis_Disease_Detailed_EDA_Project.ipynb](https://github.com/Duygu-Jones/EDA_Projects/blob/main/Kyphosis_Risk_Analysis_EDA_Project/kyphosis-disease-detailed-eda-project.ipynb)
- **Download the Dataset:** [Kyphosis.csv](https://github.com/Duygu-Jones/EDA_Projects/blob/main/Kyphosis_Risk_Analysis_EDA_Project/kyphosis.csv)

*To view the notebook online, visit my Kaggle profile. Don't forget to join the discussion!*

- **Kaggle Notebook**: [Kyphosis Disease Detailed EDA Project](https://www.kaggle.com/code/duygujones/kyphosis-disease-detailed-eda-project)

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
