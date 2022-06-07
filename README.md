# Lending Club Case Study
> We are trying to determine the features that helps in identifying whether a future loan applicant will likely to default or not based on the data of existing customers.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Recommendations](#Recommendations)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In this case study we are provided with the data of customers who has taken loan from the firm.
- A lot of features regarding the customer and other aspects are provided as a dataset.
- The dataset is about the past customers, so it included the information whether the customer has completed his payment, or still paying, or defaulted in the loan payment.
- Our objective is to find what all features/variables are relevent in deciding whether a future applicant is likely to default, so that we can give the information about a future applicant to the investors.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- For the mean values for funded amount and dti is comparatively higher to the Charged off users than the fully paid users.
- From the above plots we see that the mean value of funded_amnt and dti for users with 'Charged Off' loan_status is significantly higher than Fully paid customers for home_ownership type as 'mortgage'. So we can suggest to reduce the loan amount of customers with home_ownership type as 'mortgage'.

## Recommendations
- Reduce the funded amnt for users with homeonwership as mortgage
- Better to deny loan if dti is high

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.13
- Pandas - version 1.3.5
- Matplotlib - version 3.2.2
- Seaborn - version 0.11.2
- Google Colab

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the lending club institution (https://www.lendingclub.com/)
- This project was based on the Exploratory Data Analysis module in ML EPGP program in Upgrad


## Contact
Created by [@ShenShaji] and [@aabhiiii]- feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->