# Mart-Business-Analysis

## Introduction
I analyzed a dataset from codebasics.io about a business named Atiliq Mart. AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities: Surat, Ahmedabad, and Vadodara. They want to expand to other metros/Tier 1 cities in the next 2 years.
AtliQ Mart is currently facing a problem where a few key customers have not extended their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers daily basis so that they can respond swiftly to these issues.
## Tech Stack 
Excel, Power Query and Power Pivot
## Data Cleaning
After importing my data into power query, I checked for duplicates(found none),the validity of my data using column distribution, quality and profiling and removed columns not neccessary for my analysis. I also made sure my columns were in the right data type.
## Data Preprocessing
I noticed there was no column for Volume Fill Rate, in the Order Lines Table, so I created the column for Volume Fill Rate, which was Quantity Delivered/Quantity Ordered.
## Data Analysis & Visualizations
(https://github.com/chinazaoguejiofor-boop/Mart-Business-Analysis/blob/main/Atiliq%20Mart%20Dashboard.png)
Acclaimed Stores , Lotus Mart and CoolBlue have the lowest on time delivery rate, that is, longest On-time delivery, in essence, if they find a client who delivers at a shorter time, they won't hesistate to drop the contract with Atiliq Mart 

![uni-5]()
Elite Mart, Sorefoz Mart, info stores, Vijay Stores have the lowest  in-full delivery rate.
In essence, Atiliq Mart is on the verge of loosing Coolblue as a client due to the extremely poor delivery service which includes taking so long to deliver, as well as not delivering the full quantity.


![uni-6](https://user-images.githubusercontent.com/115374063/194787089-024473ee-8c68-419c-8cfa-13dd0ab59b3e.png)
Clients that Atiliq Mart works towards delivering orders in full are not always delivered on time, while Clients that are delivered to on-time, the rate at which orders are delivered in-full is below average

![uni-2](https://user-images.githubusercontent.com/115374063/194787200-50ecbfa4-bc52-4060-8fa6-abba401a0d9f.png)
Vadora has the poorest metric performance of the the 3 cities which shows where clients that will end their contracts with Atiliq Mart will come from

![uni-8](https://user-images.githubusercontent.com/115374063/194787311-29122679-a030-453e-ad55-60622c117560.png)
Most of the poor delivery service for Coolblue is found in Vadodara with better delivery service in full in Ahmedabad  

![uni-7](https://user-images.githubusercontent.com/115374063/194787415-890f8ce3-5db4-44b7-9417-be5e731aafa6.png)
Surat has the best Metric performance with the best delivery in August, but also the lowest Orders
![uni-3](https://user-images.githubusercontent.com/115374063/194787476-6836e99c-4119-430a-b959-95cb65ce3b37.png)
[view the dashboard here](https://user-images.githubusercontent.com/115374063/194786711-e7901387-5943-474f-a11a-2a211bc9ead6.png)
