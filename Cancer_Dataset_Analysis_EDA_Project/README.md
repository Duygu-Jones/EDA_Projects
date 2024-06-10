
# Cancer Cell Analysis EDA Project

## Executive Summary:

Using Python, we performed an Exploratory Data Analysis (EDA) on the Cancer dataset to understand the characteristics of tumor cells and determine whether the tumors are benign or malignant. This project involved data cleaning, preprocessing, visualization, and analysis to gain insights into the dataset and provide recommendations for further research and potential applications in cancer diagnosis.

## Project Description:

- In this project, we conducted a basic Exploratory Data Analysis (EDA) on the **Cancer.csv** dataset.
- EDA helps us understand the dataset in detail using basic Python code.
- Each sample in the dataset belongs to a patient and includes various biopsy measurements.
- These measurements provide information about the characteristics of the tumor cells.
- By examining these features, we aim to determine whether the tumor is **benign** (iyi huylu) or **malignant** (kötü huylu).

## Getting to Know About Cancer:

![Cancer Image](image.png)

- Cancer is characterized by the uncontrolled growth and spread of abnormal cells in the body (metastasize).
- Early detection is crucial as non-metastatic cancer is often curable, emphasizing the importance of research in early detection.
- Cancer can result from genetic mutations, either inherited or acquired due to environmental factors.
- Treatment options include surgery, chemotherapy, radiation therapy, immunotherapy, or targeted therapy, depending on the cancer type and stage.

## Methodology:

1. **Data Extraction and Cleaning:**
   - Extracted and cleaned the data from the Cancer dataset using Pandas.
   - Handled missing values and ensured data consistency.

2. **Data Preprocessing:**
   - Transformed and standardized the data to prepare it for analysis.
   - Created new features and engineered existing ones to enhance the analysis.

3. **Exploratory Data Analysis:**
   - Performed statistical analysis and visualized the data using Matplotlib and Seaborn.
   - Examined the relationships between different features and their impact on tumor classification.

### Key Visualizations:

1. **Mean Area vs. Mean Smoothness:**
![Mean Area vs Smoothness](image-1.png)

2. **Distribution of Mean Area by Diagnosis:**
![Distribution of Mean Area](image-2.png)

## Key Features and Their Importance:

1. **Radius:** Mean radius of the tumor cells.
   - Higher radius values indicate a larger tumor size, suggesting malignancy.
   - Lower radius values indicate a smaller tumor size, suggesting benignity.

2. **Texture:** Standard deviation of gray-scale values.
   - Higher texture values indicate more irregular and complex cell structures, suggesting malignancy.
   - Lower texture values indicate more uniform cell structures, suggesting benignity.

3. **Perimeter:** Mean perimeter of the tumor cells.
   - Higher perimeter values indicate a larger and more irregular tumor boundary, suggesting malignancy.
   - Lower perimeter values indicate a smaller and more regular tumor boundary, suggesting benignity.

4. **Area:** Mean area of the tumor cells.
   - Higher area values indicate a larger tumor size, suggesting malignancy.
   - Lower area values indicate a smaller tumor size, suggesting benignity.

5. **Smoothness:** Mean of local variation in radius lengths.
   - Higher smoothness values indicate less regular and smooth cell boundaries, suggesting malignancy.
   - Lower smoothness values indicate more regular and smooth cell boundaries, suggesting benignity.

## Conclusion:

Creating detailed visualizations and performing statistical analysis provided insights into the characteristics of tumor cells. This analysis showed that certain features, such as radius, texture, perimeter, area, and smoothness, play a significant role in determining whether a tumor is benign or malignant. 

## Next Steps:

1. **Advanced Modeling:**
   - Build machine learning models to predict tumor malignancy based on the identified key features.

2. **Feature Engineering:**
   - Explore additional features and interactions between features to improve model accuracy.

3. **Validation:**
   - Validate the findings with a larger and more diverse dataset to ensure generalizability.

---
