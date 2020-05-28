# Brazil's Amazon Cimate Analysis:

Project aimed at exploring the relationship between precipitation, fires and deforestation in Brazil. Gathered data from governmental websites, APIs, and CSVs. Analysis includes statistical analyses and graphs.

Because Brazil is quite large, 8.5 million square kilometers, with over 211 million people, the analysis was geographically refined from the entirety of Brazil to just analyzing the Legal Amazon. 
The Legal Amazon is a socio-geographic division in Brazil, containing nine states with the Amazon Biome (Acre, Amapá, Amazonas, Pará, Rondônia, Roraima, Tocantins, Matto Grosso and Maranhão). This region accounts for 1/3 of the planet’s tropical rainforests, has the world’s highest biodiversity, the largest genetic bank, and 1/5 of the world's available drinking water. Preserving the Amazon is a top priority in mitigating Climate Change.

### Deforestation Analysis

Deforestation rates in the Brazilian Amazon have slowed dramatically since peaking in 2004 at 27,423 square kilometers per year. By 2009, deforestation had fallen to around 7,000 square kilometers per year, a decline of nearly 75 percent from 2004, a trend that has continued until 2017. While these figures seem promising, data from the 2018 and 2019 shows otherwise.

![](/output_data/images/defor_year.png)


### Deforestation vs Fires

Using linear regression, it was found that there is an 87% correlation between fires and deforestation. Because there is no correlation between precipitation and deforestation, we can deduce that most of the deforestation is man-made, rather than caused by natural conditions.

<div><img src="https://github.com/jCosta16/brazil-climate-analysis/blob/master/output_data/images/fire_defo_state.png" alt="fireLA" width="50%"/><img src="https://github.com/jCosta16/brazil-climate-analysis/blob/master/output_data/images/lr_fire_defo_state.png" alt="firebystate" width="50%"/></div>


In 2018, Brazil released its worst annual deforestation figures in a decade. Between August 2017 and July 2018, 7,900 km2 were deforested– a 13.7% rise from the previous year, and the biggest area of forest cleared since 2008. Deforestation in the Brazilian Amazon rose more than 88% in June 2019 compared with the same month in 2018. In the year 2019 approximately 9,762 square kilometers of the Amazonian forest were destroyed, 30% more than in the previous year.

## More Visualizations
### Fire
<div><img src="https://github.com/jCosta16/brazil-climate-analysis/blob/master/output_data/images/Fires_by_state.png" alt="firebystate" width="50%"/><img src="https://github.com/jCosta16/brazil-climate-analysis/blob/master/output_data/images/fires_legalAmazon.png" alt="fireLA" width="50%"/></div>
<br>
<div><img src="https://github.com/jCosta16/brazil-climate-analysis/blob/master/output_data/images/fire_state_year.png" alt="firextebyyear"/>
  </div>

### Deforestation

<div><img src="https://github.com/jCosta16/brazil-climate-analysis/blob/master/output_data/images/def_state_year.png" alt="defobystatebyyear"/><
  </div>

### Rain

![](/output_data/images/rain_state_year.png)


