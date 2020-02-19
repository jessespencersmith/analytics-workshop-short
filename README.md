# ehr-analytics-workshop
Analytics Intensive Workshop in R using EHR (redcap) data.

This workshop assumes a no familiarity with programming, but some experience or need of analytical tools. If you have experience with programming in Python, or in base R, this workshop will still be worthwhile.

We'll cover the basics necessary for a reproducible and efficient analytics workflow. By the end of workshop, you'll have been introduced to functional programming, best practices for creatiing reproducible and understandable analytics.

## Workshop Outline

9 - 9:15
- Introductions, Discussion, and Example

9:15 - 9:45
- Discussion: Analytics Use Case
- Touring RStudio
- Writing Notebooks

10:00 - 12:00
- Validating Data
- Exploring Data
- Building Cohorts

12:30 - 4:00
- Summarising Data
- Combining Data Sources
- Building Patient Features

4:00 - 4:30
- Learning On Your Own

## Pre-Workshop Preparation

Before the workshop complete the following to make sure you have all the software you'll need installed and ready to go. If you need assistance, there will be a last-minute clinic 1/2 hour before the start of the workshop. See below for full instructions on each step.

**Prep Steps**

- [ ] Install R
- [ ] Install RStudio
- [ ] Install and test packages 

### Installing R

Visit https://cran.rstudio.com/ and select "Download and R for [your OS]". Select the "Base" option on the download page.  Once the file is downloaded, install the software.   

Also download and install Rtools if you are on Windows--you will find the link below Base on the list.

### Installing RStudio

Visit https://rstudio.com/products/rstudio/download/ and download the free version of RStudio for your operating system. 

### Installing and Testing Packages

Once R and RStudio are download, load RStudio, and copy-paste the following code in the console:

```r
install.packages("tidyverse")
install.packages("janitor")
install.packages("devtools")
install.packages("assertr")
install.packages("readxl")
install.packages("glue")
install.packages("knitr")
```
