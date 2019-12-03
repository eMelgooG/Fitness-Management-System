# Fitness Management System  
   This is a basic membership management system for a fitness centre:  
   
-> the fitness centre has three outlets: Club Mercury, Club Neptune and Club Jupiter. It also has two type of members: SingleClubMember which has access to only one of the clubs and MultiClubMember who has access too all the clubs.  
   
-> the membership fee of a member depends wether it's a single club member or multi club member. For single club members, the fees also depend on which club he/she has access to.</br>

-> finally, multi club members are awarded membership points for joining the club. Upon sign up, they will be awarded 100 points which they can use to redeem gifts and drinks from the store. Our program will not handle the redemption process. We're only gonna add 100 points to the multi club member account.  
  
-> this application uses a csv file to store information about each member. Whenever we launch the application, we will read the the information from the csv file and store the members in a LinkedList. When we add a member to the LinkedList or remove it we will also update the csv file.</br>  
  
An updated version which uses PostgreSQL to manage data, can be found [here](https://github.com/eMelgooG/fitnessMMS-PostgreSQL).  
## Demo  

 As you can see from the screenshot there is already the members.csv file where all the entries are saved. If there isn't one in your folder, don't worry about it, the app will create the file automatically in the root folder of your project. Now let's run the program:
![](https://imgur.com/OWJPjKq.png)  
 Adding a new member:  
![](https://imgur.com/gpGXyRC.png)  
 Removing a member:  
![](https://imgur.com/5hYzIY4.png)

