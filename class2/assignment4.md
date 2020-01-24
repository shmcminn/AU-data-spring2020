# Assignment 4: Find a Story

Using either the FEC, Senate lobbying portal, congressional disclosure forms or White House disclosure forms, find a newsworthy story that hasn't been previously reported. This can be something of interest to a local or national news audience.

Write a pitch to your editor about how you would pursue this story. This may include what other sources you would check with, what further data analysis you may perform and how long the story might take you.

Turn in:

1. A brief summary of what you found
1. The pitch to your editor
1. A step-by-step data diary of how you obtained the data and any cleaning/analysis you did
1. A sample headline and nut graf based on your finding

**Example**

I found that employees of Northwestern University overwhelmingly favored Hillary Clinton over Donald Trump with political contributions in the 2016 election.

To follow up on this story, I would compare this to how Northwestern employees contributed during the 2012 and 2008 presidential races and see if it lines up with the split between Clinton and Trump. I also would interview some of the few individuals who donated to Trump to see how they feel about working at an organization where they are in the minority. This story would likely take two days to report.

In order to find my story, I did the following:

1. Searched the FEC website for donations in the 2016 election cycle from employees of "Northwestern Univ"
2. Filtered to only contributions to Hillary For America and exported a CSV file of the results
3. Repeated the previous step for Trump's presidential campaign committee
4. For both CSVs, I: 
    * took the sum of the `contribution_receipt_amount` column
    * made a pivot table to get the unique number of donors to each campaign

Hed: Clinton's Donors Far Outnumber Trump's At Northwestern

Nut graf: Last election cycle's split wasn't even close. The Hillary For America campaign committee reported to the Federal Election Commission receiving donations from nearly 270 employees at Northwestern. 

How many gave to Donald Trump? Eight.


