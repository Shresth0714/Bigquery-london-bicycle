# Bigquery-london-bicycle
This is a SQL database assignment was performed to track/visualize empty bike stations in London area.

**Data Set:** bigquery-public-data -> london_bicycles <br>
**Problem:** Empty bike stations <br>
**Problem Diagnoses:** <br>
I found traces of empty stations in the dataset where bike count is zero. The total number of stations is 781 out of the 8 stations are empty. Also found that there is one station that has bike count as 0 but the docking count is 21 and empty docs are 20 which means there should be a bike count of 1. Station name: St. Mary Axe, Aldgate. Considering this situation, I will assume that there is a bike present but that has not been reported. Total empty stations using this assumption is 8.

Google data studio used for visualization - https://datastudio.google.com/s/iaLrl4nUHu0 <br>
SQL code used for analysis is in Appendix with explanations and steps.
