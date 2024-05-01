# ![[tktk Module Name] - Exercise](./assets/hero.png)

## 1. Account Balance Exercise

Using TDD, complete the following exercise.

Write the following tests for the `Account` class:

- `shouldIncreaseMyBalanceWhenIDepositMoney` - This test should create an `Account` object, deposit $50, and then check the balance.
- `shouldDecreaseMyBalanceWhenIWithdrawMoney` - This test should create an `Account` object, deposit $100, withdraw $50, and then check the balance.
- `shouldNotDecreaseMyBalanceWhenIWithdrawMoneyAndDoNotHaveEnoughToCoverTheWithdrawal` - This test should create an `Account` object, deposit $50, withdraw $100, and then check the balance.

For each of the test cases:

1. Implement the test for that test case. Uncomment it and add a test code inside it.
2. Fix compile errors.
3. Watch the test fail.
4. Write now code that you expect to make the test pass.
5. Watch the test pass. If any of your tests fail, you should repeat step #4.
6. Commit your changes and go back to Step #1 for the next test case.

| Given                     | When            | Then                                |
|---------------------------|-----------------|-------------------------------------|
| I have $100 in my account | I deposit $50   | I see that my account contains $150 |
| I have $100 in my account | I withdraw $50  | I see that my account contains $50  |
| I have $50 in my account  | I withdraw $100 | I see that my account contains $50  |

### 2. Factorial Exercise

Using TDD, complete the following exercise.

Write the following tests for the `Factorial` class:

- `shouldReturnOneWhenNumberIsOne` - This test should create a `Factorial` object, compute the factorial of 1, and then check the result.
- `shouldReturnTwoWhenNumberIsTwo` - This test should create a `Factorial` object, compute the factorial of 2, and then check the result.
- `shouldReturnOneWhenNumberIsZero` - This test should create a `Factorial` object, compute the factorial of 0, and then check the result.
- `shouldReturnSixWhenNumberIsThree` - This test should create a `Factorial` object, compute the factorial of 3, and then check the result.
- `shouldThrowIllegalArgumentExceptionWhenNumberIsNegative` - This test should create a `Factorial` object, compute the factorial of -1, and then check that an `IllegalArgumentException` is thrown.

For each of the test cases:

1. Implement the test for that test case. Uncomment it and add a test code inside it.
2. Fix compile errors.
3. Watch the test fail.
4. Write now code that you expect to make the test pass.
5. Watch the test pass. If any of your tests fail, you should repeat step #4.
6. Commit your changes and go back to Step #1 for the next test case.
