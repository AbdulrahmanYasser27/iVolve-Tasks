# Lab 1: Building and Packaging Java Applications with Gradle

This lab demonstrates how to build, test, and package a Java application using Gradle.

## Prerequisites
- Java Development Kit (JDK) installed (version 8 or higher recommended).
- Gradle installed and added to your system PATH.
- Git installed.

## Steps

1. Install Gradle  
   Follow the official installation guide: https://gradle.org/install  
   Verify installation:  
   gradle -v

   ![Gradle Installation and Setup](attachments/n9MfzbJPQ8nqPcpDvMTrn.png)

2. Clone the Source Code  
   git clone https://github.com/Ibrahim-Adel15/build1.git  
   cd build1

3. Run Unit Tests  
   gradle test

4. Build the Application  
   gradle build  
   The artifact will be located at: build/libs/ivolve-app.jar

5. Run the Application  
   java -jar build/libs/ivolve-app.jar

   ![Gradle Build and Run Output](attachments/FbxmBkqDiXGMYvE8682rF.png)

6. Verify the Application  
   Check the console output or application behavior to confirm it is working as expected.

## Expected Outcome
- Gradle successfully installed and verified.
- Repository cloned locally.
- Unit tests executed with no failures.
- JAR file generated in build/libs/.
- Application runs correctly when executed with java -jar.

## Notes
- If Gradle is not installed globally, you can use the Gradle Wrapper included in the project:  
  ./gradlew build  
  ./gradlew test
- Ensure your JAVA_HOME environment variable is set correctly.
