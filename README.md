# Pybank

## Purpose
This python program takes a list of financial records included in budget_data_1.csv and budget_data_2.csv and determines some summary statistics. Each file contains two columns: Date and Revenue. It returns a results file that includes the number of months included, the net revenue, the average change in revenue between months, the date and amount of the greatest increase in revenue, and the date and amount of the greatest decrease in revenue.

## Requirements
It requires python to be installed. Python 3.6.2 was used during development. It utilizes the os, and csv libraries to read the data file and to write the results file. The data is included in the raw_data file contained within the repository.

## Running the Code
to run enter the following into the command line: 
`$ python budget_analyis.py`

## Results
Results can be seen in pybank_results_summary_1.txt and pybank_results_summary_2.txt. <br/>
The results for each file can be seen in <br/>
budget_data_1.csv: <br/>
Total Months: 41 <br/>
Total Revenue: $18971412.00 <br/>
Average Revenue Change: -$6758.98 <br/>
Greatest Increase in Revenue: Feb-16 $1837235.00 <br/>
Greatest Decrease in Revenue: Aug-14 -$1779747.00 <br/>

budget_data_2.csv: <br/>
Total Months: $86 <br/>
Total Revenue: $36973911.00 <br/>
Average Revenue Change: -$5955.32 <br/>
Greatest Increase in Revenue: Jul-2014 $1645140.00 <br/>
Greatest Decrease in Revenue: Jun-2014 -$1947745.00