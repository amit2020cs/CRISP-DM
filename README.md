# CRISP-DM-on-the-Seatle-Airbnb-dataset
Data Scientist Nanodegree
## Business Understanding

Airbnb is a platform of accommodation which match the needs of staying and of lending.  
Their main source of income is **fee for host**. Basically, as the number of transactions between the host and the guest increases, their profit also increases.  
So, It is important to their business and I expect it to be one of their KPIs.


<img src="https://bmtoolbox.net/wp-content/uploads/2016/06/airbnb.jpg" width=700>

ref: https://bmtoolbox.net/stories/airbnb/  
## Project Motivation
Based on Cross-Industry Standard Process of Data Mining (CRISP-DM), Seatle Airbnb dataset is used which is initially hosted on kaggel platform. Three bisinuess questions were asked and answered:
* **How long is the period available for lending by rooms?**  
* **Is there a busy season?**  
* **Are there any trends of popular rooms?**  
## File description
* **CRISP-DM on the Seatle Airbnb dataset.ipynb**
* **Three csv file(calendar.csv,listing.csv,reviews.csv)**
## Requirements
* **SK Learn**
* **Pandas**
* **Numpy**
* **Matplotlib**
* **Seaborn**
## Result of the analysis
This notebook uses data from the Seattle area of Airbnb and has been analyzed to answer the following questions.
Here we summarize the answers to those questions.

* **How long is the period available for lending by rooms?**  
The histogram of maximum nights shows that there are two groups.    
One is a listing that can be used at spots such as the maximum number of nights within a week.  
The other is a listing that supports a wide range of stay from the super long-term stay of the maximum number of stays for three years or more and the minimum number of nights for around two days to the spot use. 


* **Is there a busy season?**   
**Yes**.  
Apart from the increase in the number of Airbnb users, there was definitely a timely increase in the number of reviews at the same time each year.  
It is thought that it is about one month around early September and overlaps with the summer vacation time. It is important that the number of properties that can be provided at this time exceeds demand.


* **Are there any trends of popular rooms?**  
I could not derive it from my analysis.  
However, I learned that the score improves by logarithmic transformation. I will find time in the future and try to improve.
