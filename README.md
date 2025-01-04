A/B Testing Project: StreamSmart and VibeFest
Overview

This project involves the application of A/B testing to evaluate marketing strategies and pricing decisions for two distinct cases:

    VibeFest: A marketing campaign for a new music and arts festival in New York City.
    StreamSmart: A subscription-based video streaming service evaluating the impact of different price increase strategies on customer retention.

The project applies statistical methods and hypothesis testing to analyze user behavior and determine optimal strategies.
Objectives

    To evaluate the effectiveness of two advertisements (Ad A vs. Ad B) for VibeFest in driving user engagement and ticket purchases.
    To assess the impact of a $1 vs. $2 price increase on subscription cancellations for StreamSmart.
    To recommend actionable insights based on statistical analyses.

Datasets

    StreamSmart.xlsx: Contains customer cancellation data segmented by experimental conditions ($1 or $2 price increase) and months (April and May).
        Columns:
            Condition: Pricing strategy applied ($1 or $2 increase).
            April_Cancellation: Indicates cancellation status for April (1 = canceled, 0 = not canceled).
            May_Cancellation: Indicates cancellation status for May (1 = canceled, 0 = not canceled).

Analysis Process
VibeFest A/B Test

    Hypothesis Formation:
        Hypothesis (H1): Ad A will generate more clicks and ticket purchases than Ad B.
        Null Hypothesis (H0): No significant difference between Ad A and Ad B.

    Independent and Dependent Variables:
        Independent Variable: Advertisement type (Ad A or Ad B).
        Dependent Variables: Click-through rate (CTR) and ticket purchase rate.

    Execution:
        Ads were shown to a random sample of 1000 Instagram users.
        Metrics such as clicks and purchases were tracked using Instagram’s analytics.

    Statistical Analysis:
        Chi-square test and two-proportion Z-test were used to evaluate significant differences.

StreamSmart A/B Test

    Hypothesis Formation:
        Hypothesis (H1): A $1 price increase will result in fewer cancellations compared to a $2 price increase.
        Null Hypothesis (H0): No significant difference in cancellations between the $1 and $2 price increase groups.

    Independent and Dependent Variables:
        Independent Variable: Price increase ($1 or $2).
        Dependent Variable: Cancellation rate.

    Data Cleaning:
        Checked for missing values and data type mismatches.
        Converted categorical variables to appropriate data types.
        Filtered out April cancellations to focus on May data.

    Statistical Analysis:
        Chi-square test was applied to compare cancellation rates across groups.

Key Findings

    VibeFest:
        Ad A outperformed Ad B in driving both clicks and ticket purchases.
        P-value for the difference was significant, supporting the use of Ad A for the larger campaign.

    StreamSmart:
        The $1 price increase resulted in significantly fewer cancellations in both April and May compared to the $2 increase.
        Recommendation: Implement the $1 price increase to minimize churn.

Deliverables

    Python Code:
        Assignment_2.ipynb: Jupyter Notebook containing Python code for data cleaning, visualization, and statistical analysis.
    Cleaned Dataset:
        Cleaned_StreamSmart.xlsx: Prepared dataset for analysis after filtering and cleaning.
    Reports:
        Answer_Assignment_2_Arafat.docx: Detailed answers and recommendations for the assignment.

Tools and Technologies

    Python: For data analysis and visualization.
        Libraries: pandas, numpy, matplotlib, scipy.
    Jupyter Notebook: For interactive analysis.
    Microsoft Excel: For dataset review and preprocessing.

Instructions for Use

    1. Clone the repository:
       git clone https://github.com/YourUsername/AB-Testing-StreamSmart-VibeFest.git
    2. Open the Jupyter Notebook:
       jupyter notebook Assignment_2.ipynb
    3. Follow the code to clean and analyze the datasets or use the provided cleaned dataset for your own analysis.

Acknowledgments

This project was completed as part of MKT 568 coursework at WPI Business School. Special thanks to the course instructors for her guidance. 
