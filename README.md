# spreadSheet

# toDos

### System architecture design
The goal of this part is to fully develop an architecture for this 
project, in which all important entities and processes work seamlessly.
The architecture decision will be done based on the requirements that
were gathered.

#### Designing and implementation of Database.
This is more about creating and analyzing database table relationship
with different entities of the system, we would need to
+ Find all valid system entities.
+ Create tables for each entities.
+ Find out table relationships.

#### Designing system flow
This will insure all the processes and steps are done 
in order when a user uses the system. 

#### Interface design
The interface in which the user interacts plays a key rule
for great user experience. There will be many pages and components
designed for this purposes.
+ Spread sheet submission form.
+ Data detail page.
+ Notification system for user.


## System features
### 1: Data aggregation
The main goal of this part is to convert all the raw data from the 
excel sheet to data that can be inserted in to our Database. This process contains below 
sub-processes.
For this we need to create/use reliable algorithm for file read handling.

#### Steps to follow
+ Excel file submission through a form.
+ extract columns and rows from excel file.
+ Analysing/parse rows and aggregate them.
+ insert the aggregated data to database tables.
+ perform error handling for each steps.

## 2: Data analyse
The data analyse is an important feature of the system.
The system have to extract relevant data from database. and be
able to decide certain again and give notification to end user.

