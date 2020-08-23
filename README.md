# surfs_up
## Overview of the Analysis/Purpose:
    Using my knowledge of Jupyter Notebook and SQLite databases to study weather trends for the Hawaiian island of Oahu.  In the module, the weather patterns for an entire year were studied (8-23-2016 to 8-23-2017) as part of a sales pitch to an investor (W. Avy) to possibly invest in a new "Surf n' Shake" shop.  For the Deliverables, the temperature data for the months of June and December were analyzed to determine each months summary statistics.  These statistics help determine if the surf and ice cream shop business is sustainable year round.

## Results:
    When examining the results as seen in the following pictures (./Data Boot Camp Class Folder/surfs_up/Deliverable_1_June.png) and (./Data Boot Camp Class Folder/surfs_up/Deliverable_2_December.png), three key differences can be found.  

        1) All data points for the month of December produced a minimun temperature of 56 degrees fahrenheit, while the data points for the month of June produced a minimum temperature of 64 degrees fahrenheit.  Given that the standard deviations for both months are 3.25 and 3.75, this indicates that December has had many instances where the temperature was less than the minimum temperature for the data points recorded in June (64 dgrees fahrenheit).  Winter in Hawaii occurs in December which explains the lower temperatures, but also raises concerns about the viability of the business during that month.

        2) The average temperature, or the mean temperature for each month shows a difference of about 4 degrees fahrenheit (74.9 degrees in June and 71.0 degrees in December).  Although this mean temperature difference is not insignificant, it is not as large as the mean temperature difference between June and December in other cities such as New York which alternates between being very hot (June) and very cold (December).  This matters because if the temperature is more consistent year round, the viability of the proposed business increases.

        3) The other key difference between the data recorded for June and the data recorded for December is the actual count of temperatures taken.  In June, there were 1700 temperature recordings while in December there were only 1517.  The difference of 183 recordings is significant because more data points taken tends to lead to less variance.  The standard deviation for December is higher than the standard deviation for June which means the extent of deviation in the data group as a whole is higher in December.  If more data points were taken for the month of December, maybe that wouldn't have been the case.

## Summary:
    Two additional queries that can be performed to gather more weather data include recording the precipitation(s) for both the months of June and December, while also recording the total temperature data points for more months of the year (November and March for example, since those months coincide with season changes in Oahu).  More monthly recorded data temperatures allows us to determine whether the mean temperature across every month is as relatively constant as the results for June and December would indicate.  Since Oahu is an island, there is probably lots of rainfall year round.  Examining that rainfall for the months of June and December can also help us determine whether the surf and ice cream shop is indeed a viable business.
