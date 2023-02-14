# codesignal_container

Codewriting

Welcome to the pre-certification practice task! This task is designed to be a playground that allows you to get acquainted to the testing environment and practice the functionalities of the platform before your certification.

To customize the editor settings and see the editor hotkeys, check out the IDE Settings tab  in the lower left corner of the page.

Scenario
Your task is to implement a simple container of integer numbers. You are given some template code in the Container class within the container.py file. You should implement any empty methods of this class, which correspond to the operations described below.

Unit tests are already implemented in the basicTests.py and containerTests.py files, so feel free to open them and get familiar with the details. Note that these unit tests use python3's unittest framework. To run these tests, you can use the following options associated with the RUN button located on the bottom right corner:


If you'd like to receive a raw report of tests, choose the Run option. The tests in this report will always be ordered in the same way, and will contain all debug output you've printed to the console.
If you'd like to receive test results with more structure, choose the Run Pretty Results option. Note that debug output is not supported in this option.
If you'd like to run your project in a custom way, choose the Run Custom Script option. This will create a new main.sh file that is expected to contain the execution logic. The Run Custom Script button will execute this custom script when clicked.
The auto-generated main.sh file already contains few examples that can be uncommented and executed
You can also use the following script to execute the first basic test only:
cd tests && python -m unittest basicTests.DemoICATest.test_basic1
For more information, check out the Readme tab  on the left.
Partial credit will be granted for each unit test passed, so press Submit often to run tests and receive partial credits for passed tests. Please check tests for requirements and argument types.

Operations
The program starts with an empty container.

ADD <value> should add the specified integer value to the container.

DELETE <value> should attempt to remove the specified integer value from the container. If the value is present in the container, remove it and return True, otherwise, return False.

GET_MEDIAN should return the median integer - the integer value in the middle of the sequence after all integer value stored in the container are sorted from smallest to largest. If the length of the sequence is even, the leftmost integer from the two middle integers should be returned. If the container is empty, this method should raise a runtime exception.

[execution time limit] 3 seconds