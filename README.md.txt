
Local Development Corporations Loans

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include loans data. Local development corporations are required to report information on the projects they support and how those approved projects are financed (either through grants, loans, or bonds). The dataset consists of loans data reported by Local Development Corporations beginning with fiscal years ending in 2011.


About The Dataset:
- This dataset contains 13,513 loans with 18 variables (columns) on each loan (rows), including loan amount, borrower rate (or interest rate), original loan amount, loan term completed, and many others.

The structure of your dataset:

The dataset contains data about the details of the various loans taken by The Local development corporations (Borrowers) from The Public authorities.
Each row in the dataset represents a loan, which is described by various attributes about the Borrower such as Original Loan Amount, Loan Purpose, and Amount Repaid. It also describes other parameters such as Loan Terms Completed, Interest Rate, etc.

The main features of interest in this dataset:

I'm interested in figuring out what features are best for **Predicting the Risk** for each loan.
 

The features in the dataset I think will help support my investigation into my features of interest:

The following are the important features that I'll use in this exploration:
1. Authority Name.
2. Loan Fund Sources
3. Original Loan Amount
4. Interest Rate
5. Loan Length
6. Amount Repaid
7. Loan Purpose
8. Loan Terms Completed
9. Jobs Planned
10. Jobs Created

Findings:

1- Distribution of Loan Fund Sources:
The most loan authorities are the Federal and the Not Profit ones.

2- Distribution of Recipient State:
Most of Recipients are from New York State.

3- What Are The Most Common purposes of Taking Loans?
We can notice that the most Common purposes of Taking Loans are:
1. Commercial Property Construction/Acquisition/Revitalization/Improvement.
2. Business Expansion/Startup
3. Equipment and Fixed Asset Acquisition

4- How Many Borrowers Didn't Repaid Their Loans?
The Borowers didn't repaid thier loan are (428), about 3.6% of the total recipients.

5- Distribution of Original Loan Amount:
There are outlier values.
After removing outlier values, The Distribution of Original Loan Amount is strongly Right Skewd.

6- Distribution of Interest Rate:
- The Interest Rate is almost normally distributed with mean/med=3.96/4.0.
- There are also spikes at higher interest rates at the low values (Less than 1).

7- Distribution of Loan Length:
After remiving the outlier values, Most of the loans in the dataset have a length below 60 years.

## Observations About The Dataset Features: 
- I selected the features whitch will help me Predicting the Risk for each loan.
- Most of features distributions were normal, except 'Original Loan Amount' and 'Loan Length' which have outlier values.

## Bivariate Exploration

- In this section, I'll investigate relationships between pairs of variables in my
data from the variables discussed in the previous section.

1- Does the Interest Rate Affected By The Original Loan Amount?
- We can notice that the Interest Rate Affected By The Original Loan Amount.
- The higher Original Loan Amount leads to higher Interest Rate.

2- Does the Original Loan Amount Related to the Loan Purpose?
- We can notice that the purposes with the highist amount of Loans are:
1. Land Acquisition/Development /Infrastructure Costs
2. Commercial Property Construction/Acquisition/Revitalization/Improvement.
3. Residential Property Construction/Acquisition/Rehabilitation/Improvement.

3- Does the Risk Status Affected by the Original Loan Amount?
- The Risk affected negatively by the Original Loan Amount.

4- Does the Risk Status Affected by the Interest Rate?
- We can notice that the Risk Status slightly affected by the Interest Rate.

5- Does the Risk Status Affected by the Loan Length?
- The Risk Status Affected Negativly by the Loan Length.
- The higher Loan Length leads to less Risk.

6- Does the Risk Status Affected by the Jobs Created?
- The higher of Jobs Created by the Borrower, the low Risk.

# Multivariate Exploration

- In this section, I'll Create plots of three variables to investigate my data even further.

1- Does the Risk Affected By The Original Loan Amount or Interest Rate?
- There is a relationship between Interest Rate and Loan Amount.
- Higher Loan Amount leads to Higher Interest Rate. and also leads to higher Risk.

- The last notice from this dataset:
The most Risk (unpaid loans), were in the lower sector of loan amount, and also in the lower loan length.

