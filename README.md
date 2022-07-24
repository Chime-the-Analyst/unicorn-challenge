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












