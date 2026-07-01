7th
mkdir maven2
cd maven2
type nul > pom.xml
[mkdir src\main\java]
[type nul > src\main\java\app.java]
tree /f
---relut tree---

app.java(code)
package com.example;

public class App {
    public static void main(String[] args) {
        System.out.println("Hello Maven!");
    }
}

again deskton pom.xml
pom.xml(code)
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0
         https://maven.apache.org/xsd/maven-4.0.0.xsd">

    <modelVersion>4.0.0</modelVersion>

    <groupId>com.example</groupId>
    <artifactId>MyProject</artifactId>
    <version>1.0</version>

</project>

mvn compile
mvn test
mvn package
mvn install
mvn clean package
git init
gig add .
git commit -m "update"
go to github
create repo maven2
copy n padste in termi
git push -u origin main

-----------------------
files li desktop path erase n type cmd
cmd will open
step 2 3 4 5 6 7 
go to files open maven2 -> src ->main ->java ->muycyyuv
vs code will open
app.java code ide
go to file open maven2 ->pom.xml(open with vscode) code will open
close vs
open terminal(step 12 - 20)
(21-23)
now copy that url
open jenkins
new item (maven2)
click maven project
ok
git
url
save
trigger ali {1st opetion n bulid pe[****] n github hook trigger}
envi li {add ...}
goal n option {clean compile}
save
build now
console li sucees .

