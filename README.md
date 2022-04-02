
# Head First Java

Repository to save my progress while making the exercises from the book Head First Java from O'Reilly publisher. Although the book uses a different compiler and IDE, I am choosing VS Code with Microsoft Package extension for Java.

Let's hope I can finish this book :D

## Project Journal

### 2022-04-02

Since this book covers a lot of the basics of coding, I decided to only try code that interests me. Therefore, not all exercises and examples will be found except for the ones I believe they have something different. The Guessing Game is a good example, since I had to create more than one file to run the code: one file per class.

To compile this code, no difficulties. However, to execute I followed this [tutorial](https://www.baeldung.com/java-could-not-find-load-main-class).

In a nutshell: I'm using VS Code and git. To split my efforts in a logical way, I split the several codes in different folders (chapter01, chapter02, etc.). However, this causes JVM to understand that my code is in a package. That's why VS Code added a ```package``` statement at the beginning of my Java files.

To properly compile these files from repo folder.

```bash
javac chapter02/theGuessingGame/*.java
```

And to run the program

```bash
java chapter02.theGuessingGame.GameLauncher
```

In this way, JVM will be able to find the ```main``` method from ```GameLauncher``` to run.

### 2022-04-01

To install the Oracle JDK 17 in Ubuntu 20.04, I had to use the instructions from this [page](https://www.linuxcapable.com/pt/como-instalar-java-17-lts-jdk-17-no-ubuntu-20-04/).
