<p>Query the two cities in STATION with the shortest and longest CITY names, as well as their respective lengths (i.e.: number of characters in the name).If there is more than one smallest or largets city, choose the one that comes first when ordered alphabetically.</p>
<p>The STATION table is described as follows:</p>
<p>Table: <code>STATION</code></p>


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

<p>where LAT_N is the northern latitude and LONG_W is the western longitude.</p>
<h5>Sample Input</h5>
<p>For example, CITY has four entries: DEF, ABC, PQRS, WXY</p>
<h5>Sampe Output</h5>
<pre>
ABC 3
PQRS 4
</pre>

<h5>Explanation</h5>
<p>When ordered alphabetically, the CITY names are listed as ABC, DEF, PQRS, WXY, with lengths 3, 3, 4, 3.</p>
<p>The longest name is PQRS, but there are 3 options for shortest named city. Choose ABC, because it comes first alphabetically.</p>

<h5>Note</h5>
<p>You can write two separate queries to get tge desired output. It need not be a single query</p>
