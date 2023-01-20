# API Tests Java
Task #2 of the Yandex Graduation project.Practikum: **API**

It was necessary to test API for Stellar Burgers (https://stellarburgers.nomoreparties.site/).
API documentation: https://code.s3.yandex.net/qa-automation-engineer/java/cheatsheets/paid-track/diplom/api-documentation.pdf

**Creating a user:**
- Create a unique user;
- Create a user who is already registered;
- Create a user and do not fill in one of the required fields.

**User login:**
- login under an existing user,
- login with an incorrect username and password.

**Changing user data:**
- with authorization,
- without authorization,
For both situations, you need to check that any field can be changed. For an unauthorized user, it also means that the system will return an error.

**Creating an order:**
- with authorization,
- without authorization,
- with ingredients,
- without ingredients,
- with an incorrect hash of ingredients.

**Receiving orders from a specific user:**
- an authorized user,
- an unauthorized user.

Dependencies: JUnit 4, RestAssured and Allure.

A report was made in Allure.

Tests are run and passed.
All tests are independent.
The required test data is created before the test and deleted after it is executed.
An Allure report has been made.
Tests in test/java.
