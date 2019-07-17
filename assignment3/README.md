# Cleaning LOBBYISTDATA #

## [LINK TO DATA](https://data.cityofchicago.org/Ethics/Lobbyist-Data-Compensation/dw2f-w78u/data) ##

### STEPS ###
1. I first eliminated the *LOBBYIST_MIDDLE_INITIAL* because I didn't think it was necessary to have in the data set. 
2. Then I alphabetized the data set by first name, instead of last name. This was more of a visual appeal for me than anything else. I use the filter that can **sort cells/data from A-Z** in excel. 
3. Then I combined the first and last name by using the formual **=cell&" "&cell**
3. I then wanted to cobine the *PERIOD_START* and *PERIOD_END* columns to condense the data. But I first add to format the dates a different way since excel doesn't read "/" in its formulas. I used the formatting tool in excel to convert the dates into **month (abbreviated) day, year** (format-->date)
4. When trying to combine the dates I need to find a formula that would allow me to convert it into a new table. I was able to find a formula online **=TEXT(B5,"mmm d")&" - "&TEXT(C5,"mmm d")** from this [website](https://exceljet.net/formula/create-date-range-from-two-dates)
5. Then I changed the *CREATED_DATE* into a long form date **month day, year** using the formatting tool in excel
(format-->date)
6. Then I wanted to add the **$** symbol to the COMPENSATION_AMOUNT. So I found a formula online **="$"&A2** from this [website](https://www.extendoffice.com/documents/excel/670-excel-add-text-to-beginning-end-of-cell.html)
7. Then I formatted the *COMPENSATION_AMOUNT* to have a comma for every *thousand* by using the formatting tool in excel (format-->currency)
7. Lastly, I changed the order of the columns to the order (left to right) *LOBBYIST_ID*, *LOBBYIST_NAME*, *PERIOD*, *COMPENSATION_ID*, *COMPENSATION_AMOUNT*, *CLIENT_ID*, *CLIENT_NAME*, *CREATED_DATE*. 
