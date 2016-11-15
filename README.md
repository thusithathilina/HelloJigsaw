# HelloJigsaw

##How to compile
Go to the project root.
Create a directory
```
mkdir mods
```
Then compile the project with below command
```
javac -d mods --module-source-path ../HelloJigsaw $(find  -name "*.java")
```

##How to Run
```
java -p mods -m org.wso2.jigsaw.main/org.wso2.jigsaw.main.Main
```