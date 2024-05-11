**UCR Offenses by State, 1960-2020**

This repository provides “legacy” Part-I offense counts by state, from 1960-2020. These come from the FBI’s Summary Reporting System, which is obsolete after 2020, when the FBI switched to NIBRS and agency participation substantially dropped off. 

I got 1979-2020 data from the Crime Data Explorer (https://cde.ucr.cjis.gov). These can still be obtained by clicking on the *Documents & Downloads* tab at the top of the page, and then scrolling down to *Summary Reporting System (SRS)* under the *Additional Datasets* section. A caveat is that, in the Crime Data Explorer, state names have leading spaces in some years but not others, so it requires a little cleaning up. But this is nothing an strtrim() function cannot handle. The source data also include rows for DC and the US as a whole, which I dropped from this repository. 

I filled in 1960-1978 data from the UCR Data Tool (https://www.ucrdatatool.gov), which has now been retired and is unfortunately no longer available. In 2015, I pulled the 1960-2014 data from the Data Tool, but since I cannot document the source data, I only used it to backfill prior to 1979 in the repository. However, the 1979-2013 counts in my spreadsheet align with the Crime Data Explorer—2014 counts differ, but they would have been updated in the year after I pulled them.

Note: New York did not have crime data for 1960-1964 in the Data Tool, so users will notice one less state in those years. That is not a mistake.
