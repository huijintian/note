#### 服务启动

-Dspring.profiles.active=dev

##### jvm

-server -Xms1024m -Xmx1024m -Xmn768m -Xss128k -XX:surviorRatio=6 -XX:MaxpermSize=256m -XX:parllerGCThreads=8 
-XX:MaxTenuringThreshold=0 -XX:+UseConcmarkSweepGC
