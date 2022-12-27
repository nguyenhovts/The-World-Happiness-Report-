# The-World-Happiness-Report-

The United Nations has hired you to support a week-long conference as their data specialist to help
analyze the results of the World Happiness Report. The World Happiness Report, published by the UN
Sustainable Development Solutions Network, surveys countries across several quality-of-life
characteristics – such as economy, family, health, freedom, generosity, etc. – to determine a global
happiness ranking. The happiness score is used to rank countries and it is calculated by taking the sum of
all quality-of-life characteristic scores.

  Day 1 - You have been tasked with consolidating and cleaning the 5 available datasets into a SQL view
named `vw_world_happiness_index_consolidated`.
1. Add a year column.
2. Some years include extra quality-of-life characteristics. Replace null numeric values with zero.
3. Not all datasets include a Region field. Fill out the null region values with the correct region.
4. Which countries do not have a corresponding region?
5. What is the difference in code if wanting to include all countries regardless of having a
corresponding region vs only including countries that have a corresponding region?
6. Include all countries regardless of having a corresponding region.

7. How many rows are in the consolidated view?

  Day 2 – In order to prepare this dataset for dashboard use, the quality-of-life characteristics need to be
unpivoted from columns to rows. Create another SQL view named `vw_world_happiness_index` with
the following columns: year, country, region, happiness_ranking, happiness_score, characteristic, value.


  Day 3 – You have been asked to create a report to identify which countries have ranked in the top 10
and in the bottom 10 in terms of happiness.
1. Generate a dataset that lists the top 10 and bottom 10 ranked happiest countries for each year.
2. Generate a dataset that lists the top 10 and bottom 10 ranked happiest countries of all time.
