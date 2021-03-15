# ActiveJobs
This code is used to scrape all the Dice jobs posted in the last 24 hours for a specific set of JobTitles and locations.
The project is implemented using Selenium. All the connection details are in main.py. Dice url and driver details are in Driver_Paths.py.
Scrapper.log has all the log details. The project is used for scrapping the jobs in Dice portal, however it can be extended to other portals using JobPortal_Common_Defs.py.
The jobs will be scrapped on a daily basis and are appended to a csv. Attached is a sample csv created at the end of the job.
