# hadoop_update

hadoop fs -put filename.txt filename.txt

hadoop jar hogile.jar <packagename.classname> input.txt output

hadoop fs -ls output

hadoop fs -cat output/port -r -0000

///////////

row format DELIMITED
FIELDS TERMINATED BY STORED IN ORG>
LOAD DATA LOCAL INPATH ........... INTO TABLE <tablename>

/////
  CREATE EXTERNAL stored by 'org.apache' 
  with seredproperties
  "hbase.columns.mapping"=":key
