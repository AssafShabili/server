@echo off
java -jar --add-exports=java.base/sun.security.util=ALL-UNNAMED --add-opens=java.base/java.util.jar=ALL-UNNAMED --add-opens=java.base/java.lang=ALL-UNNAMED -Xmx6G -Xms6G mohist-1.16.5-842-server.jar launchedWithJava16
pause
