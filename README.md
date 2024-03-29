# Markdown Console Application
## 1. Overview:
<details>
    <summary>Click here to see the overview</summary>

### Description
This is a simple console application for converting our (custom) markup into HTML markup, specifically, tags. This application expects to receive a file with markup and converts it into HTML markup, then outputs the result to the console.

### Capability
This project has good potential for further development, at least for educational purposes. It's possible to: 
1. Implement a web server with a nice UI
    - Implement a user friendly interface to avoid file path
    - Avoid console output (It's not a good practice as is not a user friendly)
2. Optimize the code
   - Refactoring
   - Better methods names
3. Better logic implementation.
    - Better converter logic implementation
    - Additional Unit testing
</details>

## 2. Steps to execute script:
<details>
   <summary>Click here to see the steps to run the app</summary>

To avoid building the app I decide to build It and add the JAR file to the git. I did It as to compile the java project we should java a **JDK (Java Dev Kit)**.<br>
However, to run the app we should use only **JRE (Java Runtime Engine)** <br>
<h3>To run this application, you should:</h3>
   - Install the JRE as java apps needs a JRE to run any app
   - Open the terminal in the project directory
   - Create a .txt file with input data
   - To run the app you should execute the following cmd: <br>
  ``
  java -jar .\target\MarkDown-1.0.jar
  ``
- After that you should input a file path. The file format - ***.txt!***
</details>

## 3. Instruction:
<details>
   <summary>Click here to see the instruction</summary>

So, you after execution the cmd. You will see the text to enter file path.<br>
If you will enter a wrong path or wrong file format, the app will give you one more chance : )

If you entered a right file path, I can have a 2 cases:
1. If file have everything correct - It swill output a right converted app to the console
2. If we have some format errors or smth else, we will get the error code and the app will be finished with non-zero code (1)

### Important!
***The file format should be .txt!***

</details>

## 4. Revert-commits:
I've done two revert-commits.<br>
The first one I deleted a wrong method and pushed It to the git by chance.<br>
***You can find the first one revert-commit [here](https://github.com/Farid545/Mark-Down/commit/5fee83863bba9ee2228b0b31a7e5846751610440)!***

The second one I've wrote a wrong method to preceded with Paragraphs, so I decided to revert the commit and wrote a new correct method.
***You can find the second one revert-commit [here](https://github.com/Farid545/Mark-Down/commit/3197dd342769de26150d5c3a53d27cbac078e1ec)!***