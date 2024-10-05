NAME: Dorottya Frisch

TITLE: The Effect of EU Sanctions Against Russia on the European Energy Market

Since Russia’s invasion of Ukraine on February 24th 2022 the European Union has implemented 
multiple sanctions against Russia, the most significant of those being the sanctions on Russian gas. 
Before the invasion, the majority of European natural gas and oil needs were fulfilled by importing from Gazprom, 
Russia’s largest fossil fuel supplier, however, after June of 2022 the European Council adopted a package of sanctions 
which “prohibits the purchase, import and transfer of seaborne crude oil … from Russia to the EU”, restricting 90% of 
Russian oil imports to Europe. The 27 EU member countries have all adopted different strategies to cope with the 
sanctions – some found different suppliers, others shifted towards renewable energy sources, while others began reopening previously shut down nuclear reactors.

In this project I wish to visualise how the European energy market has transformed since 2022. I would compare 
the share of Russian oil before and after the sanctions, would compare the share of various sources of energy, 
and would show the impact of sanctions on energy costs. In terms of time period, I will compare 2019 (pre-covid) to
2022 data. While it would be better to visualise 2024 data and see the long term effects of the sanctions, the dataset
I plan on using only has data until 2022.


LIKELY DATA SOURCES:

All of the data I want to use will be from Eurostat (https://ec.europa.eu/eurostat), the official database of the European Union. 

In particular, I want to use 

Gas prices for household consumers
https://ec.europa.eu/eurostat/databrowser/view/nrg_pc_202/default/table?lang=en&category=nrg.nrg_price.nrg_pc

Tracks the gas prices for household consumers in all the 27 EU countries from 2007 onward. Has 36 rows, 
one row for every EU country, one row for the aggregate EU, one row for the Eurozone, and 7 rows for neighbouring 
countries which are not in the EU. The dataset provides 30 rows (bi-annual data for all the years between 2007 and 2024), 
but I will only be using two of these, 2019-S2 and 2022-S2.


Share of energy from renewable sources
https://ec.europa.eu/eurostat/databrowser/view/nrg_ind_ren/default/table?lang=en&category=nrg.nrg_quant.nrg_quanta.nrg_ind_share

Shows the share of energy each EU country gets from renewable energy sources from 2007 onwards. Has 38 rows, 
one row for every EU country, one row for the aggregate EU, one row for the Eurozone, and 9 rows for neighbouring 
countries which are not in the EU. As above, I want to use the two columns of 2019 and 2022 to do my comparison.


Imports of oil and petroleum products by partner country
https://ec.europa.eu/eurostat/databrowser/view/nrg_ti_oil/default/table?lang=en&category=nrg.nrg_quant.nrg_quanta.nrg_t.nrg_ti

Shows the imports of oil and petroleum products by trading partner for every European country. Has 43 rows, 
one row for every EU country, one row for the aggregate EU, one row for the Eurozone, and 14 rows for neighbouring 
countries which are not in the EU. This table can be customised to show the imports by certain trade partners, so if I select
Russia in the settings, the entire table will show imports from Russia with the columns being the years when the data was reported.
I want to use both the Russia table and the overall table to get a sense of the proportion of oil which was imported from 
Russia compared to overall imports. For 2022 data I also want to look through the table to find what other countries have 
became significant trade partners. 

Imports of natural gas by partner country
https://ec.europa.eu/eurostat/databrowser/view/nrg_ti_gas/default/table?lang=en&category=nrg.nrg_quant.nrg_quanta.nrg_t.nrg_ti

Same as the table above, only for natural gas instead of oil.

QUESTIONS:

I was wondering since I am using so many different sources, if it would make sense to combine some of them into a bigger table, or 
if I should leave it as is?
