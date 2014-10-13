607quiz7
========

)PostgreSQL downloaded and installed dvdrental downloaded

2)from dvdrental database I go to SQL icon and type:

SELECT COUNT(*) FROM film  WHERE lower(title) LIKE '%bride%';

    2

3)"CREATE TABLE AS " from postgres offer a superset of functionality provided by SELECT INTO in ANSI SQL's;the advantage  of using it is that it avoid ambiguity when using an application where both syntax are used .Prior to CREATE TABLE AS ,the syntax was SELECT INTO in postgres with different meaning ,this bring ambiguity.The disadvantage is that with larger difference in syntax ,an application with a interface between the 2 syntax get more complicated to implement!

4)To prevent someone from deleting customer who owes money ,we (the administrator)can create a VIEW from customer_id table where the amount is less than zero with security key .And we(the administrator) can use this View anytime to retrieve the information needed
.. 

Click to maximize/restore view 

Click to collapse/expand grading panel 
 

Assignment Details  















Grade 

Last Graded Attempt

 /10 




 Attempt  
10/12/14 11:47 PM
  
 /10 



Submission

Submission Text 


  
..
