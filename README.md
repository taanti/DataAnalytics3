# Learn Python for Data Analyst Part 3

Hi back to the Learn Python for Data Analyst series! In this final part of the series, we will focus on data analytics and visualization, responsible analytics, and the Cross Industry Standard Process for Data Mining (CRISP-DM) methodology. Data analytics and visualization are essential skills for data analysts, enabling them to extract insights and patterns from data and communicate findings effectively. Responsible analytics ensures that data is handled ethically and responsibly, while the CRISP-DM methodology provides a structured approach to data mining projects. Let's dive into the world of data analytics and visualization!

## Data Visualization

Data visualization is the process of transforming data into visual representations, such as charts, graphs, or maps, to help understand and analyze data effectively. It plays a crucial role in data analysis by providing insights and patterns that might not be apparent from raw data. Python offers several libraries for data visualization, including Matplotlib, Seaborn, and Plotly. There are several types of plots you can create using these libraries, such as line plots, bar plots, scatter plots, pie charts, and more.

There are four common types or categories of data visualization:

1. Comparison: This type of visualization is used to compare different data points, such as comparing sales figures between different months or comparing the performance of different products.
2. Composition: Compositional visualizations show how the whole is divided into parts. Examples are a pie chart or a stacked bar chart, where each segment represents a proportion of the whole.
3. Distribution: Relationship visualizations depict relationships or correlations between variables. This can include scatter plots, network diagrams, or chord diagrams, which show how various elements relate to each other.
4. Relationship: Spatial visualizations make use of geographic information to represent data. An example is a map or heat map, which displays data based on geographic location or spatial relationships.

and There are several types of plots you can create using these libraries and which are as follows:

1. Bar Chart (Comparison)
   Bar charts are used to compare data across different categories or groups. They are suitable for visualizing categorical data and comparing values between different groups. There are two types of bar charts: vertical bar charts and horizontal bar charts.

