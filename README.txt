## How to Scan the Project:
1. To compile, run:
```
mvn -pl hadoop-maven-plugins -am install -DskipTests
```
2. To initate the scan, run:
```
MAVEN_OPTS="-Xmx4g -XX:+UseG1GC" 
mvn org.sonarsource.scanner.maven:sonar-maven-plugin:sonar -DskipTests
```

For the latest information about Hadoop, please visit our website at:

   http://hadoop.apache.org/

and our wiki, at:

   https://cwiki.apache.org/confluence/display/HADOOP/
