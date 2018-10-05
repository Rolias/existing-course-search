# Existing Course Search

When curriculum needs to check for overlap we have to search both the current library and the courses in the pipeline. The code here along with the google sheet is designed to give us a way to search both at the same time and always be hitting current data. It will rely on the augmented nightly snapshot for the course data and it will rely on Hampton's python script that queries Salesforce for courses with stages of:
Course Commissioned
Course On Hold
1st Module Approved
75% of Modules Approved
Course Delivered
Topic Approved
Topic Review