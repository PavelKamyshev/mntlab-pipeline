> Task :tasks

------------------------------------------------------------
All tasks runnable from root project
------------------------------------------------------------

Build tasks
-----------
assemble - Assembles the outputs of this project.
build - Assembles and tests this project.
buildDependents - Assembles and tests this project and all projects that depend on it.
buildNeeded - Assembles and tests this project and all projects it depends on.
classes - Assembles main classes.
clean - Deletes the build directory.
jar - Assembles a jar archive containing the main classes.
testClasses - Assembles test classes.

Build Setup tasks
-----------------
init - Initializes a new Gradle build.
wrapper - Generates Gradle wrapper files.

Documentation tasks
-------------------
javadoc - Generates Javadoc API documentation for the main source code.

Help tasks
----------
buildEnvironment - Displays all buildscript dependencies declared in root project 'mntlab-pipeline'.
components - Displays the components produced by root project 'mntlab-pipeline'. [incubating]
dependencies - Displays all dependencies declared in root project 'mntlab-pipeline'.
dependencyInsight - Displays the insight into a specific dependency in root project 'mntlab-pipeline'.
dependentComponents - Displays the dependent components of components in root project 'mntlab-pipeline'. [incubating]
help - Displays a help message.
model - Displays the configuration model of root project 'mntlab-pipeline'. [incubating]
projects - Displays the sub-projects of root project 'mntlab-pipeline'.
properties - Displays the properties of root project 'mntlab-pipeline'.
tasks - Displays the tasks runnable from root project 'mntlab-pipeline'.

Verification tasks
------------------
check - Runs all checks.
jacocoTestCoverageVerification - Verifies code coverage metrics based on specified rules for the test task.
jacocoTestReport - Generates code coverage report for the test task.
test - Runs the unit tests.

Rules
-----
Pattern: clean<TaskName>: Cleans the output files of a task.
Pattern: build<ConfigurationName>: Assembles the artifacts of a configuration.
Pattern: upload<ConfigurationName>: Assembles and uploads the artifacts belonging to a configuration.

To see all tasks and more detail, run gradle tasks --all

To see more detail about a task, run gradle help --task <task>
