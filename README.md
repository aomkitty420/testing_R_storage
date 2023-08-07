# testing_R_storage
#testing public R coding storage#
##testing_R_coding_storage
print("hello world")

install.packages( "tidyverse" )
install.packages("ggplot2")
library("tidyverse")
library("ggplot2")

df<-mtcars %>%
    select(mpg,hp,wt,am)
