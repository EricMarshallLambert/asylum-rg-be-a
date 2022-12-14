## Problem Statement
[Human Rights First (HRF)](https://www.humanrightsfirst.org/)   is an independent advocacy and 
action organization that challenges America to live up 
to its ideals. HRF is seeking a data search and 
visualization tool to provide the public with a 
user-friendly view into their large data set of asylum 
case decisions. The concept is similar to [the TRAC database](https://trac.syr.edu/phptools/immigration/asylum/)—
a popular existing tool, but with a far more robust ability to select
and filter data.

This design document describes the HRF Asylum Report
Generator backend, a new service that will allow users
to view and filter decision data on multiple parameters,
generate visualizations, and download search results.

## General Use Cases
*For most up-to-date and detailed product requirements, please see Jira. This list is 
intended to give an overall picture.*

* A user can generate a table of results, filtered by multiple parameters
* A user can generate a real-time graph to represent what trend looks
like over time (Release 4)
* A user can generate a heatmap of asylum case outcomes (Release 5)
* A user can download the results of their search (Release 6)

  
## Project Scope

### Current scope
* Users can view all case data in a table
* Users can filter the dataset by one or more parameters 


### Future Scope
* Users can create a heatmap of asylum case outcomes
* Users can create a heatmap of asylum case outcomes filtered 
by one or more parameters
* Use can generate a real-time graph to display a trend over time
* Users can download their search results

### Out of scope
* There is no user account, authentication, or log-in
* Users cannot modify data in the dataset (cannot add, update, or delete.) 


## Learner Resources
This project extends the use of Spring Boot previously studied in the BD
curriculum. Previous BD learners have found these resources helpful in getting
up to speed:
* [Spring Book Workshop for BD led by Tom](https://www.youtube.com/watch?v=bQDvoqSSVpQ)
* [Spring Boot Cook Book](https://aveuiller.github.io/spring_boot_apprentice_cookbook.html)

This project makes use of Docker. Previous BD learners found this online tutorial, which is broken into chapters
helpful:
* [Docker tutorial](https://www.youtube.com/watch?v=3c-iBn73dDE)
