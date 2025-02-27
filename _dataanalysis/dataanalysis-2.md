---
title: "Indeed Jobs Web Scraping and Analysis"
excerpt: "In this project I scraped data science job descriptions from Indeed website. Asking the right questions and analyzing the scraped data allowed finding relevant insights. <br/>


<img src='/images/da2_word_cloud.png'>"

collection: dataanalysis
---

- *Scraped over 1000 job descriptions from Indeed web pages*
- *Visualized the companies and the locations with the highest number of job listings*
- *Calculated the minim and maxim average salary*
- *Engineered features from the text of each job description to quantify the value companies put on specific tools, platforms, skills and data science roles*
- *Created a word cloud highlighting the most frequently used words in job descriptions*
<br/>

[GitHub](https://github.com)



---
**Which are the companies with the highest number of job listings?**

Notice that Microsoft has the highest number of jobs, followed by Amazon and Zillow. There are 69 companies that posted only 1 job and 28 companies that listed 2 jobs. Most companies have between 1 and 10 jobs.



<img src='/images/da2_jobs_comp.png'>


---
**What is the frequency of words for specific tools and platforms, skills, and roles?**

Tableau is the top data analytics tool while Azure is the preferred cloud computing platform. The roles as data scientists are in more demand than data analysts. Other roles like data engineer or machine learning engineer are less present. Most position types are for senior level, followed by intern and entry level.



<img src='/images/da2_tools_roles.png'>


---
**What is the count of word frequency in job descriptions?**

A count of all words that occur in job descriptions and job titles highlight the importance of specific words. As Word Cloud shows, the most frequent word is **data**, followed by **machine learning**, **experience**, **engineering** and **customer**.




<img src='/images/da2_word_cloud.png'>


---
**What is the average salary?**

Calculating the average salary included checking the formatting of salary values then defining a function to format, calculate and split salary in minim and maxim values. 
The results showed that the **minim average** salary is **115,887** a year and the **maxim average** is **159,665** a year.





