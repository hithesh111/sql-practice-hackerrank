Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN.

The CITY table is described as follows:

![1449729804-f21d187d0f-CITY](https://user-images.githubusercontent.com/44721008/108241529-f0cad580-7171-11eb-8007-a39695e8de9e.jpg)

QUERY :

SELECT *

FROM CITY

WHERE COUNTRYCODE = 'JPN'
