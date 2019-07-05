# gradle-example
#1

1. 
When run ./gradlew build, got below error message:

FAILURE: Build failed with an exception.

* What went wrong:
Could not determine java version from '12.0.1'.

The reason is the default gradle version of this project is too low, it can be found in: gradle-example/gradle/wrapper/gradle-wrapper.properties

After updating the gradle version by: gradle wrapper --gradle-version=4.8, error is gone.

