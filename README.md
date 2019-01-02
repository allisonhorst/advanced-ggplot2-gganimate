# advanced-ggplot2-gganimate
eco-data-sci workshop (January 2019) - advanced data viz in ggplot2 + gganimate

# Data viz with ggplot2 and gganimate
eco-data-sci workshop (January 2019) 

[eco-data-sci.github.io](eco-data-sci.github.io)



We'll use examples to learn some basics of gganimate with ggplot2, + a few gg-extras. 

Includes:

- Animated point plots
- Animated line plots
- Animated column graphs
- Animated ridge plots
- Repulsive text labels
- Easy level highlighting

## Required packages: 

- ggplot2
- ggridges 
- ggimage (optional, but fun...)
- gganimate
- ggrepel

Install ggimage + gganimate development versions from github:

```r
setRepositories(ind=1:2)
## install.packages("devtools")
devtools::install_github("GuangchuangYu/ggimage")
```

```r
# install.packages('devtools')
devtools::install_github('thomasp85/gganimate')
```

## Data: 

### Channel Island Fox population data (ci_fox_pop.csv)

Friends of the Channel Island Fox: <http://www1.islandfox.org/p/materials.html>

### Star Wars API ('starwars' in dplyr)

This data comes from SWAPI, the Star Wars API (<http://swapi.co/>), and exists in dplyr as 'starwars'. More infomration: <https://dplyr.tidyverse.org/reference/starwars.html>



https://dplyr.tidyverse.org/reference/starwars.html

### Abalone physiology and rings data (abalone.csv): 
    Accessed from UCI Machine Learning Repository (<https://archive.ics.uci.edu/ml/datasets/abalone>)

    Warwick J Nash, Tracy L Sellers, Simon R Talbot, Andrew J Cawthorn and Wes B Ford (1994), "The Population Biology of Abalone (_Haliotis_ species) in Tasmania. I. Blacklip Abalone (_H. rubra_) from the North Coast and Islands of Bass Strait", Sea Fisheries Division, Technical Report No. 48 (ISSN 1034-3288)

    Original Owners of Database:

    Marine Resources Division
    Marine Research Laboratories - Taroona
    Department of Primary Industry and Fisheries, Tasmania
    GPO Box 619F, Hobart, Tasmania 7001, Australia
    (contact: Warwick Nash +61 02 277277, wnash '@' dpi.tas.gov.au) 
