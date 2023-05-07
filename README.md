Download Link: https://assignmentchef.com/product/solved-homework-1-ie7275-data-mining-in-engineering
<br>
<strong>Note: </strong>Read the book chapter “R Graphics.pdf” posted on Blackboard. Practice example problems given in the book chapter.

<h1>Problem 1 (Forest Fires) [40 points]</h1>

The file forestfires.xlsx includes data from Cortez and Morais (2007). The output area was first transformed with a ln(<em>x</em>+1) function. Then, several data mining methods were applied. After fitting the models, the outputs were post‐processed with the inverse of the <em>ln</em>(<em>x</em>+1) transform. Four different input setups were used. The experiments were conducted using a 10‐fold (cross‐validation) Í 30 runs. Two regression metrics were measured: MAD and RMSE. A Gaussian support vector machine (SVM) fed with only 4 direct weather conditions (temp, RH, wind and rain) obtained the best MAD value: 12.71  0.01 (mean and confidence interval within 95% using a t‐student distribution). The best RMSE was attained by the naive mean predictor. An analysis to the regression error curve (REC) shows that the SVM model predicts more examples within a lower admitted error. In effect, the SVM model predicts better small fires, which are the majority. Number of instances and attributes are 517 and 13 respectively.




<strong>Attribute Information: </strong>

X          x‐axis spatial coordinate within the Montesinho park map: 1 to 9 <strong>Y</strong>   y‐axis spatial coordinate within the Montesinho park map: 2 to 9 month month of the year: ʹjanʹ to ʹdecʹ

<table width="418">

 <tbody>

  <tr>

   <td width="54">day</td>

   <td width="364">day of the week: ʹmonʹ to ʹsunʹ</td>

  </tr>

  <tr>

   <td width="54">FFMC</td>

   <td width="364">FFMC index from the FWI system: 18.7 to 96.20</td>

  </tr>

  <tr>

   <td width="54">DMC</td>

   <td width="364">DMC index from the FWI system: 1.1 to 291.3</td>

  </tr>

  <tr>

   <td width="54">DC</td>

   <td width="364">DC index from the FWI system: 7.9 to 860.6</td>

  </tr>

  <tr>

   <td width="54">ISI</td>

   <td width="364">ISI index from the FWI system: 0.0 to 56.10</td>

  </tr>

  <tr>

   <td width="54">temp</td>

   <td width="364">temperature in Celsius degrees: 2.2 to 33.30</td>

  </tr>

  <tr>

   <td width="54">RH</td>

   <td width="364">relative humidity in %: 15.0 to 100</td>

  </tr>

  <tr>

   <td width="54">wind</td>

   <td width="364">wind speed in km/h: 0.40 to 9.40</td>

  </tr>

  <tr>

   <td width="54">rain</td>

   <td width="364">outside rain in mm/m2 : 0.0 to 6.4</td>

  </tr>

  <tr>

   <td width="54">area</td>

   <td width="364">the burned area of the forest (in ha): 0.00 to 1090.84</td>

  </tr>

 </tbody>

</table>




First load the file forestfires.csv, next perform the following tasks for the data:

<ol>

 <li>Plot area temp, area vs. month, area vs. DC, area vs. RH for January through December combined in 1 graph. Hint: Place area on Y axis and use 2×2 matrix to place the plots adjacent to each other.</li>

 <li>Plot the histogram of wind speed (km/h).</li>

 <li>Compute the summery statistics (min, 1Q, mean, median, 3Q, max,) of part b?</li>

 <li>Add a density line to the histogram in part b.</li>

 <li>Plot the density function of each month of the 12 months, possibly on one plot. Use different colors in the graph to interpret your result clearly. [Hint: use qplot(geom=density)]</li>

 <li>Plot the scatter matrix for temp, RH, DC and DMC. How you can interpret the result in terms of correlation among these data.</li>

 <li>Create boxplot for wind, ISI and DC. Are there anomalies/outliers. Interpret your result.</li>

 <li>Create the histogram of DMC. Create the histogram of log of DMC. Compare the result and explain your answer.</li>

</ol>




<h1>Problem 2 (Tweeter Accounts) [40 points]</h1>

Twitter is a social news website. It can be viewed as a hybrid of email, instant messaging and sms messaging all rolled into one neat and simple package. Itʹs a new and easy way to discover the latest news related to subjects you care about.




This is the data set crawled on July, 2009. BlogCatalog is a social blog directory website. This contains the friendship network crawled. For easier understanding, all the contents and variables are organized in CSV file format.




First load the file M01_quasi_twitter.csv, next perform the following tasks:

<ol>

 <li>How are the data distributed for friend_count variable?</li>

 <li>Compute the summery statistics (min, 1Q, mean, median, 3Q, max) on friend_count?</li>

 <li>How are the data quality in friend_count variable? Interpret your answer</li>

 <li>Produce a 3D scatter plot with highlighting to impression the depth for variables below on csv dataset. created_at_year, education, age. Put the name of the scatter plot “3D scatter plot”.</li>

 <li>Consider 650, 1000,900,300 and 14900 tweeter accounts are in UK, Canada, India, Australia and US Plot the percentage Pie chart includes percentage amount and country name adjacent to it, and also plot 3D pie chart for those countries along with the percentage pie chart. Hint: Use C=(1, 2) matrix form to plot the charts together.</li>

 <li>Create kernel density plot of created_at_year variable and interpret the result.</li>

</ol>







<h1>Problem 3 (Insurance Claims) [20 points]</h1>

Consider that we need to rate a product based on four different aspects

Sustainability, Carbon footprint, weight and required power to be built. Those variables are gathered into raw_data.csv spreadsheet in columns A, B, C and D respectively.




First load the file raw_data.csv, next perform the following tasks:

<ol>

 <li>Normalize the data and create new dataset with normalized data and name it</li>

</ol>

Ndata.

<ol>

 <li>Create the boxplot of all the variables in their original form.</li>

 <li>Create boxplot of all the variables in their normalized form.</li>

 <li>Compare the result of part b and part c; interpret your answer.</li>

 <li>Prepare scatter plot of variables A and B. How correlated the data are in these variables. Interpret your answer.</li>

</ol>










<strong>Files Included in the Folder: </strong>

<strong>Homework 1.pdf R Graphics.pdf forestfires.csv M01_quasi_twitter.csv raw_data.csv </strong>