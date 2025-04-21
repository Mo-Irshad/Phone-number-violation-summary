# Phone-number-violation-summary
This project is to classify customers phone numbers entered in different counters of outlets
This python file is made up to read the sample data file given because the code contain cleaning part of the data
The data is in the raw format that it just as dowloaded from the software so first in the code there will be some removal part of the rows and clomns

Sample.csv is the raw data
violation_phone_summary.xlsx is the output file

Use of this report automation:
This is used to understand how many customers are giving theri number and use of customer care number.
As this business give loyalty points to the customers, miss use of this can happen, The billers can give their number to theft the loyalty points, in order to prevent this daily the number entered is monitered.
Two sheets are created one to understand the summary and other two detect which customer is classified on which, a remarks column is given to sort them out
This code accept csv file and give output in excel file.

Remarks detail:
Repeting_More_3 : is to identify that if a outlet repeat a same customer number more that 3 times it is considered as a scam
F2D_Cust_num : Outlet are advised to give company Customer number if the customer refuse to give their number, so this classify the outlet that used customer care number
Fake number : Numbers which start rather than 6,7,8,9 and not 10 digits are considered fake number
CustNum_WOT_F2D_name : Classifies number is customer care number but the customer name is another 'A customer care number only have same customer name 'customer_care'
Fake_CustNum : Customer number written wrongly at the end
