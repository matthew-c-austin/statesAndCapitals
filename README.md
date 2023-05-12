# States and State Capitals Trivia -- Lab 19

- Run test with `./gradlew test`

This doesn't give too much information though. To see the specifics of the test you need to run with more info turned on and the `clean` command needs to be added, or it won't give results a second time until code has changed. Even then a lot of extra information is displayed. Use grep to isolate the output of the tests:

- `./gradlew clean test --info | grep -A 1 STANDARD_OUT `