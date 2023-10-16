# Data breach analysis 

Bitsight, the international cybersecurity rating agency requested an interactive data storytelling about trends in data breaches. Bitsight provided me with a dataset including data breach security incidents from 2015 until 2022 in the US. 

## My workflow 

- Data processing using arquero.js 
- EDA using arquero.js and plot.js 
- Creating a storyline based on the most interesting patterns discovered in the EDA 
- Designing different data visualisation options using d3.js 
- Writing the blog post including the final interactive visualisations 

## Challenges 

The dataset didn't include any numeric variable hence showing frequency by categories was the only option, which limited the possibility in terms of visualisation type. 

Another challenge was to understand which data patterns are revealing realworld trends. In order to overcome I researched deeply the topic and kept in close contact with the Bitsight team. 

After discussing the results of the EDA with the Bitsight team I decided to use an interactive barcode chart in the format of a small multiples. 

![Alt text](<Images/Viz 6.png>)

![Alt text](<Images/Screen Recording 2023-10-16 at 16.10.27.gif>)


This chart allows the user to make several comparisons in one view. First comparing low severe (=blue) vs. high severe (=red) cases over time and secondly by different category types like sectors, motivation, assets etc. The chart includes a tooltip to show all details per case. For the purpose of smooth UX I applied transitions when buttons are pressed. The whole visualisation is written using d3.js.  

