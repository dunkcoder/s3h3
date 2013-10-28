s3h3
====

##### spring3 mvc and hibernate3

##### execute below batch to deploy irontracksql for runtime
```java
copy irontracksql.jar ${S3H3_HOME}\WEB-INF\lib\
copy irongrid.properties ${S3H3_HOME}\WEB-INF\lib\
xcopy lib\*.* ${S3H3_HOME}\WEB-INF\lib\lib\ /s/e
```
