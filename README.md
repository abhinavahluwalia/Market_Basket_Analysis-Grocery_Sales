## Market Basket Analysis using Grocery Sales Dataset

<p> This repository is dedicated to market basket analysis performed for a grocery sales data set. <br>
	The data set contains nearly 10000 sets of items bought during sales transactions having are a total of 169 items of interest.<br>
	The goal of the notebook is to perform market basket analysis of these item sets to identify combinations of items that can be promoted together following item purchase trends observed from the data.</p>

<p> The analysis follows the following approach:
	1. Wrangling the data to get it into a format ingestable for the apriori algorithm
	1. Visual EDA of frequent items observed in transactions
	1. Determination of frequent itemsets using the apriori algorithm and finding appropriate values for support and confidence levels
	1. Determination of association rules amongst items using association metrics such as confidence, lift and conviction.
</p>
We can clearly observe the association between the purchase certain items at the end of the analysis.