===========================================
To enable the compaction:
===========================================

set hive.input.format=org.apache.hadoop.hive.ql.io.CombineHiveInputFormat;
set mapred.min.split.size=100000000;
