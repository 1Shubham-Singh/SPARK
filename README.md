# SPARK
Learning Apache Spark from fundamentals to advanced concepts with hands-on projects and real-world data processing use cases.4
@@ -1,2 +1,14 @@
 # SPARK
 Learning Apache Spark from fundamentals to advanced concepts with hands-on projects and real-world data processing use cases.
+#1.HOW TO CREATE SPARK SESSION
+from pyspark.sql import SparkSession
+spark_session = SparkSession.builder.appName("Spark DataFrames").getOrCreate()
+#HOW TO CHECK VERSION
+spark_session.version
+#2.WHAT IS PRE-CREATED SPARK SESSION here (spark) is pre-created spark session
+spark.version
+#3.HOW TO USE SPARK SESSION TO READ TABLE DAT
+df = spark.table("dev.spark_db.diamonds")
+#HOW TO DISPLAY THE DATA WITH FUNCTION EX:-show(),display()
+spark.show()
+spark.display()
\ No newline at end of file