- Vertical Bar Chart : Suitable for comparing data with multiple categories.

  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Vertical%20Bar%20Chart.png" /></div>

  Data Source: [Source](https://opendata.jabarprov.go.id/id/visualisasi/hutan-untuk-masa-depan)

- Horizontal Bar Chart : Ideal with big data between categories.
  Example:

  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Horizontal%20Bar%20Chart.png" /></div>

  Data Source: [Source](https://opendata.jabarprov.go.id/id/visualisasi/potret-permasalahan-remaja-di-jawa-barat)

2. Line Chart (Comparison)
   Line charts are used to show trends or changes over time. They are suitable for visualizing data that changes continuously or sequentially. There are two types of line charts: single line charts and multiple line charts.

- Single Line Chart : Suitable for visualizing a single data series over time.

  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Single%20Line%20Chart.png" /></div>

  Data Source: [Source](https://opendata.jabarprov.go.id/id/visualisasi/jabar-juara-swasembada-ayam-pedaging-nasional---jdvf-competition-2022)

- Multiple Line Chart : Ideal for comparing multiple data series over time.
  Example:

  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Multiple%20Line%20Chart.png" /></div>

  Data Source: [Source](https://opendata.jabarprov.go.id/id/visualisasi/penguatan-kinerja-keuangan-pemprov-jabar-melalui-optimalisasi-pajak-kendaraan-bermotor-pemprov-jawa-barat---jdvf-competition-2022)

3. Stacked Bar Chart (Comparison & Composition)
   Stacked bar charts are used to compare data across different categories while showing how individual parts make up a whole. They are suitable for visualizing categorical data and comparing values between different groups. Stacked bar charts can be used for both comparison and composition purposes.

   Example:

   <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Stacked%20Bar%20Chart.png" /></div>

   Data Source: [Source](https://opendata.jabarprov.go.id/id/visualisasi/visualisasi-desa-yang-mengalami-pencemaran-lingkungan-di-provinsi-jawa-barat-tahun-2020)

4. Stacked 100% Bar Chart (Comparison & Composition)
   Stacked 100% bar charts are similar to stacked bar charts but represent the data as percentages of the whole. They are suitable for visualizing the composition of data across different categories. Stacked 100% bar charts can be used for both comparison and composition purposes.

   Example:

   <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Stacked%20100%25%20Bar%20Chart.png" /></div>

   Data Source: [Source](https://ironic3d.com.au/categorical-charts/power-bi-100-stacked-bar-chart)

5. Pie Chart (Composition)
   Pie charts are used to show how individual parts make up a whole. They are suitable for visualizing the composition of data and comparing the proportions of different categories. Pie charts are ideal for displaying data with a small number of categories.

   Example:

   <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Pie%20Chart.png" /></div>

   Data Source: [Source](https://medium.com/@halilintarbasyeban/sekolah-data-pacmann-project-analisa-jumlah-kasus-balita-gizi-buruk-pada-provinsi-jawa-barat-tahun-1051eebc8360)

6. Tree Map Chart (Composition)
   Tree map charts are used to display hierarchical data as a set of nested rectangles. They are suitable for visualizing the composition of data and comparing the proportions of different categories. Tree map charts are ideal for displaying data with multiple levels of hierarchy.

   Example:

   <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Tree%20Map.png" /></div>

   Data Source: [Source](https://opendata.jabarprov.go.id/id/visualisasi/melihat-kesempatan-kerja-di-jawa-barat)

7. Scatter Plot (Relationship)
   Scatter plots are used to explore relationships between variables. They are suitable for visualizing the correlation between two continuous variables. Scatter plots can help identify patterns, trends, and outliers in the data.

   Example:

   <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Scatter%20Plot.png" /></div>

   Data Source: [Source](https://opendata.jabarprov.go.id/id/visualisasi/ubi-jalar---komoditas-ekspor-unggulan-jawa-barat)

8. Spatial Chart (Relationship)
   Spatial charts are used to display data on maps or geographical regions. They are suitable for visualizing data that has a spatial component, such as locations, regions, or countries. Spatial charts can help analyze patterns and trends based on geographical data.

   Example:

   <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Spatial%20Chart.png" /></div>

   Data Source: [Source](https://opendata.jabarprov.go.id/id/visualisasi/west-java-through-the-lens-of-sdg-4-quality-education---jdvf-competition-2022)

## Data Visulization Using Matplotlib and Seaborn

Matplotlib and Seaborn are popular Python libraries for data visualization. Matplotlib is a versatile library that allows you to create a wide range of plots, including line plots, bar plots, scatter plots, and more. Seaborn is built on top of Matplotlib and provides a higher-level interface for creating attractive and informative statistical graphics. It offers a variety of built-in themes and color palettes to enhance the visual appeal of your plots.

### Matplotlib

- Used for Basic Graph Plotting: Matplotlib is used to create various types of graphs such as line charts, bar graphs, scatter plots, and more to easily visualize data.
- Works with Datasets and Arrays: Matplotlib works efficiently with datasets and arrays, allowing users to easily visualize data in various formats.
- Interacts with Pandas and Numpy: Matplotlib interacts well with libraries like Pandas and Numpy, commonly used in Exploratory Data Analysis. This enables users to easily explore and visualize data stored in data structures like DataFrames and arrays.
- Further Customization: Matplotlib is highly customizable, allowing users to control every aspect of their plots. This enables users to create visualizations tailored to their data analysis needs.

There are several types of plots you can create using Matplotlib, such as:

1. Line Chart :
   Line charts effectively display trends over time, ideal for continuous or sequential data like time series. With Matplotlib, customization options abound, allowing for tailored visualization.

Example:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Matplot%20Multi%20Line.png" /></div>

2. Bar Chart :
   Bar charts in Matplotlib are effective for comparing categories or showing discrete data. They're ideal for visualizing categorical variables or comparing different groups. Matplotlib provides extensive customization options for bar charts, allowing for tailored presentations.

Example:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Matplot%20Stacked%20Bar%20Chart.png" /></div>

3. Histogram :
   Histograms visually represent data distribution, aiding in understanding numerical data frequency. Matplotlib's customizable options enable tailored visualizations.

Example:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Matplot%20Histogram.png" /></div>

### Seaborn

- Primarily Used for Statistical Visualization: Seaborn is primarily used for statistical visualization and excels at creating complex visualizations with minimal code.
- Works with Entire Datasets: Unlike Matplotlib, Seaborn typically works with entire datasets rather than individual data points, making it efficient for exploring and visualizing large datasets.
- Organized and Functional: Seaborn is known for its organization and functionality, treating the entire dataset as a single unit and simplifying the process of creating intricate visualizations.
- Rich in Built-in Themes: Seaborn offers a wide range of built-in themes and styles, allowing users to customize the appearance of their plots effortlessly. It is commonly used for statistical analysis and visualization tasks.

There are several types of plots you can create using Seaborn, such as:

1. Line Chart :
   Seaborn offers seamless creation of line charts, perfect for depicting trends over time. Its simplicity and customization options make it a top choice for exploratory data analysis and visualization tasks.

Example:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Seaborn%20Multi%20Line.png" /></div>

2. Bar Chart :
   Seaborn simplifies the creation of bar charts, making them perfect for comparing categories or displaying discrete data. Its intuitive interface and customization options make it a preferred tool for exploratory data analysis and visualization tasks.

Example:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/Seaborn%20Multi%20Bar%20Chart.png" /></div>

## Cross Industry Standard Process for Data Mining (CRISP-DM)

Cross Industry Standard Process for Data Mining (CRISP-DM) is a widely used methodology for data mining projects. It provides a structured approach to data mining projects, guiding practitioners through the various stages of the project lifecycle. CRISP-DM consists of six phases:

1. Business Understanding: In this phase, the project objectives and requirements are defined, and the data mining goals are established. It involves understanding the business problem, identifying the data mining goals, and defining the project scope.
2. Data Understanding: In this phase, the data is collected, explored, and prepared for analysis. It involves understanding the data sources, exploring the data to identify patterns and relationships, and preparing the data for modeling.
3. Data Preparation: In this phase, the data is cleaned, transformed, and formatted for modeling. It involves cleaning the data, selecting relevant features, and creating new variables to improve the quality of the data.
4. Modeling: In this phase, the data is modeled using various data mining techniques to build predictive or descriptive models. It involves selecting the appropriate modeling techniques, building and evaluating the models, and selecting the best model for deployment.
5. Evaluation: In this phase, the models are evaluated to assess their performance and validity. It involves evaluating the models against the data mining goals, interpreting the results, and determining the next steps.
6. Deployment: In this phase, the models are deployed into production and integrated into the business processes. It involves deploying the models, monitoring their performance, and ensuring that they are used effectively to achieve the business objectives.

Example :

- CRISP-DM Process of Supermarket Sales Analysis

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics3/CRISP-DM%20EDA.png"/></div>
That was a example of CRISP-DM process. in Explaratary Data Analysis from Business Understanding.

Full CRISP-DM process can be seen in the file [CRISP-DM]().

## Responsible Analytics

Responsible Analytics is the practice of conducting data analysis in an ethical and responsible manner. It involves handling data responsibly, ensuring data privacy and security, and mitigating bias in data analysis. Responsible analytics is essential to build trust with stakeholders, comply with data privacy laws, and make informed decisions based on data insights. There are several key aspects of responsible analytics, including data privacy laws, best practices for responsible data handling, types of bias, and how to mitigate them. There some subtopics that are discussed in Responsible Analytics:

### Data Privacy Laws

Data privacy laws is a set of regulations that govern how organizations collect, store, process, and share personal data. These laws are designed to protect the privacy and security of individuals' personal information and ensure that organizations handle data responsibly. There are some common data privacy laws that are applicable in different regions and countries, such as:

- General Data Protection Regulation (GDPR) is a data privacy law that applies to the European Union (EU) and the European Economic Area (EEA). It regulates the processing of personal data and aims to protect the privacy and rights of individuals. The GDPR sets strict requirements for data protection, consent, and data subject rights. This law applies within the European Union and the European Economic Area. It focuses on the protection of personal data and the rights of individuals. It applies to organizations that process personal data of EU residents, regardless of the organization's location.
- The Family Educational Rights and Privacy Act (FERPA) is a data privacy law that applies to educational institutions in the United States. It protects the privacy of students' educational records and prohibits the disclosure of certain information without consent. FERPA sets guidelines for the collection, use, and disclosure of student data. This law is applicable in the United States.
- Health Insurance Portability and Accountability Act (HIPAA): HIPAA is a data privacy law that applies to healthcare organizations in the United States. It protects the privacy and security of individuals' health information and sets standards for the use and disclosure of protected health information. This law is applicable in the United States.
- Institutional Review Board (IRB) Regulations: IRB regulations are guidelines that govern the ethical conduct of research involving human subjects. They ensure that research studies involving human participants are conducted ethically and protect the rights and welfare of participants. This law is applicable in the United States.
- PCI Data Security Standard (PCI DSS): PCI DSS is a data privacy law that applies to organizations that process payment card transactions. It sets security standards for protecting cardholder data and aims to prevent data breaches and fraud. This law is applicable in the United States.

### Best Practices for Responsible Data Handling

Responsible data handling is the practice of managing data in an ethical and responsible manner. It involves safeguarding data privacy, security, and integrity to protect individuals' personal information and ensure data accuracy and reliability. There are several best practices that organizations can follow to handle data responsibly:

- Methods of Handling Personally Identifiable Information (PII): Organizations should implement data protection measures to safeguard personally identifiable information (PII) from unauthorized access, use, or disclosure. This includes encrypting sensitive data, restricting access to authorized personnel, and implementing data security controls.
- Securing Data: Organizations should secure data by implementing encryption, access controls, and monitoring mechanisms to protect data from unauthorized access, data breaches, and cyber threats. This helps ensure the confidentiality, integrity, and availability of data.
- Protecting Anonymity: Organizations should anonymize data to protect the privacy and anonymity of individuals. This involves removing or encrypting personally identifiable information (PII) from datasets to prevent the identification of individuals. Anonymizing data helps reduce the risk of data re-identification and unauthorized disclosure.
- Importance of Anonymizing Data: Anonymizing data is crucial to protect the privacy and confidentiality of individuals' personal information. It helps organizations comply with data privacy laws, prevent data breaches, and build trust with customers. Anonymizing data also reduces the risk of data misuse and unauthorized access.
- Trade-offs When Balancing Interpretability and Accuracy: Organizations should balance interpretability and accuracy when handling data to ensure that data analysis is meaningful and reliable. This involves considering the trade-offs between model complexity, interpretability, and accuracy to make informed decisions based on data insights.
- Shortcomings of Making Population-Level Generalizations with Limited Sample Data: Organizations should be cautious when making population-level generalizations with limited sample data. Small sample sizes may not be representative of the entire population, leading to biased or inaccurate conclusions. It is essential to consider the limitations of sample data and validate findings with additional data sources.

### Type of Bias and How to Mitigate Them

Bias in data analysis refers to systematic errors or distortions in data that lead to inaccurate or misleading conclusions. There are several types of bias that can occur in data analysis, including confirmation bias, human cognitive bias, motivational bias, and sampling bias. To mitigate bias in data analysis, data analysts should be aware of these biases and take steps to reduce their impact. Some ways to mitigate bias in data analysis include:

- Confirmation Bias: Confirmation bias is the tendency to search for, interpret, or remember information that confirms one's preconceptions or beliefs. To mitigate confirmation bias, data analysts should seek diverse perspectives, challenge assumptions, and consider alternative explanations to avoid bias in data analysis. Example: A data analyst may selectively choose data that supports a particular hypothesis while ignoring contradictory evidence, leading to biased conclusions.
- Human Cognitive Bias: Human cognitive bias refers to the systematic errors in judgment or decision-making that occur due to cognitive limitations or mental shortcuts. To mitigate human cognitive bias, data analysts should use data-driven decision-making, rely on evidence-based reasoning, and seek feedback from peers to reduce bias in data analysis. Example: A data analyst may rely on intuition or gut feeling rather than data-driven analysis when making decisions, leading to biased conclusions.
- Motivational Bias: Motivational bias is the tendency to interpret data in a way that aligns with one's interests, goals, or motivations. To mitigate motivational bias, data analysts should maintain objectivity, consider multiple viewpoints, and disclose potential conflicts of interest to ensure unbiased data analysis. Example: A data analyst may manipulate data or results to support a specific agenda or outcome, leading to biased conclusions.
- Sampling Bias: Sampling bias occurs when the sample data used for analysis is not representative of the entire population, leading to biased or inaccurate conclusions. To mitigate sampling bias, data analysts should use random sampling methods, ensure sample representativeness, and validate findings with additional data sources to reduce bias in data analysis. Example: A data analyst may collect data from a non-random or biased sample, leading to skewed or misleading results that do not reflect the population.

- How to Select Visualizations/Data Representations to Avoid Bias:

  - Use appropriate visualizations that accurately represent the data and avoid distorting or misinterpreting information.
  - Choose visualizations that are clear, concise, and easy to understand to communicate data effectively.
  - Consider the audience and purpose of the visualization to select the most suitable representation for the data.
  - Use multiple visualizations to present different perspectives or comparisons to provide a comprehensive view of the data.
  - Validate visualizations with statistical analysis or data modeling to ensure accuracy and reliability in data analysis.

## End Notes

The last part of the Learn Python for Data Analyst series focused on data analytics and visualization, responsible analytics, and the Cross Industry Standard Process for Data Mining (CRISP-DM) methodology. Data analytics and visualization play a crucial role in extracting insights and patterns from data, while responsible analytics ensures that data is handled ethically and responsibly. The CRISP-DM methodology provides a structured approach to data mining projects, guiding practitioners through the various stages of the project lifecycle. By following best practices for responsible data handling, mitigating bias in data analysis, and selecting appropriate visualizations, data analysts can conduct data analysis effectively and make informed decisions based on data insights. I hope you found this series helpful and informative. Thank you for reading!
