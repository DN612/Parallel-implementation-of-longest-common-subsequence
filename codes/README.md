## Code update and run using script

Go to github repo "https://github.com/letshpcorg/letshpcsample". This repository has the scripts and a sample code to show the ease of use for the task of benchmarking a code for the platform.
Go to folder collect_data_without_perf to gather data without using the perf utility.
Go to folder named 'all_codes'. Here modify name format of the folder as id1-id2-problem_name-approach_name 
Add problem_name and approach_name to maps.py file. Adjust number of processors and problem size in maps.py for the given problem.
For code files, replace the contents with the new serial and parallel codes without changing the file name.
Download the scripts from the repository.
To run the script on multi-processor machines or cluster, do ./run_script_without_perf.sh to start data collection and generate csv file.
Make sure you run the code for at least 10 iterations.

## Plotting results

Go to letshpc.herokuapp.com
In Report Generator Tool, using 'Normal' option, upload CSV file "combined_logs.csv", generated after running script.
Select all the cores and press 'Update'.
Select a metric and choose 'Mean' as statistic. 
Make sure that of x and y-axis are properly scaled and labelled.
Export all the necessary graphs.




