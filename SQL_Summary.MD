
# Data	Definition	Language	(DDL)
General purpose: Manages	table	and	index	structure.	The	most	basic	
items	of	DDL	are	the	CREATE,	ALTER,	RENAME	and	DROP	statements:

* CREATE creates	an	object	(a	table,	for	example)	in	the	database.	
* DROP deletes	an	object	in	the	database,	usually	irretrievably.	
* ALTER modifies	the	structure	an	existing	object	in	various	ways—for	example,	adding	
a	column	to	an	existing	table.	

# Data Manipulation Language (DML)
Used to delete add and update data.
CRUD - Create Read Update Delete
| Operation | mySQL | Description |
| --------- | --- | ----------- |
| Create  | INSERT INTO | inserts	new	data	into	a	database |
| Read  | SELECT | extracts	data	from	a	database |
| Update  | UPDATE | updates	data	in	a	database |
| Delete  | DELETE | deletes	data	from	a	database |
| Union | UNION | unions data from two table that is different from each other without copies to one table|
| Intersect| IN | selects the data that is inside the interval of columns or interval of set of data |
| If query for columns | WHERE | takes an condition and returns the data that satisfies the condition |
| Sort | ORDER BY | sorts the given columns if it can by numerical order or by lexical order if its for strings |
| Take sample | LIMIT | LIMIT i j -> returns j elements after the row i. Or LIMIT i returns i elements from somewhere |
| Make set of column | GROUP BY | makes sure only one record will appear in a table. |
| If query for a set (after GROUP BY) | HAVING | acts like WHERE just for set after result of a GROUP BY query |
| Table Intersection | INNER JOIN | if two tables have the same colums it results in a new table with the records of the columns from each table to a new one |
| Count table left once and intersection once again | LEFT JOIN | if two tables have the same columns it results in a new table contains all of the left table added to the records of the right table that the columns intersect with the left table |
| Count table right once and intersection once again | RIGHT JOIN | same for right |
| full join | not doc | - |



# The 4 main concepts of databases
1. Atomicity - Every operation in a database must excecute intierly or not excecute at all.
2. Consistency - Each transaction must change the database only in allowed ways.
3. Isolation - Several clients can not change data in the same table at the same time. They must be serial ordered.
4. Durability - The database transactions are saved so if the database crashed, it still will make the transaction complete or revert the changes after it's rebuilt.

# Common functions in mySQL
| Function | mySQL | Description |
| Count row | COUNT | Counts the amount of rows |
| Average column | AVG | Averages the given numbers of a column |
| Sum | SUM | Sums the given column |
| maximum value | MAX | returns the maximum value inside a column |
| minimum value | MIN | returns the minimum value inside a column |



#### Temp links for devs
[sql pdf](https://www.halvorsen.blog/documents/tutorials/resources/Structured%20Query%20Language.pdf)
