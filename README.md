**Dashboard and Insights - Eurovision 1975-2019**

Upcoming 2023 Eurovision Song Contest inspired me to **gather relevant data** and **build a dashboard** that answers following quations: 
* Who has won **the most number of times**?
* Which **song and artist are the top** of all the times?
* How did introducing **free choice in terms of language** of performance increased **English share**, when it happened and how does the **trend look** now?
* Does songs in **english tend to win** or just the opposite? 
* Do **jury and viewers always agree**?
* Does **geografical and cultural closeness** influence the voting? If so, **who is more biased - jury or viewers**? 

These and many more quations can be answered based on my interactive dashboard. On the last page you can find some **facts and my conclusions** (some answers to above quations - spoiler 😉) that I came to while using this dashboard.

During process of designing and building this dashboard I tackled **some challenges and learned new features of Power BI** (and have a lot of fun as well 😊). 

**Technologies used**:
* Power BI Desktop
* Power Query

Challenges I encountered:
* Differences in names of countries between tables - I found out about it because it resulted in Blank() fields -> Solution: Standardising the names.
* Two columns in fact table was logically related to one filed in dimension table -> Solution:  Inactive relationsships and function USERELATIONSHIP().
* Problem with calculation sum of points received and given for one country -> Solution: Creating new table (using function SUMMARIZE) and and creating new key out of countries and year.


![image](https://user-images.githubusercontent.com/102869680/224977119-d7c8a5a1-7d5c-461f-85f5-97dda7b7ed61.png)
![image](https://user-images.githubusercontent.com/102869680/224977203-7ada0349-23f8-4e0d-87fe-7d612b5bb0c3.png)
![image](https://user-images.githubusercontent.com/102869680/224977275-6a9158aa-4cf4-4455-968a-f9ab302d42c3.png)
![image](https://user-images.githubusercontent.com/102869680/224977344-df49ef1a-1c88-4098-8419-def23e1ff2d6.png)
