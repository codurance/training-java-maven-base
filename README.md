# How to use this repo during the training

1. Navigate to the repo here [https://github.com/codurance/training-java-maven-base](https://github.com/codurance/training-java-maven-base)
2. Click the Fork button from the top right corner of the page
3. Chose to fork the code to your personal github account
4. You can rename the github repo to the kata name from the Settings tab. e.g. fizzbuzz-kata
5. Clone the code from the forked repository:
```bash
git clone git@github.com:<youGithubHandle>/fizzbuzz.git
cd fizzbuzz
./mvnw clean install
```
6. You can rename the github repo to the kata name from the Settings tab
7. Copy and paste the bash instructions to the team so they can use your forked repo


# Java/Maven + JUnit5 Kata Seed

## Install & Run All tests
`./mvnw clean test`

## Only run specific Kata unit test
* `./mvnw clean test -Dtest="TheFirstUnitTestClass"`
* `./mvnw clean test -Dtest="TheSecondUnitTestClass#the_test_method"`


## Import it into IntelliJ IDEA
* `idea .`


##
The projects presented are over-simplifications. Real production apps will have dozens if not more dependencies lying around
