# titanic-random-forest
This is the script accompanying the tutorial here: https://will-stanton.com/2015/03/08/machine-learning-with-r-an-irresponsibly-fast-tutorial/

**All credit to Will Stanton for creating the code and tutorial.** I only made some minor adjustments to the code/repository to make it a little more user friendly for my intended audience.

This script+tutorial is an easy introduction to machine learning in R for novice users. It uses the Caret R package to implement a Random Forest model on the [Titanic Kaggle dataset](https://www.kaggle.com/c/titanic/data) to predict which passengers survived or died. It demonstrates how to implement this simple machine learning model and walks through how to submit your predictions to the ongoing Kaggle Titanic competition.

To use:
1. Ensure you have [R](https://cran.r-project.org/) AND [R Studio](https://www.rstudio.com/products/rstudio/download/#download) installed.
2. Download this repository to your computer by clicking the green "Clone or Download" button above, download the .zip file, and unzip it to anywhere on your hard drive. (Git savvy folks can instead fork and clone the repo if they wish).
3. Open titanic-random-forest.Rproj in R Studio, this will automatically set the working directory to wherever the .Rproj file ([more info on using R Project files](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects)) is located on your hard drive.
4. Open the r script titanic.R in R Studio.
5. From here, you should be able to simply run the R script from start to finish without any edits. However, I highly recommend following along with the tutorial linked above and running the code line-by-line while trying to understand what each line does.

Note: I converted this to use R Projects, and also provide the datasets in this GitHub repository. So, you can skip the steps about downloading the data and setting your working directory (setwd) from the tutorial.
