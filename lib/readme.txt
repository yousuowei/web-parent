关于工程缺少jar 文件解决方法
cmd 命令 cd　到当前文件目录，运行下面命令
mvn install:install-file -DgroupId=org.springside -DartifactId=springside-special -Dversion=1.0 -Dpackaging=jar -Dfile=springside-special.jar
mvn install:install-file -DgroupId=com.baidu -DartifactId=bcs-sdk-java -Dversion=1.4.5 -Dpackaging=jar -Dfile=bcs-sdk-java_1.4.5.jar