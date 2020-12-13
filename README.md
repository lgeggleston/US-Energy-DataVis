# US-Energy-DataVis
How does the distribution of energy production between different sources change over time? Is overall energy production and consumption increasing or decreasing over time? What percent of total energy production was in fossil fuels for a given year?	

Data sourced from the US Energy Information Administration: https://www.eia.gov/totalenergy/data/monthly/

I used 236 months of data as items, from 2000 to 2019, and attributes included the amount of production in each source (coal, nuclear, solar, biomass, etc.), monthly totals of fossil fuels and renewables, and monthly total production, consumption, imports, and exports.  

Processing and visualization decisions: I made agglomerations of some attributes in order to clarify and keep my graphics readable.  For example, for the lineplot I added all the smallest sources of renewables into one line. In the donut chart, I further combined all renewables into one segment, because pie-type charts become less useful with too many attributes encoded.   For both of the smaller idioms (donut and bar chart), I combined the data for all the months in a year, in order to make interactive selection of timespans in the line plot easier to read and more useful.  I also calculated percentages using the yearly totals to display on the donut chart. Finally, I calculated average values for each year to display on the line plot tooltip. All of these choices were made in order to simplify, make the graphs more readable, and display information that may be more useful to readers (yearly instead of monthly).
