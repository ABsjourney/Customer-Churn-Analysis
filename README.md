# Customer-Churn-Analysis
data analysis project visualizing customer retention and churn trends.
## Hello! 👋  
So this is kinda my first real deep dive into Data Analytics land. I honestly wanted to go past just throwing together charts and call it a day, and instead dig into the “why” underneath all those numbers. I started with a raw dataset and then transformed it into a kind of interactive dashboard, to expose the narrative for why customers stick around or decide to go.

## The “Aha!” Moments 💡  
When I was poking around the data I kept running into a couple of points that felt really clear:
- **The 24-Month Cliff:** around the 2-year moment there is this noticeable jump in churn. It seems like either loyalty mechanisms or the pricing approach loses some power there, so yeah that becomes a solid goal for future tuning  
- **Subscription Health:** I compared Basic vs Standard vs Premium, and that let me locate who is most exposed faster, instead of relying on guesses. It turned into more evidence based decisions than “feelings”

## My Workflow 🛠️  
To get the dashboard actually working I leaned on:
- **Power BI:** for cleaning, setting up the model, and assembling the final report  
- **DAX:** I tried out custom measures to estimate churn rates and compute averages, and wow that learning curve was not small at all!  
- **Data Source:** big thanks to the community on Kaggle for the [Customer Churn Dataset](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset)  

## See the Dashboard 📊  
I added a quick preview right below, so you can get the vibe without downloading anything.

![Dashboard Preview](churn%20analysis%20dashboard.png)
## Project File 📁
Feel free to download the full Power BI file to explore my data model and DAX measures:
[Download Project File](CHURN ANALYSIS DASHBOARD COMPLETE.pbix)
---
*Honestly I’m pretty proud of this being my first project. If you have thoughts , or tips on how to refine my DAX logic or the overall dashboard look, I’d really like to hear it.


