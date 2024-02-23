"Zoo" small database

This database is ideal for small zoo. There are a lot of functionalities, which will save a lot of your time. 
For example there are 7 queries, using which you will be able to do complicated operations in one click. 
This queries will allow you to see health of your animals, producer of fodder, see the salaries of staff, delete empty tables and connect two tables in one. 

    List of functionalities :
- Add animals
- Find fodder for an animal  
- Check their health 
- Control staff
- Change feeding timetable 
- Easily check info about animals

    There is 7 queries :

AnimalHealth – is a select query that allows you to see current health level of each animal.
MoreFood - is an append query that will add new time of feed and quantity of fodder.
QuantityChange – is an update query that will update time of eating.
FoddVsSuplFeed – is an union query than will combine table Fodder with table Supplier Feed.
Salary – is a maketable query that will make new table with staffs names and salaries.
DeletingEmpty – is a delete query which that will delete empty values in table Aviary.
AnTypeGender – is a crosstab query that will combine Animal name, type and date of birth in one 
       table.

    Modules:
FormAnimals
FormFeedPlusSubForm
MainForm
SubFormFodder
