Download Link: https://assignmentchef.com/product/solved-stat210-410-assessment2-aphid-body
<br>
In each assignment you will be able to earn up to 5 marks based on your engagement on the moodle Discussion forums from the topics associated with the given assignment. See the Assignment assessment criteria document for more details.

<h1>Question 2</h1>

The net reproductive rate (<em>R</em><sub>0</sub>) of an animal is defined as the total number of offspring that an individual can produce during its lifetime and can be calculated as follows:

<em>∞</em>

<em>R</em>0 = X(<em>l</em><em>xm</em><em>x</em>)

<em>x</em>=0

where <em>l<sub>x </sub></em>is the proportion of females surviving to each age and <em>m<sub>x </sub></em>is the average number of offspring produced at each age. Hence, if you had data on two different time-periods or ages you would calculate (<em>R</em><sub>0</sub>) as:

<em>R</em><sub>0 </sub>= (<em>l</em><sub>1</sub><em>m</em><sub>1</sub>) + (<em>l</em><sub>2</sub><em>m</em><sub>2</sub>)

The <em>aphid </em>data-set contains records of the number of eggs produced on three different days by each of 20 aphids.

<table width="270">

 <tbody>

  <tr>

   <td width="64">Variable</td>

   <td width="206">Description</td>

  </tr>

  <tr>

   <td width="64">ID</td>

   <td width="206">Individual aphid in the experiment</td>

  </tr>

  <tr>

   <td width="64">Day1</td>

   <td width="206">Number of eggs produced on Day 1</td>

  </tr>

  <tr>

   <td width="64">Day2</td>

   <td width="206">Number of eggs produced on Day 2</td>

  </tr>

  <tr>

   <td width="64">Day3</td>

   <td width="206">Number of eggs produced on Day 3</td>

  </tr>

 </tbody>

</table>

Note: <em>NA </em>indicates that the animal has died.

Using the <em>aphid </em>data-set:

<ul>

 <li>Create a function to calculate <em>R</em><sub>0 </sub>for the population.</li>

 <li>Estimate a boot-strapped standard error and 95% confidence interval of <em>R</em><sub>0 </sub>using 100,000 replicates.</li>

 <li>Provide a brief summary of your result as well as fully annotated code in your <em>R Script </em></li>

</ul>

<h1>Question 3</h1>

The <em>Body </em>dataset contains 21 body dimension measurements as well as age, weight, height, and gender on 507 individuals. The 247 men and 260 women were primarily individuals in their twenties and thirties that all reported to exercise on a regular basis.

<table width="425">

 <tbody>

  <tr>

   <td width="91">Variable</td>

   <td width="334">Description</td>

  </tr>

  <tr>

   <td width="91">BA_diam</td>

   <td width="334">Biacromial diameter</td>

  </tr>

  <tr>

   <td width="91">PB</td>

   <td width="334">Biliac diameter, or “pelvic breadth”</td>

  </tr>

  <tr>

   <td width="91">BI_diam</td>

   <td width="334">Bitrochanteric diameter</td>

  </tr>

  <tr>

   <td width="91">Chest_dep</td>

   <td width="334">Chest depth between spine and sternum at nipple level</td>

  </tr>

  <tr>

   <td width="91">Chest_diam</td>

   <td width="334">Chest diameter at nipple level, mid-expiration</td>

  </tr>

  <tr>

   <td width="91">Elbow_diam</td>

   <td width="334">Elbow diameter, sum of two elbows</td>

  </tr>

  <tr>

   <td width="91">Wrist_diam</td>

   <td width="334">Wrist diameter, sum of two wrists</td>

  </tr>

  <tr>

   <td width="91">Knee_diam</td>

   <td width="334">Knee diameter, sum of two knees</td>

  </tr>

  <tr>

   <td width="91">Ankle_diam</td>

   <td width="334">Ankle diameter, sum of two ankles</td>

  </tr>

  <tr>

   <td width="91">Shoulder_g</td>

   <td width="334">Shoulder girth over deltoid muscles</td>

  </tr>

  <tr>

   <td width="91">Chest_g</td>

   <td width="334">Chest girth</td>

  </tr>

  <tr>

   <td width="91">Waist_g</td>

   <td width="334">Waist girth, narrowest part of torso below the rib cage</td>

  </tr>

  <tr>

   <td width="91">Navel_g</td>

   <td width="334">Navel (or “Abdominal”) girth at umbilicus and iliac crest</td>

  </tr>

  <tr>

   <td width="91">Hip_g</td>

   <td width="334">Hip girth at level of bitrochanteric diameter</td>

  </tr>

  <tr>

   <td width="91">Thigh_g</td>

   <td width="334">Thigh girth below gluteal fold</td>

  </tr>

  <tr>

   <td width="91">Bicep_g</td>

   <td width="334">Bicep girth, flexed</td>

  </tr>

  <tr>

   <td width="91">Forearm_g</td>

   <td width="334">Forearm girth, extended, palm up</td>

  </tr>

  <tr>

   <td width="91">Knee_g</td>

   <td width="334">Knee girth over patella, slightly flexed position</td>

  </tr>

  <tr>

   <td width="91">Calf_g</td>

   <td width="334">Calf maximum girth</td>

  </tr>

  <tr>

   <td width="91">Ankle_g</td>

   <td width="334">Ankle minimum girth</td>

  </tr>

  <tr>

   <td width="91">Wrist_g</td>

   <td width="334">Wrist minimum girth</td>

  </tr>

  <tr>

   <td width="91">Age</td>

   <td width="334">Age (years)</td>

  </tr>

  <tr>

   <td width="91">Weight</td>

   <td width="334">Weight (kg)</td>

  </tr>

  <tr>

   <td width="91">Height</td>

   <td width="334">Height (cm)</td>

  </tr>

  <tr>

   <td width="91">Gender</td>

   <td width="334">Gender (1 – male, 0 – female)</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Produce some appropriate exploratory graphics of the <em>Body </em> Given the number of variables ensure that all graphics are easily readable and understandable. Provide a general summary of the trends seen in your graphics. Note: These graphics do not have to be exhaustive, just useful.</li>

 <li>Split the <em>Body </em>data-set into 50:50 testing:training data-sets. Use the validation set approach to implement forward <em>or </em>backward selection to select an optimal subset of predictors of <em>Weight</em>. Provide a summary of your results which includes (but is not limited to) appropriate tables, metrics and commentary on the relative accuracy of your results.</li>

 <li>Using the testing and training data-sets created in (b) use ridge <em>or </em>lasso regression to constrain or regularise the predictors of <em>Weight</em>. You should employ cross-validation to tune the value of <em>λ </em>during the training phase of your model. Provide a summary of your results which includes (but is not limited to) appropriate tables, metrics and commentary on the relative accuracy of your results.</li>

</ul>