# Project Name:Unicorn Challenge

I decided to jump on this challenge by Maven Analytics to test out my data visualization skills. The goal is to analyze the dataset and draw insights.
## Tools Used
* **Microsoft Excel** : Data cleaning
* **Power BI** : Data visualization

## What's a Unicorn Company
A unicorn Company is a privately held startup company that has a valuation of over a billion dollars.

## Dataset

![image](https://user-images.githubusercontent.com/109159668/180643852-f38c7df6-f187-4feb-ab67-1ec0df79184a.png)

                                    Overview of dataset

## Data Cleaning Process
The valuation column contained alphanumeric values like $180B.The objective is to transform the values into numbers but to make that easier you have to remove the dollar sign, the mid function was used to remove the dollar sign

![image](https://user-images.githubusercontent.com/109159668/180643989-b974166a-5c4d-4ce9-90f0-2cb047da28e5.png)
  
    MID Function

![image](https://user-images.githubusercontent.com/109159668/180644006-11d27dca-a0d7-4415-af97-e98d05629c21.png)

    New Column

Then a nested if statement was used to change the letters to their corresponding numerical equivalent.

![image](https://user-images.githubusercontent.com/109159668/180644059-3221f76b-0293-4ea0-bab5-d38bcf757d6f.png)
    
    Nested IF

This process was also repeated on the funding column

![image](https://user-images.githubusercontent.com/109159668/180644092-7958c682-ccb4-4447-be93-af714a9e2197.png)

    New valuation column

![image](https://user-images.githubusercontent.com/109159668/180644124-d325463c-94f3-451a-acc1-3a8b7a487bf2.png)

    New funding column  

## Data transformation
The dataset was imported into power BI and I went ahead to transform it.The valuation and funding columns were changed to currency and that was that.

## Question that needed answers
* I wanted to know the total amount of funding and total valuation for the companies
* I wanted to know how funding companies has changed over the years
* I wanted to know how the valuation of companies have changed over the years
* I wanted to know the industry with the highest valuation and the industry with the highest funding
* I wanted to find the continent with the most industries

### Total amount of funding and Total valuation
The total amount of funding was $591.82bn while the total valuation was $3.71T

![image](https://user-images.githubusercontent.com/109159668/180644267-280a728a-a771-43fb-9efe-d3a465a59f67.png)

    Total valuation and funding

### How has companies funding changed over the years?
I noticed that companies were funded with around $5bn at most ,until 2010 where funding started to skyrocket and funding was at an all-time high in 2015 with over $100bn before it came back down in 2020.

![image](https://user-images.githubusercontent.com/109159668/180644310-3a90fc91-b702-4e9c-8efb-5fcd2618680f.png)

    Funding over the years

### How the valuation of companies has changed over the years?
The valuation of companies stayed at that $5bn range before increasing in year 2000 then skyrocketing in 2015 with companies reaching $600bn in valuation.

![image](https://user-images.githubusercontent.com/109159668/180644329-51eb43b6-6e24-42da-9303-564f549b3704.png)

    Valuation over the years

### Highest funding and Highest valuation
I wanted to know the industry with the highest valuation and the companies with the highest funding and check whether it's the most funded companies that turned out to be the most valuable.
The fintech industry had both the highest funding and the highest valuation. The fintech industry had a total funding of $108bn and its now valued at $882bn.

![image](https://user-images.githubusercontent.com/109159668/180644377-6b77050a-ea13-4338-a809-13852c130fdc.png)

    Funding by industry

![image](https://user-images.githubusercontent.com/109159668/180644390-548b7210-01ca-43f9-859b-4d100495fb8e.png)

    Valuation by industry

### The continent with the most industries
North America was the continent the most industries with a total of 558

![image](https://user-images.githubusercontent.com/109159668/180644428-55111816-95f8-4e05-ad42-f7b0be09634f.png)

    North Americas total industries

![image](https://user-images.githubusercontent.com/109159668/180644448-04bdd079-1339-4404-96ae-58e0d3c59f6f.png)

    World Map

### Full Dashboard

![image](https://user-images.githubusercontent.com/109159668/180644472-a2ff68a8-0e2e-4f1e-b442-2c5c7cce6dfe.png)

    First page

![image](https://user-images.githubusercontent.com/109159668/180644515-0424019c-2e75-462a-b009-33f119add784.png)


    Second page


