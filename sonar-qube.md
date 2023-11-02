# SonarQube

Sonarqube is used for static testing means testing code without execution. It checks the code smells , code complexity, providing better solutions etc.

## Features of SonarQube

1. It can work with 25 different languages.
   Ex:- Java, .NET, JS, COBOL, php, Python, C++, Ruby, Cotlen, etc.

2. **Tricky Issues**
   a. **Detect Bugs**

   b. **Code Smells** - Code smells are the characteristic of code that indicates that there might be a problem caused by the code in future.
   But smells aren't necessarily bas, sometimes they are how a functionality works and there is nothing that can be done about it.

   c. **Security Vulnerability** - SonarQube can detect security issues that a code may face.
   Ex:- If a developer forgets to close an open SQL database OR If important information like username and password have been directly written in a code.

   d. **Activate Rules Needed** - You can create and maintain different rules that are specific to particular projects, there are known as Quality Profiles.

   e. **Execution Path** - Whenever there is Data flow in your program, and there is a lot of involvement between the different Modules.
   SonarQube can figure out if there are any tricky bugs in these execution paths.

3. **Enhanced Workflow (Ensure Better CI/CD)**
   a. **Automated Code Analysis** - Keeps working in the background from the development
   phase itself, monitoring and identifying errors.

   b. **Get access through Webhooks's & API** - To Initiate tests we do not need to come to SonarQube
   directly, we ean do that through an API call.

   c. **Integrate GitHub** - It can be directly integrated with your choice of version control software.
   Eg. GitHub

   d. **Analyze branched and Decorate pull requests** - It gives us a branch Level analysis, ie. it doesn't just analyze the master branch it also analyzes the other branches, identifying any errors.

4. **Built-in methodology**
   a. **Discover memory leaks** - it can show the memory leak in your application, if the application has a tendency to fail or go out of memory.
   This generally will happen slowly happen over a period of time.

   b. **Good Visualizer** - it has a goad way of visualizing, it gives simple overviews of the overall health of the code.
   ex. Number of bugs, Number of code smells and other details and a simple view.
