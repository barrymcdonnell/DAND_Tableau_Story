# Prosper Loan Data: A Tableau Story
Creating a Tableau story as part of the Udacity DAND programme

First version of the story: https://public.tableau.com/profile/barry.mcdonnell#!/vizhome/Udacity_DAND_Barry_McDonnell_Loans_v1/ProsperLoansv1

Final version of the story: [insert link here]

# Summary

Prosper is a peer-to-peer loan platform allowing people to borrow money from other individuals at certain rates, enabling them to bypass traditional banks and potentially making loans more affordable and accessible for thousands of people.

There are over 110,000 observations in the data set with 81 variable covering such things as the original date of the loan, the amount of the loan, the APR, a credit score, geographical state information, debt to income ratio and many more

# Design

There is a question that I want to answer in relation to the Prosper data - how has lending evolved over the year? Has the number of loan offered increased over the year or been influenced by external factors? How has loan status changed? Are more people going into arrears or are they paying off the loans early? Do people have different monthly repayments based on their income and has it changed over time? How does the interest/fees generated compare to the total money repaid over the term of the loan? How does the interest/fees generate fluctuate over months? How does the number of loans fluctuate by state? What difference is there between the minimum and the maximum APR rates in each state?

How has lending evolved over the years (in the dataste)? What changes have been made to lending and borrowing habits? Are there any external factors over the time period that have had an influence on lending habits? 

The best way to answer these questions is through a series of different type of visualisations. Time series data (as is contained in this dataset) is often better visualised through a line graph. Line graphs can show trends over time. For the first part of the story a line will be used to portray the number of loans offered and the average borrower APR and to compare them to see if there is any correlation between them. Line graphs are also used in the 2nd and 3rd part of the story as these parts portray data over time. 

When comparing the average amount of total payment over the course of the term and the average interest paid as a percentage of the total amount paid back, this is best highlighted using a bar chart with a line chart on top. Theis enabled the variables on the chart to be clearly visible and distinct from each other. There is a variable in the dataset called Borrower State - this is encoded as geographical information so a map is definitely the best way to display this. When comparing two different variables against a third geographical variable, a bar chart with a line chart was considered to best the best option here. Each of the chart types have filter actions where the user can choose (a number of) states or a (range of) loan amount or employment status or income range.

On some of the graphs, data points are highlighted, showing the to hte reader immediately the values behind the data. On other graphs, part of the data is highlighted, like the average (using a reference line) or the minimum and maximum values. On the map, certain values are visible at all times allowing the user to easily compare values across different states. On a number of the line charts, colour has been used to differenciate between different values, for example different income ranges have different colours so it is immediately apparent to the user which income range is which

# Feedback

I sent my initial Tableau version to a colleague and this is the feedback I received:

* you should include a title slide
* maybe include a logo to make it more professional
* explain what the story is going to talk about properly, not just a page-by-page description
* explain the types of visualisations you are going to use
* I'm not sure I like the bubble chart!
* the first graph is a little empty; include some numbers to it's easier to see what we're looking at
* can you add somthing to the employment status, like income range or length of time in the job?
* there is very little filtering on the pages - what if we could select individual states or be able to focus on one employment status or income range?
* ensure that a full range of colours is used to differenciate between the variables
* ensure that the legends are adequately positioned and that the axis labels have meaningful names

# Resources

Data was downloaded from here - https://docs.google.com/document/d/1w7KhqotVi5eoKE3I_AZHbsxdr-NmcWsLTIiZrpxWx4w/pub?embedded=true

The dataset used was the 'Loan data from Propser'
