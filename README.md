<h1>CSE 511 - Data Processing at Scale</h1>


<h3>Project description</h3>
The project was aimed to setup a spark cluster with HDFS and run SparkSQL queries (geo-spatial) on the it.

<br>Native spark cluster was used as cluster manager.</br>
<br>Hadoop Distributed File System (HDFS) was used as distributed storage system.</br>
<br>The setup was done using Amazon EC2 virtual machines as nodes.</br>
<br>Spatial queries such as range query, range join query, distance query, distance join query, hot zone analysis and hot cell analysis were executed.</br>
<br>Spatial queries were executed by implementing user defined functions such as ST_contains and ST_within in Scala.</br>
<br>ST_contains takes a point and a rectangle and returns a boolean indicating whether the point is inside the rectangle.</br>
<br>ST_within takes two points and a distance and returns a boolean indication whether the distance between the points is not more than the distance provided.</br>
<br>Technology used: Apache Spark, Hadoop Distributed File System (HDFS), Scala, sbt build tool, Amazon EC2.</br>
