"# discover-gradle"

# Install Gradle - from - https://gradle.org/releases/

Execute following commands to setup project -

> gradle init

Above command will prompt for few inputs, provide those & proceed

> gradlew.bat help

> gradlew.bat tasks

Above command will show all tasks we can viz., commands

> gradlew.bat dependencies

Above command will show all the project dependencies

====================================================================================

## Build Setup tasks

---

init - Initializes a new Gradle build.
wrapper - Generates Gradle wrapper files.

## Help tasks

buildEnvironment - Displays all buildscript dependencies declared in root project 'discover-gradle'.
dependencies - Displays all dependencies declared in root project 'discover-gradle'.
dependencyInsight - Displays the insight into a specific dependency in root project 'discover-gradle'.
help - Displays a help message.
javaToolchains - Displays the detected java toolchains.
kotlinDslAccessorsReport - Prints the Kotlin code for accessing the currently available project extensions and conventions.
outgoingVariants - Displays the outgoing variants of root project 'discover-gradle'.
projects - Displays the sub-projects of root project 'discover-gradle'.
properties - Displays the properties of root project 'discover-gradle'.
resolvableConfigurations - Displays the configurations that can be resolved in root project 'discover-gradle'.
tasks - Displays the tasks runnable from root project 'discover-gradle'.

# To see all tasks and more detail, run gradlew tasks --all

====================================================================================

# Some imp tasks -

> gradlew.bat jar
> gradlew.bat test
> gradlew.bat assemble
