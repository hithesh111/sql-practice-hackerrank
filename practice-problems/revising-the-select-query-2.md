Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA.

The CITY table is described as follows:

![1449729804-f21d187d0f-CITY](https://user-images.githubusercontent.com/44721008/108240337-c2002f80-7170-11eb-8a09-9787634800d2.jpg)

QUERY:

SELECT NAME

FROM CITY

WHERE POPULATION>120000 AND COUNTRYCODE = 'USA'
