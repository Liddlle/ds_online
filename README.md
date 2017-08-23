
Syllabus:   
-----------------------------------

* Week 1. INTRODUCTION. What is Data Science? art of DS + exploratory DA (лекция?)
Reproducible Research and Data Science  
https://stepik.org/lesson/50472/step/1
* Week 2. Introduction to the tools: R, RStudio, RMarkdown. Reports - начало лабораторных
https://aabakhitova.shinyapps.io/week2_2_basics/
* Week 3. Making plots: grammar of graphics and ggplot2 package https://aabakhitova.shinyapps.io/week3_ggplot2/
* Week 4. Data aggregation and manipulation: dplyr and tidyr (lubridate) packages 
Part 1: dplyr + ggplot повторение
Part 2: tidyr + lubridate
* Week 5. (КР1)
* Week 6 . Параметрические тесты + проверка гипотез
* Week 7. Проверка на нормальность, непараметрические тесты  
* Домашнее задание
* Week 8. Statistical learning: Linear Regression Models, Decision Trees (только лекция) 
* Week 9. Linear Regression Models
* Week 10. Regression and Classification Decision Trees 
* (Week 11. Unsupervised learning: Introduction to Clustering)
* (КР2)
* Домашнее задание и экзамен


Материалы:  
- Art of Data Science 
- Exploratory Data Analysis 
- http://tidyverse.org/   
- R for Data Science от Hadley Wickham http://r4ds.had.co.nz/   
- Text Mining with R http://tidytextmining.com/
- Статистика https://www.openintro.org/stat/textbook.php?stat_book=isrs 
https://bookdown.org/ 

Датасеты:
- датасет по звездным войнам в пакете purrr  
- https://www2.stat.duke.edu/courses/Fall15/sta112.01/data/ 
- kaggle  
  

learnr и checkr  
https://rstudio.github.io/learnr/  
https://github.com/dtkaplan/checkr/blob/master/vignettes/checking-code.Rmd  


Как на степике добавить задание с датасетом:
"Настройки урока" -> "Файлы" -> "Добавить файл" -> "Скопировать ссылку"
а потом в окне с кодом прописала код для чтения датасета
m <- read.csv(url("https://stepik.org/media/attachments/lesson/48791/Pokemon.csv"))
