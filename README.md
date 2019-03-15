# Where do I need SQL in spite of using R professionally? DPLYR package
The first idea is to go through what I played with dplyr and open this discussion, why SQL when I can use dplyr. 
I got the impression at work, that mainly who comes from SQL world, are not aware of R package and their usage. 

dplyr is a part of "tidyverse".  I recomment to install.packages(tidyverse), sooner or later you need all of them for your data prepration. 


I just got the inspiration of using nycflights13::flights. This dataset contains all 336776 flights that departed from New York City in 2013. Lately it is challenging to install this CRAN package directly. This worked for me:
install.packages("https://cran.r-project.org/src/contrib/nycflights13_1.0.0.tar.gz", repos=NULL, method="libcurl")

You should know that "flights" is a "tibble". Tibbles are data frames, but slightly tweaked to work better in the tidyverse. 
