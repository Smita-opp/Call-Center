# Call Center -Dashboard

### Dashboard Link : 



# Snapshot of Dashboard (Power BI Service)                                                               
 ![image](https://github.com/Smita-opp/Call-Center/assets/159506053/2f467d18-c002-41de-a555-b422887d5a40)





Main DAX Functioned used in the reports are mentioned below.

1. No of Answered Call .

       # of answered = Calculate(distinctcount('Call Center'[Call Id]),
       Filter('Call Center','Call Center'[Answered (Y/N)]="Y"))

2. No OF resolved case

         # of resolved = Calculate(distinctcount('Call Center'[Call Id]),
         Filter('Call Center','Call Center'[Resolved]="Y"))
