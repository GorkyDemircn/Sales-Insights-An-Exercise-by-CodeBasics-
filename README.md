# Sales Insights An Exercise by CodeBasics
We are going to cleanse and visualize our data by using Microsoft Power BI as an exercise. In addition to that,  as a database, we will be using MySQL to analyze our data.

As a feedback for the youtube channel (codebasics), I have really enjoyed with the whole series which gave me a good insight to comprehend how data analysis works by using data science tools. So, this has been a good starting point to dive into data science.

<ol type = '1'>
   <li>
       <h4> To find out the total transaction of a company </h4> <p> Use this code : <code> Total Transaction = COUNTROWS('sales transactions') </code> </p> 
   </li>
 
  <li>
      <h4> To find out the revenue of a company </h4> <p> Use this code : <code> Revenue = SUM('sales transactions'[sales_amount]) </code> </p> 
   </li>
   
   <li>
      <h4> To see the revenue of a company in SQL by looking at the year 2020 </h4> <p> Use this code :
      <code> SELECT SUM(sales_amount) FROM transactions as trns INNER JOIN date as dt
             ON trns.order_date = dt.date
            WHERE dt.year = 2020) </code> </p> 
   </li>
   
   <li>
      <h4> To see the revenue of a company in SQL by looking at distinctive years </h4> <p> Use this code :
      <code>SELECT DISTINCT(year) FROM date </code> </p> 
   </li>
</ul>


<h2> To see the incomplete design and short demo, click the link below: </h2>

<ol type = "1">

<li>
    <p>
       <a href="https://user-images.githubusercontent.com/110297297/191347007-36945647-3e36-4c95-9162-5c77513844d2.png">First Glance</a>
   </p>
</li>

<li>

<p>
    <a href= "https://user-images.githubusercontent.com/110297297/190251453-0e4c7a6c-9812-415b-afc1-77c3cc9773dd.png"> List top 5s </a>  
</p>
</li>

<li>
<p>
   <a href= "https://user-images.githubusercontent.com/110297297/190251598-8473c05c-6432-4889-80a5-9a5e32662e78.png"> Revenue Trend  </a>
</p>
</li>


<li>
<p>
   <a href= "https://user-images.githubusercontent.com/110297297/190251598-8473c05c-6432-4889-80a5-9a5e32662e78.png"> Comparison betweeen customer type and markets  </a>
</p>
</li>




<li>
<p>
  <a href= "https://user-images.githubusercontent.com/110297297/190001961-0e0fd3f6-d3ed-4c11-8225-761cf50a9c10.mp4" > A short insight about data with a video </a>
</p>
</li>


</ol>






