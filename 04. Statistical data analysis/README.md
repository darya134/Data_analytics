# 04. An analysis of a telecom company's tariffs

## Dataset

The following data was available:

Table users
* user id
* first name
* last name
* age 
* registration date (day, month, year)
*  termination date (if the value is missed, then the tariff was still valid at the time of uploading the data)
* city
* tariff

Table calls
* call id
* call date
* call duration
* user id

Table messages
* message id
* message date
* user id

Table internet
* session id
* mb used
* session date
* user id

Table tariffs
* tariff
* monthly fee
* minutes included
* messages included
* mb included
* pay per minute
* pay per message
* pay per gb

## Task

Examined customer behavior and the costs of different mobile operator tariffs for a mobile telecommunications company.  

## Python libraries

*pandas*, *matplotlib*, *numpy*, *seaborn*, *scipy*
