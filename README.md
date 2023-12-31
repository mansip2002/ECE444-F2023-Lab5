# ECE444-F2023-Lab5
Code tutorial from: https://github.com/mjhea0/flaskr-tdd

# Unit Test Cases
The test cases can be found here: https://github.com/ECE444-2023Fall/project-1-web-application-design-group25-pixelpals/blob/main/tests/test_app.py

They test the basic functionality of the search feature and are called: test_invalid_search_results, test_valid_search_results, and test_empty_search

# Pros and Cons of TDD
Pros of TDD:
The main pros of test-driven development are higher product quality, test suite quality, and overall productivity. By writing failing tests, code to pass the test, and then refactoring, developers can check for duplication and code smells multiple times throughout the development process. This process, especially refactoring helps improve the overall structure of the code while checking for defects. Code redundancy is also reduced because you are only writing the minimum amount of code needed to pass the tests. The resulting code is easy to test, and little developer time is wasted on unnecessary code, improving their productivity. The cycle helps improve the test suite as developers can re-write or add more tests because the tests are also being tested in the process. This leads to improved overall productivity, readability, and maintainability of the product. 

Cons of TDD:
The main cons of TDD are centred around the practical use of the development process, writing inconsistencies in the tests, and maintaining the test suites. Initially, starting TDD is cumbersome and time-consuming because it requires thinking about the complete design of interfaces before they’re created. In addition, it requires a lot of maintenance over time if key parts of the codebase change. If the codebase changes and the tests start to fail, time will need to be invested to make sure the tests pass too. Similarly, if team turnover is high, it can also be difficult to justify onboarding and maintaining the test suites. Finally, TDD relies on the developers catching or thinking about defects in the codebase. If developers don’t write thorough tests, tests that are trivial or not complete, they may not catch any bugs. 
