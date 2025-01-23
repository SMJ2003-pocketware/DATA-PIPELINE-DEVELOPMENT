# DATA-PIPELINE-DEVELOPMENT

*COMPANY*: CODTECH IT SOLUTIONS PVT.LTD

*NAME*: SOHAM MAJUMDER

*INTERN ID*: CT6WMIS

*DOMAIN*: DATA SCIENCE

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

As part of this task, I developed an automated data pipeline to preprocess, transform, and load data using Python. The pipeline was built using powerful libraries like Pandas and Scikit-learn, and I implemented it in a Jupyter Notebook environment hosted on Google Colab. I chose Google Colab because it offers a cloud-based, pre-configured setup that simplifies the process of writing and executing Python scripts. This made it easy for me to focus entirely on the task without worrying about the installation or configuration of dependencies. For handling the data, I used Pandas, which is an efficient tool for creating, cleaning, and manipulating datasets. Scikit-learn was instrumental in building the pipeline, as it provided essential preprocessing tools, including the SimpleImputer for filling missing values, StandardScaler for scaling numeric features, OneHotEncoder for converting categorical data into a machine-readable format, and the Pipeline module to combine all these steps into a streamlined and reusable process.
The process started with loading the data. I created a small sample dataset with missing values, numeric columns (like age and salary), and categorical columns (like city and gender). This step simulated a typical real-world scenario where raw data often contains inconsistencies and missing values. While the data was hardcoded for simplicity in this demonstration, it could easily be replaced with a dataset sourced from a file, a database, or an API. Once the data was loaded into a Pandas DataFrame, I moved on to preprocessing. I divided the columns into numeric and categorical groups, as these types of data require different handling techniques. For numeric columns, I applied SimpleImputer to fill missing values with the column mean and then standardized the data using StandardScaler to ensure that all values were on a comparable scale. For categorical columns, I used SimpleImputer to fill missing values with the most frequently occurring category and OneHotEncoder to convert these columns into dummy variables, making them suitable for machine learning models.
Next, I used a ColumnTransformer to combine the transformations for numeric and categorical data into a single processing step. This approach streamlined the preprocessing phase and ensured modularity and reusability of the pipeline. The entire workflow was automated using Scikit-learn's Pipeline feature, which allowed me to define a sequence of steps and apply them seamlessly to the data. After applying the pipeline, I converted the processed data back into a Pandas DataFrame, including descriptive column names for better readability. Finally, I saved the transformed data into a CSV file named processed_data.csv. Since I used Google Colab, the file was saved in the /content/ directory, which is the default workspace for Colab notebooks. The processed file could then be downloaded to my local machine or shared with others for further use.
This task highlights the importance of data pipelines in real-world applications. Data preprocessing and transformation are critical for tasks like machine learning, data analysis, ETL (Extract, Transform, Load) processes, and business intelligence. By automating these steps, the pipeline saves time and reduces errors, especially when working with large datasets. Google Colab proved to be an excellent platform for this task due to its simplicity, cloud-based storage, and collaborative features. This experience not only helped me understand the fundamentals of ETL processes but also demonstrated how tools like Pandas and Scikit-learn can be leveraged to build scalable and efficient data workflows.

#OUTPUT

![Image](https://github.com/user-attachments/assets/0038b953-2a5c-45da-a41b-806640419b37)

![Image](https://github.com/user-attachments/assets/0038b953-2a5c-45da-a41b-806640419b37)

![Image](https://github.com/user-attachments/assets/e027ebd4-eee7-4559-ac25-ad04eed6a364)
