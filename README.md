# Homework


- Project with a Java file
- .gitignore created ignoring .idea
- All done remotely


## Java file

Create file with [InteliJ](https://www.jetbrains.com/idea/) using the "Hello World" template.


```java
class Main{
    
    public static void main(String args[]) { 
        System.out.println("Hello, World"); 
    } 
           
} 
```

Adding the single file in the /src/ directory to the git project and commiting it.

## .gitignore file

Creating a .gitignore directly from Github with the following code:

```.gitignore
# IntelliJ Idea files
.idea
```

Commiting and pulling it to your own machine.


## Version Control

In order to make sure we have the same files on our own machine and the Github project we use the following two git bash commands:

```Bash
git push -u origin master

```
and
```Bash
git pull origin master

```
