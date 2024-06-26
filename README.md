# Chess Project

This is a chess game project written in Java. Below is a detailed description of the project structure and the purpose of each file and directory.

## Project Structure

### Directories

- **gradle/wrapper/**
  - Contains Gradle Wrapper files, which allow the project to be built using a specific version of Gradle without requiring the user to install Gradle manually.
  - **gradle-wrapper.jar**: The Gradle Wrapper executable jar.
  - **gradle-wrapper.properties**: Configuration properties for the Gradle Wrapper.

- **src/**
  - Contains the source code for the project.
  - **main/java/XXLChess/**
    - **App.java**: The main application class that initializes and runs the game.
    - Other source files related to the chess game logic (e.g., Board.java, Chess.java, Game.java, Player.java).

### Files

- **build.gradle**
  - The build script for Gradle, which includes dependencies and build configurations for the project.

- **config.json**
  - Configuration file for the application, contains settings and parameters required by the game.

- **gradlew**
  - The Unix shell script for the Gradle Wrapper, used to build the project on Unix-like systems.

- **gradlew.bat**
  - The Windows batch script for the Gradle Wrapper, used to build the project on Windows systems.

- **level1.txt**
  - A sample text file for level 1 data, which include the initial game setup.
