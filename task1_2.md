# Завдання 1
link https://www.kaggle.com/rohanrao/formula-1-world-championship-1950-2020
Датасет має данні про міжнародні перегони формули 1 1950-2021 роках
Є дані про кількість кругів, учасників, кілкість пітстопів та багато інших деталей.

# Завдання 2
``` > library(XML)
> xmlUrl = "http://d396qusza40orc.cloudfront.net/getdata%2Fdata%2Frestaurants.xml"
> download.file(xmlUrl, "data.xml", "auto", TRUE)
> data <- xmlParse("data.xml")
> sum(xpathSApply(data, "//zipcode", xmlValue) == 21231)
[1] 127 ```
