## MARKDOWN ASSIGNMENT
### A Data Diary

#### Which industries contributed the most to the Republican and Democratic parties? How much was contributed to each party?
* Highlight all cells, make pivot table
* Assign "Industry" to ROWS; Assign SUM of "Amount" to VALUES
* Copy Pivot Table, create new sheet (Q1) and shift+CMD+V, freeze top row and add filters
* Sort SUM of AMOUNT column from Z - A
  * The industry that contributed the most with $7,514,000 was entered just as "Republican/Conservative." After that, Securities & Investment ($3,375,000), Media/Entertainment ($3,030,000), Tobacco ($3,020,000), and Real Estate ($2,500,000) were the industries that contributed the most. 

#### How much did donors from the Misc. Business sector contribute to the Democratic party?
* Highlight all cells, make pivot table
* Assign "Industry" to ROWS; Assign SUM of "Amount" to VALUES; Assign "Party" to COLUMNS
* Copy Pivot Table, create new sheet and shift+CMD+V, freeze top row and add filters
* Sort Industry from A-Z to find all the categories that start with Misc
* In next column, add in equation '=SUM(C35,C37,C38,C39,C41)' to find the total that these industries spent on the Democratic Party
  * The total that donors from the Misc Business sector contributed to the Democratic Party is $2,650,000
##### Which donors were based in Miami Lakes, FL?
* In main data sheet, copy all data for D Party 
* In new sheet, paste data and sort 'Donor' A-Z
* Start VLOOKUP equation in new column
* '=VLOOKUP(I7,A2:K186,1,FALSE)'
  * The donor based in Miami Lakes, FL was Windmere Corp

#### What percentage of the tobacco industry’s donations does Philip Morris account for? How much is it? 
* Filter 'Industry' column on main data by deselecting all and only choosing Tobacco to be visible
* Gather all Tobacco data (A378:K398) and create new sheet with data > create pivot table with that new tab
* Assign "Donor" to ROWS; Assign SUM of "Amount" to VALUES
* Show VALUES as % of grand total
  * Phillip Morris' donations account for 68.54% of all the tobacco industry's donations. That is $2,070,000.

#### Describe (in two to three sentences — no need for a detailed story pitch) one potential story from this dataset that you’d find promising if this were a project you were working on. Give it a headline. Include up to three types of sources you would call to report out the story and a few of the questions you might ask.
* It is simultaneously interesting and scary that the "Industry" that had the most donations was not an industry that provides necessary services to people but rather just a vague "Republican/Conservative". I think there is an interesting story here that could trace the different organizations that donated under this vague umbrella term and see where they came from, what kind of lobbying they do, and where they are getting this money to donate in the first place. I would like to call up the heads of these organizations and better try to understand what they are supporting and why. I would also reach out to professors who are experts in lobbying and politics to ask what the current situation is like in addressing this kind of donation strategy and what it means for fair elections.

#### What data might be suitable to join with this data to provide context or additional stories? Give me two examples.
* Since this is an old data set from a past election/presidency, I think it would be interesting to compare this data with the budget that ended up getting passed the following year. Depending on who won, were the top donor's interests represented in America the following year? 
* It also might be interesting to see the ways in which each of (or perhaps one single industry) allocates their campaign financing funds with the rest of their budget. How important is donating to politicians for these big (and smaller) corporations? What can that tell us about the state of the country today?


