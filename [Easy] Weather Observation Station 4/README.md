<h3>Easy</h3><hr>

<p>Find the difference between the total number of  CITY entries in the table and the number of distinct CITY entries in the table.
The STATION table is described as follows:

Table: <code>STATION</code></p>


<pre>
+-------------+--------------+
| Column Name | Type         |
+-------------+--------------+
| ID  	      | NUMBER       |
| CITY        | VARCHAR2(21) |
| STATE       | VARCHAR2(2)  |
| LAT_N       | NUMBER       |
| LONG_W      | NUMBER       |
+-------------+--------------+
</pre>

<p>where LAT_N is the northern latitude and LONG_W is the western longitude.
For example, if there are three records in the table with CITY values 'New York', 'New York', 'Bengaluru', there are 2 different city names: 'New York' and 'Bengaluru'.
The query returns 1, because total number of records - number of unique city names = 3 - 2 = 1</p>
