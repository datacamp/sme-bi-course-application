# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- Power BI / Tableau specific: We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise: Financial Data Analysis

#### Dataset
*ex-1-financial-transactions.csv*

#### Files

- **Initial**: *ex-1-initial.yxmd*
- **Solution**: *ex-1-sol.yxmd*

#### Learning Objective
Successfully prepare the data for analysis by converting a string into a date, removing null values, applying consistent letter casing and sorting the data.

#### Context
Before any type of analysis some data preparation should be made to avoid a situation where the posterior insights are made worthless (garbage in, garbage out concept).
The proper selection and cleansing of data is an essential to have good results in an analysis especially in a financial transaction context where meticulous data plays a vital role in generating high-impact insights.

#### Steps to be executed by the student
- Use the Datetime tool to convert the `transaction_date` field to a standard datetime format, naming it `transaction_made_at`. Make sure you specify the correct datetime format for `transaction_date`.
- Remove `transaction_date` field from the dataset using the Select tool.
- Identify and filter out null values in the `transaction_amount` field using the Filter tool.
- Convert the text in `transaction_status` field to upper case by applying the Data Cleansing tool.
- Utilize the Sort tool to arrange the data by `transaction_made_at` in reverse chronological order.

#### Exercise question:
What is the date shown in `formatted_timestamp` for the first record?
Answer: 2022-12-30

#### End goal:
*Add an image of the final visualization here.*


## 2nd VM Exercise: Content Engagement of a Streaming Service

#### Dataset
*ex-2-streaming-service-engagement.csv*

#### Files

- **Initial**: *ex-2-initial.yxmd*
- **Solution**: *ex-2-sol.yxmd*

#### Learning Objective
Successfully prepare the data for analysis by removing null values, removing punctuation, adding consistent formatting and sorting the data.

#### Context
To understand which content is generating more engagement to then base investment decisions, it's imperative to ensure the dataset is well-prepared.
Therefore, there is the need to have data filled in key columns and consistent formatting, creating the basis for an analysis with high-quality insights.

#### Steps to be executed by the student
- Identify and filter out null values in the `rating` field using the Filter tool.
- Remove unwanted characters such as punctuation and make the `genre` field lowercase.
- Utilize the Sort tool to arrange the data by descending `rating` and ascending `duration`.
   
#### Exercise question:
What is the name of the content with the highest rating and lowest duration?
Answer: *justo*

#### End goal:
*Add an image of the final visualization here.*