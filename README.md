Tobii Eyetracker in R
=====================

Just a small test to plot the data exported by the tobii eyetracker in R

Tobii Eyetracker in R  

- Go to [r-project.org/](http://www.r-project.org/)  
- download and install R for your OS from one of the servers  

Mac OSX  

- Open a Terminal window and enter the follwing code  

This creates an R envoirment file in your home directory  

    echo "R_LIBS=/Users/$HOME/rLibrary" > $HOME/.Renviron

Then enter  

    mkdir ~/rLibrary  

This creates a folder called r
- Start R.app from your Applications folder  

Check your current working directory by entering:  

    getwd()  

The result should point to your home folder  

Set your working directory to somewhere where you can remember. e.g the Desktop or where ever you cloned this repo.  

    setwd("/Users/[YOUR USER NAME]/Desktop/tobii-Eyetracker-R")  

Now you can place files in there and read them with R.  

- Open the eyetracker.R with the R app.  
- Select the lines you want to execute  
- hit cmd + enter  
