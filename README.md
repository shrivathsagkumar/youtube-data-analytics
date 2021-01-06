# Youtube Trending Prediction

- I edit this To: Shrivathsa Gopala Krishna Kumar.
- To remember our firendship and dedicate his work.

## Introduction
This is a group project (machine Learning): Vloggers on YouTube are provided with visual analytics on the content they upload by default, but they
do not get the overall visualization of their competitor. Analyzing trending videos may provide publishers
with the ability to predict the trend. Thus, they can develop their future content based on the analysis.
Our analysis provides market forecast and intelligence which reveals information on the viewership, likes
and dislikes. This model prediction is based on many parameters and knowledge that our models have acquired by
analyzing most trended videos that have been uploaded on YouTube. So, this can be extremely useful and
profitable for YouTube channels who depend on their channels as a source of income.
. I also included 15 pages of research (by Shrivathsa Gopala Krishna Kumar, Rahul Niranjan Srinivas, and myself) that can be found [here](https://github.com/shrivathsagkumar/youtube-data-analytics/blob/master/src/Final-Report-pdf.pdf).

![alt](https://github.com/shrivathsagkumar/youtube-data-analytics/blob/master/src/images/CorrelationMap.PNG)

My application will be built from various data mining and model prediction methods. The combination of them will increase the change to prevent fraud detection. The disadvantage of this is the response time to end-users as many layers of detection will add more execution time to the application (O(log(n))).
Please click [here](https://github.com/shrivathsagkumar/youtube-data-analytics/blob/master/src/Final-Report-pdf.pdf) for the full statistic and prediction. 

### Technology
* R Programming
* Business Analyst
* Machine Learning
* Data Mining
* Data Visualization
* HTML
* CSS
* AI
* Algebra
* Statistics.

### Algorithm & Methods
* Data Exploration: Explore min, max, mean, standard deviation, correlation, and else.
* Data Transformation
* Plotting Methods
* Principal Component Analysis (PCA)
* Eigen Vector
* Pearson Correlation Map
* Spearman correlation map
* Confusion Matrix
* Predictive Models
* Hypothesis Test

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Data
Data is also include in the data folder.
Please download data at [kaggle.com](https://www.kaggle.com/datasnaek/youtube-new) first.

### Prerequisites
What things you need to install the software and how to install them:
- R CRAN Project: R is a free software environment for statistical computing and graphics. It compiles and runs on a wide variety of UNIX platforms, Windows and macOS
- RStudio IDE: RStudio is an integrated development environment (IDE) for R. It includes a console, syntax-highlighting editor that supports direct code execution, as well as tools for plotting, history, debugging, and workspace management. Click here to see more RStudio features. RStudio is available in open source and commercial editions and runs on the desktop (Windows, Mac, and Linux) or in a browser connected to RStudio Server or RStudio Server Pro (Debian/Ubuntu, Red Hat/CentOS, and SUSE Linux)

### Installing

A step by step series of examples that tell you how to get a development environment running:
* [Install R](https://www.r-project.org/) - If you haven't downloaded and installed R, here's how to get started.
* [R Studio IDE](https://rstudio.com/products/rstudio/#:~:text=RStudio%20Take%20control%20of%20your%20R%20code%20RStudio,tools%20for%20plotting,%20history,%20debugging%20and%20workspace%20management.) - After that choose R Studio Desktop, and the free version (unless you have the Pro install). R free version is a pretty good IDE.

## Running the tests

Explain how to run the automated tests for this system:
- Start R Studio.
- Open a project, navigate to the download file
- Open the rmd file (Final_Report.rmd).For example:
```
~/youtube-data-analytic/Final_Report.rmd
```

- you can store the WholesaleCustomersData.csv in the same folder, but it is recommended to store in a data as below (coding standard):
```
~/youtube-data-analytic/data/data.csv
```
- Make sure to change the import code on top if you want to move your data anywhere. Depend on where you download the code. Your path will be different from mine. Please replace the path below with your  path:
```
# Import Data
Rdata <- read.csv("~/R/DataMining/youtube-data-analytic/data/data.csv", header=TRUE)
# path:"~/R/DataMining/youtube-data-analytic/data/data.csv"
```
- Do it a few time to replace with the correct import file
- Please take a quick view of [import data in R](https://support.rstudio.com/hc/en-us/articles/218611977-Importing-Data-with-RStudio?mobile_site=true) if you fail to change the import code.
- Run the IDE by Choose the Knit option:
```
hit the "Knit" button
```

![alt](https://github.com/shrivathsagkumar/youtube-data-analytics/blob/master/src/images/1.png)

## Deployment
This can be deployed to any database system for prediction. Please note the application will work with any bigger or smaller data set as long as it follows the design pattern of this data set.
```
Columns Data Type
1. video_id String
2. trending_date Date
3. title String
4. channel_title String
5. category_id Integer
6. publish_time Date
7. tags String
8. views Integer
9. likes Integer
10. dislikes Integer
11. comment_count Integer
12. thumbnail_link String
13. comments_disabled Boolean
14. ratings_disable Boolean
15. video_error_or_removed Boolean
16. description String
```
More continuous attributes can just be added to the application, and it should work fine (with a bit of modification). Please refer to my research paper for a better understanding. [Full research paper can be found here](https://github.com/shrivathsagkumar/youtube-data-analytics/blob/master/src/Final-Report-pdf.pdf).

I will not guarantee that this application will work "Big data set". If you are interested in a "Big(or Large) data set" please join here for [an argument](https://www.researchgate.net/post/How-much-data-is-considered-to-be-small-data-Large-data-in-data-mining) on what data set is considered a large data set in data mining.

## Built With

* [R Studio IDE](https://rstudio.com/products/rstudio/#:~:text=RStudio%20Take%20control%20of%20your%20R%20code%20RStudio,tools%20for%20plotting,%20history,%20debugging%20and%20workspace%20management.) 
* [R CRAN Project](https://www.r-project.org/)

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Truc Huynh** - *Initial work* - [TrucDev](https://github.com/jackyhuynh)
* **Shrivathsa Gopala Krishna Kumar** - *Initial work* - [ShrivathsaKumar](https://github.com/shrivathsagkumar)
* **Rahaul Niranjans** - *Initial work* - [RahulNiranjans](https://github.com/rahulniranjans)

## References

my README.md format was retrieved from
* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* **Purdue University FortWayne** - where we represent this research in presentation and get improved feedback.

