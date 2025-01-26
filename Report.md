# Homework Aloha World Report

The following report contains questions you need to answer as part of your submission for the homework assignment. 


## Design Doc
Please link your UML design file here. See resources in the assignment on how to
link an image in markdown. You may also use [mermaid] class diagrams if you prefer, if so, include the mermaid code here.  You DO NOT have to include Greeting.java as part of the diagram, just the AlohaWorld application that includes: [AlohaWorld.java], [Greeter.java], and [ConsoleView.java]
[![](https://mermaid.ink/img/pako:eNp9VF1v2jAU_SuWn0BNEAmQJnmYFqXdGimDqdBV3Zgqk7iJ22B3junGEP3tc76G-UpewPcen3N9fH03MGIxhi6MMpTnVwQlHC3nFMivjAAvYym6ZzyLwaaKF99FLpAgEVgiQjtTwQlNfvwEiCd5F7wxEu-Q-o6g063C2zlVFXxGc5bhbwT_ViX0WuKJUJSBaYQoxRxMfW88vr49BwtJLt6ret5BOPG9MJg9PE6-zoLJeKpsUjSbqtRjJViM0RJ3uqDiOokIWYQyItYSRag4hkQpjl5uV9RLCpO6YMGkIqLHwFcpIT5zjIWUqt0ESb1W_TwwrtwiPVFNq92qOKg8g5KTKiCriz42cM-6BlYEz3ld0N14914QtCH8m2DstQGCmRc-tAGurj95d-HssblOxcDagY5y3m57WgOqCyq45c5bL1vJ7VEfvIOL8kJPspeJujsAyiNCJjRbHyN1pY4qd4ru4-QNc05iDFKUp7583Uc17yD41wpleWeyeMaRAGzxfKpNd3DBzusqxRVdIyFqRx00sDJVdP3D3ghwwV2O85OwpuFd4HOMRINSd-_DKiaowSXmclTFcs6Vj2UORYrl24Cu_Bsj_jKHc7qVOLSSR1zTCLqCr7AGOVslKXSfpElytXqNpWo9JP9HXxH9ztiy2SKX0N3AP9C1zZ5jjgzHdCzHGTmWrcE1dPWh0-9djgamZfcNw7YG5uVWg39LBqNnGcbANvv2sN-3RkN7oEEcE8H4l3pKFz_bf8EbxU0?type=png)](https://mermaid.live/edit#pako:eNp9VF1v2jAU_SuWn0BNEAmQJnmYFqXdGimDqdBV3Zgqk7iJ22B3junGEP3tc76G-UpewPcen3N9fH03MGIxhi6MMpTnVwQlHC3nFMivjAAvYym6ZzyLwaaKF99FLpAgEVgiQjtTwQlNfvwEiCd5F7wxEu-Q-o6g063C2zlVFXxGc5bhbwT_ViX0WuKJUJSBaYQoxRxMfW88vr49BwtJLt6ret5BOPG9MJg9PE6-zoLJeKpsUjSbqtRjJViM0RJ3uqDiOokIWYQyItYSRag4hkQpjl5uV9RLCpO6YMGkIqLHwFcpIT5zjIWUqt0ESb1W_TwwrtwiPVFNq92qOKg8g5KTKiCriz42cM-6BlYEz3ld0N14914QtCH8m2DstQGCmRc-tAGurj95d-HssblOxcDagY5y3m57WgOqCyq45c5bL1vJ7VEfvIOL8kJPspeJujsAyiNCJjRbHyN1pY4qd4ru4-QNc05iDFKUp7583Uc17yD41wpleWeyeMaRAGzxfKpNd3DBzusqxRVdIyFqRx00sDJVdP3D3ghwwV2O85OwpuFd4HOMRINSd-_DKiaowSXmclTFcs6Vj2UORYrl24Cu_Bsj_jKHc7qVOLSSR1zTCLqCr7AGOVslKXSfpElytXqNpWo9JP9HXxH9ztiy2SKX0N3AP9C1zZ5jjgzHdCzHGTmWrcE1dPWh0-9djgamZfcNw7YG5uVWg39LBqNnGcbANvv2sN-3RkN7oEEcE8H4l3pKFz_bf8EbxU0)



### Program Flow
Write a short paragraph detailing the flow of the program in your own words. This is to help you understand / trace the code (and give you practice of something called a code walk that will be required in this course).

This program is designed to greet a user based on the location information they provided.<br>
The program execute by the steps below.<br>
* Ask user for their name
* Ask user the locality they want to choose
* Return the greeting message that is corresponded to the chosen locality 
* Ask user if they want to be greeted again
   * If yes, restart from step2
   * If no, the program will be terminated

## Assignment Questions

1. List three additional java syntax items you didn't know when reading the code.  (make sure to use * for the list items, see example below, the backtick marks are used to write code inline with markdown)
   <br><br>**Example**
   * Final[^1]
   * Math[^2]
   <br><br>**My example**
   * Static[^3]
   * Private constructor[^4]
   * Override[^5]<br>
   

2. For each syntax additional item listed above, explain what it does in your own words and then link a resource where you figured out what it does in the references section. 

    * The `Static` keyword means that the member is belonged to the class itself. That means it can be accessed without being instantiated.
    * The `Override` keyword let a subclass provide a specific implementation that is already defined in the superclass
    * The `Private` constructor prevents a class being instantiated. 

3. What does `main` do in Java? 

    The main function is the entry point of a program. It contains codes to execute and call other methods.

4. What does `toString()` do in Java? Why should any object class you create have a `toString()` method?

    The `toString()` returns textual representation of a class. The result is usually informative for human to read in sake of debugging.

5. What is javadoc style commenting? What is it used for? 

    It is an API documentation generator. It is meant to create for explaining implementation details 

6. Describe Test Driving Development (TDD) in your own words. 

    Test Driving Development means developer writes automative unit test before writing the actual code that needs to be tested.  

7. Go to the [Markdown Playground](MarkdownPlayground.md) and add at least 3 different markdown elements you learned about by reading the markdown resources listed in the document. Additionally you need to add a mermaid class diagram (of your choice does not have to follow the assignment. However, if you did use mermaid for the assignment, you can just copy that there). Add the elements into the markdown file, so that the formatting changes are reserved to that file. 


## Deeper Thinking Questions

These questions require deeper thinking of the topic. We don't expect 100% correct answers, but we encourage you to think deeply and come up with a reasonable answer. 


1. Why would we want to keep interaction with the client contained to ConsoleView?
   <br>Keeping interaction with client contained to ConsoleView provided a clean and maintainable architecture. It increases flexibility and reusability of the program. That's said, if we want to modify the client interaction, the modification will be contain in the ConsoleView class. It is not necessary to change other class.


2. Right now, the application isn't very dynamic in that it can be difficult to add new languages and greetings without modifying the code every time. Just thinking programmatically,  how could you make the application more dynamic? You are free to reference Geeting.java and how that could be used in your design.
   <br><br>The program is now with the fixed members in it (i.e.USA, Hawaii, China, Italy). The program doesn't allowed new location information being added. One way to approach this issue is to modify Greeter class then allow user to add more location. Another approch is to include Greeting class in the program which provides a way to let user to costumize their greeting message.


> [!IMPORTANT]
>  After you upload the files to your github (ideally you have been committing throughout this progress / after you answer every question) - make sure to look at your completed assignment on github/in the browser! You can make sure images are showing up/formatting is correct, etc. The TAs will actually look at your assignment on github, so it is important that it is formatted correctly.


## References

[^1]: Final keyword in Java: 2024. https://www.geeksforgeeks.org/final-keyword-in-java/. Accessed: 2024-03-30. 

[^2]: Math (Java Platform SE 17). https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Math.html. Accessed: 2024-03-30.

[^3]: Static Keyword in Java https://www.geeksforgeeks.org/static-keyword-java/ Accessed: 2025-01-25.

[^4]: Overriding in Java https://www.geeksforgeeks.org/overriding-in-java/ Accessed: 2025-01-25.

[^5]: Private Constructors in Java https://www.baeldung.com/java-private-constructors Accessed: 2025-01-25.


<!-- This is a comment, below this link the links in the document are placed here to make ti easier to read. This is an optional style for markdown, and often as a student you will include the links inline. for example [mermaid](https://mermaid.js.org/intro/syntax-reference.html) -->
[mermaid]: https://mermaid.js.org/intro/syntax-reference.html
[AlohaWorld.java]: src/main/java/student/AlohaWorld.java
[Greeter.java]: src/main/java/student/Greeter.java
[ConsoleView.java]: src/main/java/student/ConsoleView.java