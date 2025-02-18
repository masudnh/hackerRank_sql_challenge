<h3>Easy</h3><hr>

<p>Query the following two values from the STATION table</p>
<p>1. The sum of all values in LAT_N rounded to a scale of 2 decimal places.</p>
<p>2. The sum of all values in LONG_W rounded to a scale of 2 decimal places.</p>

<h5>Input Format</h5>
<p>The STATION table is described as follows:</p>
<p>Table: <code>Station</code></p>


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

<p>Where LAT_N is the northen latitude and LONG_W is the western longitude</p>
<h5>Output Format</h5>
<p>Your result must be in the form:</p>
<pre>
lan lon
</pre>

<p>Where lat is the sum of all values in LAT_N and lon is the sum of all values in LONG_W. Both result must be rounded to a scale of 2 decimal places.</p>
