
# All-in-One Complaint Report

This project is a demo of a sophisticated complaint report I have built using Python, Plotly, Pandas and more. The code is written in Jupyter Notebook, feel free to download it and have a look.


## Features

- Total Complaints by Year
- Total Complaints by Sales Office
- Total Complaints by Analyst, i.e. who is responsible for processing the complaint
- Total Complaints by Creator, i.e. who created the complaint in the system
- Complaints filed for Customer Service
- Complaints filed for Customer Service by quarters & reasons for these Complaints
- Complaints filed for Customer Service with specifically indicated Customer Service errors
- Total OTIF, i.e. how many complaints have been registered in the system within one day from the day they have been filed
- Individual OTIF, i.e. the same as above but split for each employee
- Total Pricing Issues, i.e. how many complaints have been filed due to discrepancies in prices on billing documents.
- Pricing Issues by Month
- Pricing Issues by Sales Representative
- Total Complaints for DC Spring Valley
- DC Spring Valley Complaints by Month
- DC Spring Valley Complaints by Reason/Failure Code. i.e. whether the complaint is concerning logistic shortage, quality issue etc.
- DC Spring Valley Complaints by Justification Code, i.e. whether the complaint has been justified or not
- DC Spring Valley Complaints Justification Code by Values (of credit notes)
- DC Spring Valley Complaints by Total Value (of credit notes)
- DC Spring Valley Complaints Value by Month



## Transformations

To create a final report, the script utilizes several files:

- Quality Complaint - SalesOrg Level 2 - raw file with source data of all registered complaints.
- 0ANALYSIS_PATTERN - contains a list of orders and credit notes along with their values.
- korekty - contains a list of orders along with the complaint numbers. Based on this, complaints and values are matched together.
- formuły - includes lists of source values and corresponding target values that the aforementioned values should be transformed into. These include quality analysts, months, complaint reasons, justification codes, and more.

Using the above-mentioned files, the script performs a series of transformations and "cleans" the file, bringing it to the final version from which all visualizations are subsequently generated.
List of all the transformations can be found within the .ipynb Jupyter Notebook file.


## Download

Final report is ready under "All in One Report.html" file. It requires additional styling so that it does not scare anyone away, so I highly advise you download the css, js and scss folders as well and put them in the same folder as All in One Report.
