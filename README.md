# MiniSQLEngine
SQL engine is defined as software that recognizes and interprets SQL commands to access a relational database and interrogate data. SQL engine is also commonly referred to as a SQL database engine or a SQL query engine.

## Technologies 
1) Jupyter Notebook
2) Python3 and its Libraries

## Launch
How to run the project?

**Dependencies**

Before plugging into the project make sure you have the following requirements updated: (run the command aside if not)

apt-get -y update : execute if running any of the below.
1) Python3: apt-get -y install python3 
2) Python pip: apt-get -y install python3-pip 
3) CSV: pip3 install python-csv
4) SQL Parser: pip3 install sqlparse
5) IterTools: pip3 install more-itertools

**Clone**

Clone this repo to your local machine using:
```code
git clone https://github.com/SmritiAgrawal04/MiniSQLEngine.git
```

**Execute all the cells of the notebook to start the engine.**

## Implementation Details
Implemented a subset of SQL clauses like- Select, From, Where, Aggregate Functions(max, min, sum, avg, count), Distinct, Group By and Order By. Almost all permutation and combination of above clauses can be exceuted on the built engine. Examples of some queries are as follows- 

1) select * from table1;
2) select A, B from table1 where B < 800;
3) select max(B) from table1 where B < 500;
4) select A,D from table1, table2 where A < 500;
5) select B from table1 group by b;
6) select C from table1 order by C DESC;
7) select a,b from table1, table2 where A > 800 and B < 200;
8) select avg(D), sum(E) from table2;
9) select * from table1 group by B order by A DESC;
10) select * from table2 where e < 10000 order by D ASC;
