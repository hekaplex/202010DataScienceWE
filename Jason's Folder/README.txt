# Repository for Jason T

My goal at this point is to leverage Power Platform certifications for current career mobility. I'll probably just complete a MVP around BI since I'm also focused on trying to 
build a Python foundation in preparation of a DS sponsorship following Divergence.

Since labor is typically the largest cost for organizations, I was thinking of doing an HR analytics piece. The dataset I pulled focuses on predicting retention. Useability is
high, however not a significant amount of variables and relatively basic.

My initial thoughts for the flow would be:

-ETL dataset
-Benchmark classifier via Azure ML
-PowerApp for employee engagement and interaction, but also generating additional variables through user-inputs
-Power Automate that connects with PowerApp to input variables to be used for future model tuning, could possibly send alerts to HR or team leads for whatever reason
-Dashboard for HR teams

# I'm more focused on synching the platforms than build-outs. Essentially, future use case would be to take additional variables to build a more robust model for 'fit' using 
self-identified employee inputs, process automation for talent acquisitions, and automated dashboards for business leaders to gauge their teams.
