# Why is Apache Spark implemented in Scala?

标签（空格分隔）： 未分类

---
By:Matei Zaharia, CTO @ Databricks
When we started Spark, we wanted it to have a concise API for users, which Scala did well. At the same time, we wanted it to be fast (to work on large datasets), so many scripting languages didn't fit the bill. Scala can be quite fast because it's statically typed and it compiles in a known way to the JVM. Finally, running on the JVM also let us call into other Java-based big data systems, such as Cassandra, HDFS and HBase.

Since we started, we've also added APIs in Java (which became much nicer with Java 8) and Python.




