## How to Scan the Project:
1. To compile, run:
```
mvn clean compile test-compile -DskipTests
```
2. To initate the scan, run:
```
mvn org.sonarsource.scanner.maven:sonar-maven-plugin:sonar \
  -DskipTests
```

For the latest information about Hadoop, please visit our website at:

   http://hadoop.apache.org/

and our wiki, at:

   https://cwiki.apache.org/confluence/display/HADOOP/
