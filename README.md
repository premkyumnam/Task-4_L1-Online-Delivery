<html>
  <body>
    
  <h1>Task#4_Level#1: ONLINE DELIVERY ANALYSIS</h1>
    
  <h2>Projec Review: </h2>
In this project, I analyzed a restaurant dataset to identify food trends. The goal of this 4<sup>th</sup> task (Level 1) is to:

1. Determine the percentage of restaurants that offer online delivey. And
2. Compare the average ratings of restaurants with and without online delivery 

<h1>Tools & Technologies:</h1>

To achieve this, I used the following tools and technologies:

1. Python: Programming language
2. Pandas: For data analysis, cleaning, exploration, and manipulation.
3. NumPy: For efficient numerical computations.
4. Matplotlib: For data visualization, including plots, charts, and graphs.
5. Seaborn: For statistical data visualization, building on Matplotlib.
6. Jupyter Notebook(IDEs): As the primary environment for data processing and analysis.<br><br>
These tools enabled me to effectively extract insights and meaning from the data.</p>

<h1>Results:</h1>
<p>First,I tried to find out the total number of restaurants using <br> <em>"total_resutaurants=len(df)"</em><br><br> And then,  I got the total number of restaurants that do not offer online delivery i.e., 7091  and <br>the total number of restaurant that offer online delivery is 2451. <br>And tried to find out the percentage of restaurants that offer and do not offer online delivery.  This is the formula I am applying here: <br><br><br>

  <p>
  $$ \text{Online Delivery Percentage} = \left( \frac{\text{Online Delivery Counts}}{\text{Total No. of Restaurants}} \right) \times 100 $$
</p></br> 
<p>And the Python code is given below:<br></br>
<em>
  1. online_delivery_percentage = (online_delivery_counts / total_restaurants) * 100</em> </br>
  2. avg_rating_online = df[df["Has Online delivery"] == "Yes"]["Aggregate rating"].mean()</br>
  3. avg_rating_no_online = df[df["Has Online delivery"] == "No"]["Aggregate rating"].mean()</br>
</em>
</p>

  
Finally, I identified the required results of the 4<sup>th</sup> task(level 1):<br><br>

1. The percentage of restaurants that offer online is 25.69 and do not offer online delivery is 74.31 </b><br>
2. The average ratings with online delivery is 3.25 and the average ratings without online delivery is 2.46.<br></br>

This is the formula I am applying Here:
<p>
  $$ \text{Average Rating} = \frac{\text{Sum of all ratings}}{\text{Number of ratings}} $$
</p>

A huge thanks to Cognifyz Technologies for this amazing learning opportunity! Every step in this journey is helping me grow, and I'm excited for what's next.<br><br>

Explore the full project on LinkedIn and GitHub:<br>
https://www.linkedin.com/in/yumnam-premkumar-singh-6347a8145/<br>

<p>I hope this will be very helpful to new learners and students. <br>
And I'd love to hear your thoughts and feedback! <br>
Let's connect and explore more data-driven insights together. <br><br>
Thank you all!

  <b>(YUMNAM PREMKUMAR SINGH)</b>
</p>
</body>
</html>
