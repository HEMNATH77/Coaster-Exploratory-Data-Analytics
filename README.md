# Coaster-Exploratory-Data-Analytics

<h2>Introduction</h2>
<p>Coaster Exploratory Data Analysis (EDA) is a process used to investigate and understand the patterns, relationships, and trends within a dataset related to roller coasters. This analysis typically involves summarizing key statistics, visualizing data through plots and graphs, and identifying any anomalies or interesting patterns. The goal is to gain insights into aspects such as coaster speed, height, type, and popularity, which can inform further analysis or decision-making in areas like theme park design, safety improvements, or marketing strategies.</p>

<h2>Process for Visualisations</h2>
<ol><h3>1. Importing the Dataset and Python Libraries</h3>
    <h3>2. Data Preparation</h3>
    <h3>3. Data Cleaning</h3>
    <h3>4. Data Visualisations</h3>
    <ol><h4>Bar Graph</h4>
    <h4>Histogram</h4>
    <h4>Line Graph</h4>
    <h4>Scatter Plot</h4></ol>
    <h3>5. Use of Seaborn </h3></ol>

<h2>Importing the Dataset and Python Libraries</h2>
<p> Import the Python Libraries Such as Pandas , Numpy , Matplotlib and Seaborn in Jupyter Notebook. Download the Dataset from the Kaggle and Import it as a Data Frame in the Jupyter Notebook</p>
<img src="https://github.com/user-attachments/assets/4997799c-2fe8-477f-8544-0ba6a6250a12">  
<h2>Data Preparation </h2>
<p> From the importing Dataset , Look out the columns and Data. Take the necessary Data that you want to analyse for visualisation.</p>
<img src="https://github.com/user-attachments/assets/3349dc62-3062-4506-a59f-bf2e2f7143a1">
<h2>Data Cleaning</h2>
<p>In Data Cleaning, Clean the dataset with the duplicate values. These duplicate values can disturb the visualisation process. Renaming the columns with our interest and neglecting the null values in the dataset</p>
<img src="https://github.com/user-attachments/assets/4048d541-742d-4026-a7ac-221784d2ec89">
<h2>Data Visualisation</h2>
<p> As it is our first project we have going to visualise the started year ,Speed and Height columns with some visualization plots. </p>
<h3>1.Bar Graph</h3>
<p>In this visualization, we utilized the Matplotlib library to plot data related to the start year of various entities. By representing the start year data visually, we aimed to uncover trends, patterns, and distributions over time, providing a clear and insightful way to understand the temporal aspects of the dataset. This approach helps in easily identifying any significant periods, spikes, or gaps in the data, enhancing our overall analysis and interpretation.</p>
<img src="https://github.com/user-attachments/assets/c71a4d0f-0b3f-4f66-8880-a137bcbe49c9">

<h3>2.Histogram</h3>
<p> We analyzed the height data by creating a histogram using the Matplotlib library. The histogram provides a clear representation of the distribution of heights, allowing us to observe how frequently different height ranges occur within the dataset. This approach helps in identifying common height intervals, detecting any skewness or outliers, and understanding the overall spread of the data, making it a valuable tool for our exploratory analysis.</p>
<img src="https://github.com/user-attachments/assets/f78437dc-ec97-4b7f-96d8-475e0888275c">

<h3>3.Line Graph</h3>
<p>Here ., we focused on the speed data and represented it using a line graph created with the Matplotlib library. By plotting the speed data over time or across different categories, the line graph effectively highlights trends, fluctuations, and patterns within the dataset. This method allows for a clear and continuous view of how speed varies, making it easier to identify any significant changes or relationships within the data, enhancing our overall understanding and analysis.</p>
<img src="https://github.com/user-attachments/assets/b0905a90-843f-48d8-8155-b426f74f74fb">

<h3>4.Scatter Plot</h3>
<p>We utilized the Matplotlib library to create a scatter plot that represents the relationship between height data and speed data. By plotting each data point with height on the x-axis and speed on the y-axis, the scatter plot effectively reveals any correlations, trends, or clusters between these two variables. This visualization allows us to visually assess how speed varies with height, helping to identify any potential patterns, outliers, or relationships that might be present in the dataset, thereby deepening our analysis.</p>
<img src="https://github.com/user-attachments/assets/972b16bb-869b-4c7f-a52c-d5a9d021d403">

<h3>5.Scatter plot using seaborn </h3>
<p> In this visualization, we utilized Seaborn to create a scatter plot that represents the latitude and longitude data, with each point colored by the year started. By plotting latitude on the x-axis and longitude on the y-axis, the scatter plot reveals the geographic distribution of the data over time. The color coding based on the year started allows us to observe how locations have changed or spread over different time periods, providing valuable insights into temporal and spatial trends within the dataset. This visualization helps in understanding both the geographic and temporal dimensions of the data simultaneously.</p>
<img src="https://github.com/user-attachments/assets/853816ee-4582-435d-83a7-0f2bd5b8de85">

<h2>Conclusion</h2>
<p> The coaster exploratory data analysis provided valuable insights into the key characteristics and trends within the dataset, such as coaster heights, speeds, and geographic locations. Through various visualizations, including histograms, scatter plots, and line graphs, we identified patterns, correlations, and distributions that help us better understand the factors influencing roller coaster design and performance over time. This analysis also highlighted any outliers or anomalies that may warrant further investigation. Overall, the exploratory data analysis serves as a foundation for deeper analysis, guiding decisions related to coaster safety, design improvements, and market trends.</p>



