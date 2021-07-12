# understanding package declaration
## compiling class using specific classpath
`javac -cp specific-classpath ocpstudy/ClassNeedSpecificClasspathToCompile.java -d generated_classes` output directory `generated_classes`

Explanation : `javac` compile `ocpstudy.ClassNeedSpecificClasspathToCompile` by using `ocpstudy.SpecificClasspathClass` from `specific-classpath` folder. it creates classes files on `generated_classes` folder.

## running class using specific folder
* compile first the classes by following previous step
* `java -cp generated_classes ocpstudy.ClassNeedSpecificClasspathToCompile` output `successfully load class from specific classpath`