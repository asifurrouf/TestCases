## DEFINITION

A test case is a set of conditions or variables under which a tester will determine whether a system under test satisfies requirements or works correctly.
The process of developing test cases can also help find problems in the requirements or design of an application.

## TEST CASE TEMPLATE

A test case can have the following elements. Note, however, that normally a test management tool is used by companies and 
the format is determined by the tool used.

| Attributes | Description |
| --- | --- |
| Test Suite ID | The ID of the test suite to which this test case belongs |
| Test Case ID | The ID of the test case |
| Test Case Summary | The summary / objective of the test case |
| Related Requirement | The ID of the requirement this test case relates/traces to |
| Prerequisites | Any prerequisites or preconditions that must be fulfilled prior to executing the test|
| Test Procedure | Step-by-step procedure to execute the test |
| Test Data | The test data, or links to the test data,that are to be used while conducting the test. |
| Expected Result | The expected result of the test |
| Actual Result | The actual result of the test; to be filled after executing the test |
| Status | Pass or Fail. Other statuses can be ‘Not Executed’ if testing is not performed and ‘Blocked’ if testing is blocked |
| Remarks | Any comments on the test case or test execution |
| Created By | The name of the author of the test case |
| Date of Creation | 	The date of creation of the test case |
| Executed By | The name of the person who executed the test |
| Date of Execution | The date of execution of the test |
| Test Environment | The environment (Hardware/Software/Network) in which the test was executed |

## TEST CASE Example

| Attributes | Description |
| --- | --- |
| Test Suite ID | TS001 |
| Test Case ID | TC001 |
| Test Case Summary | To verify that clicking the Generate Coin button generates coins |
| Related Requirement | RS001 |
| Prerequisites | User is authorized >> Coin balance is available |
| Test Procedure | Select the coin denomination in the Denomination field. >> Enter the number of coins in the Quantity fiel >> Click Generate Coin. |
| Test Data	 | Denominations: 0.05, 0.10, 0.25, 0.50, 1, 2, 5 >> Quantities: 0, 1, 5, 10, 20  |
| Expected Result	 | Coin of the specified denomination should be produced if the specified Quantity is valid (1, 5) >> A message ‘Please enter a valid quantity between 1 and 10’ should be displayed if the specified quantity is invalid.|
| Actual Result	 | If the specified quantity is valid, the result is as expected. >> If the specified quantity is invalid, nothing happens; the expected message is not displayed |
| Status | Fail |
| Remarks | This is a sample test case. |
| Created By | John Doe |
| Date of Execution | 01/14/2020 |
| Executed By | Jane Roe |
| Date of ReExecution | 02/16/2020 |
| Test Environment | OS: Windows >> Browser: Chrome |

## WRITING GOOD TEST CASES

* As far as possible, write test cases in such a way that you test only one thing at a time. Do not overlap or complicate test cases. Attempt to make your test cases ‘atomic’.
* Ensure that all positive scenarios and negative scenarios are covered.
* Language:   
	Write in simple and easy to understand language.
        Use active voice: Do this, do that.
        Use exact and consistent names (of forms, fields, etc).
* Characteristics of a good test case:
        Accurate: Exacts the purpose.
	Economical: No unnecessary steps or words.
        Traceable: Capable of being traced to requirements.
	Repeatable: Can be used to perform the test over and over.
	Reusable: Can be reused if necessary.

