# Project-Mexican-restarant-Rating-SQL-Tableau-
##### Description of the dataset 
   
Restaurant ratings in Mexico by real consumers from 2012, including additional information about each restaurant 
    and their cuisines, 
        and each consumer and their preferences. The dataset is available on Maven analytics website
      https://www.mavenanalytics.io/data-playground?page=2&pageSize=5
   
   
##### Tasks to do and our insights from the analysis:
      
###### What can you learn from the highest rated restaurants? Do consumer preferences have an effect on ratings?
      
    The highest rated restaurant was selectedusing a SQL query [select * from restaurants where Restaurant_ID  in
         (select Restaurant_ID from ratings where Overall_Rating=2 and
        Food_Rating=2 AND Service_Rating=2)] then analysed using Tableau. From the reported results, we can say that the 
        the highest restaurants have a medium prices, propose Mexican cuisine, don't have parking, don't allow smocking, dont 
        offer alcohol  and most of they are located in San Luis Potosi state because it's a touristic state
        
         

  ###### What are the consumer demographics? Does this indicate a bias in the data sample? 
          The consumer demographic is single, students who are independent don't have children and have a medium budget. 
            Yes, from the donut chars illustrated in my dashboard I can say that the is a bias in the data sample because 80%
           of the population of the data represents single students and this will lead to some false positive insights.

           Are there any demand & supply gaps that you can exploit in the market?
           Yes, The customer need more mexican food with a medium price. For the supply, I am not seeing variables related to
            supplies.

   ###### If you were to invest in a restaurant, which characteristics would you be looking for?
         If I want to invest in  a restaurant, I will invest in a restaurant that offer mexican food with a medium price. 
         
   My Tableau Dashboard https://public.tableau.com/app/profile/lamis.ghoualmi
          
 
