# UFOs

## Purose 

The purpose of the project is to make Dana’s website better with adding searching table that can filter out sectors such as city, state, country, and shape. By adding this feature to the website it make it easier for the users to find information they need. 

## Walk-Thorugh 

The website starts with an interesting article which gains interests of the users. Image I used for the banner is a image of the Earth looking from the 
space.
<img width="1285" alt="website 1" src="https://user-images.githubusercontent.com/100255000/171774845-eed71e90-154f-4aa9-9ca3-8068ef77f927.png">



The filter section controls the table that is being generated, the filter contains Date, City, State, counrty and shape sections. 
The Result shows below. 

<img width="1287" alt="website 2" src="https://user-images.githubusercontent.com/100255000/171774855-d8d7c90c-5cab-4698-96d5-c74d0c234295.png">

## Analysis 

More filters were added by using "li" class. Codes used are shown in the following image. 
<img width="653" alt="code-html-filter" src="https://user-images.githubusercontent.com/100255000/171775020-6290ed40-b002-4d37-a393-12f7ddbcbce6.png">

The filters are updataed using these codes on app.js file. 
Main functions that are used are updateFilters() and filterTable().
updateFilters() function saves the element, value, and the id of the filter that was changed.
and  filterTable() fuction loops through all of the filters and keeps any data that matches the filter values.

Here are the codes that are used. 
<img width="537" alt="code- app-filter2" src="https://user-images.githubusercontent.com/100255000/171777003-a5415211-f8fe-46e2-bf16-bfe7376600a9.png">
<img width="624" alt="code-app-filter1" src="https://user-images.githubusercontent.com/100255000/171776998-f0a25063-72d5-4e48-9eb1-0e22662088b8.png">

The result looks like this if I filter out for date of 1/6/2010.
<img width="995" alt="result1" src="https://user-images.githubusercontent.com/100255000/171779182-a87a5559-e7bb-4e25-b6b1-b4d5d68e43f3.png">


## Summary 

The website looks and works very well, but it has few drawbacks. 
First of all, Button for the filter would come in handy to make users to assure that the it has been added to the results. 

Secondly, it would be better to shorten the article to make sure the table shows when we open the website in one glance. 

