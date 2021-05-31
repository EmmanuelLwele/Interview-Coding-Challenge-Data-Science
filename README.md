# Interview-Coding-Challenge-Data-Science
Interview Coding Challenge Data Science Step 1 of the Data Scientist Interview process. Follow the instructions below to complete this portion of the interview. Please note, although we do not set a time limit for this challenge, we recommend completing it as soon as possible as we evaluate candidates on a first come, first serve basis... If you have any questions, please feel free to email support@TheZig.io. We will do our best to clarify any issues you come across.  Prerequisites:  A Text Editor - We recommend Visual Studio Code for the ClientSide code, its lightweight, powerful and Free! (https://code.visualstudio.com/) SQL Server Management Studio (https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017) R - Software Environment for statitistal computing and graphics. You can download R at the mirrors listed here (https://cran.r-project.org/mirrors.html) Azure - Microsoft's Cloud Computing platform. You can create an account without a credit card by using the Azure Pass available at this link (https://azure.microsoft.com/en-us/offers/azure-pass/) Git - For source control and committing your final solution to a new private repo (https://git-scm.com/downloads) a. If you're not very familiar with git commands, here's a helpful cheatsheet (https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)   'R' Challenge For each numbered section below, write R code and comments to solve the problem or to show your rationale. For sections that ask you to give outputs, provide outputs in separate files and name them with the section number and the word output "Section 1 - Output". Create a private repo and submit your modified R script along with any supporting files.  Load in the dataset from the accompanying file "account-defaults.csv"      This dataset contains information about loan accounts that either went delinquent or stayed current on payments within the loan's first year. FirstYearDelinquency is the outcome variable, all others are predictors. The objective of modeling with this dataset is to be able to predict the probability that new accounts will become delinquent; it is primarily valuable to understand lower-risk accounts versus higher-risk accounts (and not just to predict 'yes' or 'no' for new accounts).     FirstYearDelinquency - indicates whether the loan went delinquent within the first year of the loan's life (values of 1)     AgeOldestIdentityRecord - number of months since the first record was reported by a national credit source     AgeOldestAccount - number of months since the oldest account was opened     AgeNewestAutoAccount - number of months since the most recent auto loan or lease account was opened     TotalInquiries - total number of credit inquiries on record     AvgAgeAutoAccounts - average number of months since auto loan or lease accounts were opened     TotalAutoAccountsNeverDelinquent - total number of auto loan or lease accounts that were never delinquent     WorstDelinquency - worst status of days-delinquent on an account in the first 12 months of an account's life; values of '400' indicate '400 or greater'     HasInquiryTelecomm - indicates whether one or more telecommunications credit inquires are on record within the last 12 months (values of 1)    Perform an exploratory data analysis on the accounts data      In your analysis include summary statistics and visualizations of the distributions and relationships.   Build one or more predictive model(s) on the accounts data using regression techniques      Identify the strongest predictor variables and provide interpretations.     Identify and explain issues with the model(s) such as collinearity, etc.     Calculate predictions and show model performance on out-of-sample data.     Summarize out-of-sample data in tiers from highest-risk to lowest-risk.    Split up the dataset by the WorstDelinquency variable.      For each subset, run a simple regression of FirstYearDelinquency ~ TotalInquiries.     Extract the predictor's coefficient and p-value from each model.     Store the  in a list where the names of the list correspond to the values of WorstDelinquency.    Load in the dataset from the accompanying file "vehicle-depreciation.csv".      The dataset contains information about vehicles that our company purchases at auction, sells to customers, repossess from defaulted accounts, and finally re-sell at auction to recover some of our losses.     Perform an analysis and/or build a predictive model that provides a method to estimate the depreciation of vehicle worth (from auction purchase to auction sale). Use whatever techniques you want to provide insight into the dataset and walk us through your results - this is your chance to show off your analytical and storytelling skills!     CustomerGrade - the credit risk grade of the customer     AuctionPurchaseDate - the date that the vehicle was purchased at auction     AuctionPurchaseAmount - the dollar amount spent purchasing the vehicle at auction     AuctionSaleDate - the date that the vehicle was sold at auction     AuctionSaleAmount - the dollar amount received for selling the vehicle at auction     VehicleType - the high-level class of the vehicle     Year - the year of the vehicle     Make - the make of the vehicle     Model - the model of the vehicle     Trim - the trim of the vehicle     BodyType - the body style of the vehicle     AuctionPurchaseOdometer - the odometer value of the vehicle at the time of purchase at the auction     AutomaticTransmission - indicates (with value of 1) whether the vehicle has an automatic transmission     DriveType - the drivetrain type of the vehicle
