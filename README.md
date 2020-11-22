1. Run `gradle init` 
    - Select project type - `2: application` 
    - For the other questions, press enter to use the default values
2. Explore the build
    - Find the task to run the application using `./gradlew tasks`
    - Run the application using the wrapper and the task you found, it should print `Hello World!`
    - Run the tests of the application
    - Create a build scan with `./gradlew build --scan` and explore the timeline. Which tasks have been executed?
3. Modify the project - `app/build.gradle` file
    - Change your project to apply  the`java-library` instead of the `application` plugin
    - You need to remove the application specific configuration `application {}`
    - Run `./gradlew tasks` and `./gradlew build --scan` again. What changed?
