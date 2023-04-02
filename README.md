# Case-Study-A-Fund-Raising-Net-Return-Prediction-Model

# Healthcare for All - Donor Analysis

## Background and Objectives

"Healthcare for All" is a not-for-profit organization that provides financial help to people who are not able to afford healthcare. They raise funds through donations from all across the country and have an in-house database of over 13 million donors. One of their most efficient channels for a long period of time has been direct mails. However, for the last couple of years, they have seen a decline in the donations through this medium.

As an analyst working for "Healthcare for All," you will analyze the results of one of their recent direct mail fundraising appeals and develop a model that will help them maximize the net revenue generated from future renewal mailings to Lapsed donors.

## Population

The population for this analysis will be Lapsed donors who received the June 1997 renewal mailing. The analysis file includes all 191,779 Lapsed donors who received the mailing, with responders to the mailing marked with a flag in the TARGET_B field. The total dollar amount of each responder’s gift is in the TARGET_D field.

## Cost Matrix

The package cost (including the mail cost) is $0.68 per piece mailed.

## Analysis Time Frame and Reference Date

The mailing was sent out in June 2018. All information included in the file (excluding the giving history date fields) is reflective of behavior before 6/97. This date may be used as the reference date in generating the "number of months since" or "time since" or "elapsed time" variables. You can also find the reference date information in the filed ADATE_2. This filed contains the dates the promotion was mailed.

## Data Sources and Order & Type of the Variables in the Data Set

The dataset includes:

- 24 months of detailed promotion and giving history (covering the period 12 to 36 months before the mailing)
- A summary of the promotions sent to the donors over the most recent 12 months before the mailing (by definition, none of these donors responded to any of these promotions)
- Summary variables reflecting each donor's lifetime giving history (e.g., total # of donations before mailing, total $ amount of the donations, etc.)
- Overlay demographics, including a mix of household and area level data
- All other available data from the database (e.g., date of first gift, state, origin source, etc.)

## Instructions

We will be working with a limited version of this dataset this week, but it pays to think on how you would structure this problem in advance.

For this week, you will find all the necessary files as well as the tasks list in Case Study 1 repository on GitHub.

You will be guided through this exercise in class.

## Description for the Data in file1.xlsx, file2.xlsx, file3.xlsx, and file4.xlsx

| Variable | Description |
|----------|-------------|
| CONTROLN | Control number (unique record identifier) |
| STATE    | State abbreviation (a nominal/symbolic field) |
| HV1      | Median Home Value in hundreds |
| IC1      | Median Household Income in hundreds |
| IC2      | Median Family Income in hundreds |
| IC3      | Average Household Income in hundreds |
| IC4      | Average Family Income in hundreds |
| HVP1     | Percent Home Value >= $200,000 |
| IC5      | Per Capita Income |
| POBC1    | Percent Foreign Born |
| POBC2    | Percent Born in State of Residence |
| AVGGIFT  | Average dollar amount of gifts to date |

## Description for the data in vlookup_table.csv


| Variable | Description |
|----------|-------------|
| TCODE    | Donor title code)  |
| STATE    | State abbreviation |
| DOB      | Date of Birth                       |
| DOMAIN   | Represents city level, socio economic status |
| GENDER   | Gender of the donor |
| CONTROLN | Control number (unique record identifier) |
| TARGET_D | Donation Amount (in $)|
