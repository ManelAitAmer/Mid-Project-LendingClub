# Mid-Project-LendingClub

![LC-Logo-Official-min](https://github.com/ManelAitAmer/Mid-Project-LendingClub/assets/160795377/317be1d3-b413-481a-816c-6a6a6bc8f252)

## Definition of a LendingClub :pushpin::

A ***Lending Club*** is a platform that allows individuals to lend to other individuals.This could be for various purposes such as debt consolidation, home improvement, education, or small business funding.

They provide an alternative to traditional banking channels by leveraging technology to streamline the lending process and offer potentially better rates for both borrowers and investors.

## DATABASE:

The Database is from Kaggle : (https://www.kaggle.com/datasets/joebeachcapital/lending-club/data).

This data set represents 10,000 thousands of loans made through the Lending Club platform , with 55 variables. 

To make this date more cleare and studiable , I cleaned it by : 

- Dropping Nans :wastebasket: .
- Checking duplicates and spaces :paperclips:.
- Replacing some information to make the data more clear (will help for visualization) :open_book:.

The correlation Matrix-Heatmap , helped for cleaning the data.

**First Correlation Matrix-Heatmap Plot:**

<img width="1000" alt="Screenshot 2024-06-08 at 08 26 49" src="https://github.com/ManelAitAmer/Mid-Project-LendingClub/assets/160795377/26a8011d-521a-4f16-bcc1-ac8e43f26f9b">

**Final Correlation Matrix-Heatmap Plot:**

<img width="1005" alt="Screenshot 2024-06-08 at 08 34 49" src="https://github.com/ManelAitAmer/Mid-Project-LendingClub/assets/160795377/78cf60c8-046e-4421-92cc-bf42d1ed4923">

Data passed from 55 columns to 29 columns.

## Data Vizualization :bar_chart: :

For Data Vizualization , we will Use Histograms and Boxplots with and without outliers , but I will only put here we will only see the  without outliers; KDE plots , Frequency counts , violin plots :

<img width="1011" alt="Screenshot 2024-06-08 at 08 55 20" src="https://github.com/ManelAitAmer/Mid-Project-LendingClub/assets/160795377/e30e15ab-8b9c-4bc2-8c2b-00a1888ce82b">

<img width="998" alt="Screenshot 2024-06-08 at 08 56 11" src="https://github.com/ManelAitAmer/Mid-Project-LendingClub/assets/160795377/624694fc-f5ab-4bb3-b110-e72819ed9e29">

<img width="1000" alt="Screenshot 2024-06-08 at 08 51 59" src="https://github.com/ManelAitAmer/Mid-Project-LendingClub/assets/160795377/14ccad99-2431-45cd-93d6-572f4b7cb812">

<img width="487" alt="Screenshot 2024-06-08 at 08 53 02" src="https://github.com/ManelAitAmer/Mid-Project-LendingClub/assets/160795377/d4fd4ed2-e0a3-419d-8c74-7be1f6556325">

<img width="479" alt="Screenshot 2024-06-08 at 08 53 42" src="https://github.com/ManelAitAmer/Mid-Project-LendingClub/assets/160795377/c13d5014-ddd8-4782-88f4-852115169bd1">



This plot is used to visualize the distribution of **loan_amount** within the **loan_data** dataset.

The histogram shows the frequency of loan amounts in different bins. This can help in understanding the central tendency, spread, and shape of the loan amount distribution.

<img width="718" alt="Screenshot 2024-06-08 at 09 02 09" src="https://github.com/ManelAitAmer/Mid-Project-LendingClub/assets/160795377/a58e9e8a-66b0-4cd9-8e8c-3e029f758911">
