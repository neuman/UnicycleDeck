# UnicycleDeck
A Playing Card Deck sample / boilerplate project for Decko. Contains 52 cards, boxart and instructions for poker. 

# Styles
- **bootstrap.css:** Bootstrap is a framework which provides a way to build responsive web content. 
- **decko.css:** This file fontains css for decko to use in printing, previewing and export. Only mess with these if you know what you're doing.
- **custom.css:** This is where you should put the specifics of your project.


# Templates
 - Templates are written [handlebars style](https://handlebarsjs.com/guide/)
     - {{ variable }}
 - CSS and Javascript files can be linked following normal html syntax within the head block. 

```java
import java.util.Scanner;

public class HelloWorld {

    public static void main(String[] args) {

        // Creates a reader instance which takes
        // input from standard input - keyboard
        Scanner reader = new Scanner(System.in);
        System.out.print("Enter a number: ");

        // nextInt() reads the next integer from the keyboard
        int number = reader.nextInt();

        // println() prints the following line to the output screen
        System.out.println("You entered: " + number);
    }
}
```
```
  {{#block head}}
    <link rel="stylesheet" href="styles/bootstrap.css">
    <link rel="stylesheet" href="styles/decko.css">
    <link rel="stylesheet" href="styles/project.css">
    <link rel="stylesheet" href="fontawesome/css/all.css">
  {{/block}}  
```

 - Noodles