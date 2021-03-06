<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Bureau_of_Customs.svg/1200px-Bureau_of_Customs.svg.png" width=20% align="center">  

# Call of Duties: An Analysis of the Duties and Taxes of Imported Products in 2019

## <span style="color:darkblue"> Executive Summary </span>

Except for the year 2018, the Philippine Bureau of Customs (BoC) has consistently missed its revenue collection targets. It seems likely that the BoC would again miss their target in 2020 because of the pandemic affecting the world. This study is an exploration of the importing behavior of the Philippines using 2019 customs data. The data is part of the "Philippine Customs Imports dataset" made available by the BoC [through their website](http://customs.gov.ph/import-reports/). The researchers would like to explore the question "Where does the Bureau of Customs' income come from?"

In line with this, the researchers would like to know:

* What materials are we importing from which countries?
* How much do these materials contribute to BoC revenue?
* How does the value of duties and taxes vary relative to the dutiable value of a product?

Data were extracted from the customs website and consolidated in `Jojie` and transactions for 2019 were consolidated in a CSV file. Data and rows based on DUTIESTAXES were focused on and prepared for analysis. All data based on `DUTIESTAXES` were filtered. Concerning the `DUTIESTAXES`, a new column named `HS2` was derived from `HSCODE`, `year` and `month` was added to it, then the `HSCODES` were merged into the current dataframe. The dataframe was then analyzed and the results showed that the materials that contributed the most in the BoC’s revenue are oil, machinery, electrical components and vehicles, and the countries that provided these the most are China, Thailand, Korea, and Indonesia. The insights gathered from this analysis can inform the agency so they can reduce risks related to too much reliance on a single supplier for a particular product as well as to hit their revenue collection target by making use of its limited manpower to monitor and ensure collections knowing that certain products contribute more to revenues. This is especially relevant now as countries impose lockdowns in their economy, overreliance on a single country for a certain product might prove to be a single point of failure in the entire supply chain.

