<style>
red { color: red }
h3 { color: yellow }
gray {color:gray}
orange {color:orange}
arial {font-family:arial}
white {color:white}
</style>

# <orange>ISTQB Fundementals of Testing</orange>

<br>

> <orange>KEYWORDS</orange>

<br>

- [Testing](#testing)
- [Debugging](#debugging)
- [Defect](#defect)
- [Error](#error)
- [Root Cause](#root-cause)
- [Quality Control](#quality-control)
- [Quality Assurance](#quality-assurance)
- [Testware](#testware)
- [Traceability](#traceability)
- [Validation](#validation)
- [Verification](#verification)
- [Test Basis](#test-basis)
- [Test Case](#test-case)
- [Test Suite](#test-suite)
- [Test Objectives](#test-objectives)
- [Test Data](#test-data)
- [Test Procedure](#test-procedure)
- [Test Process](#test-process)
- [Test Oracle](#test-oracle)
- [Test Condition](#test-condition)
- [Test Planning](#test-planning)
- [Test Monitoring and Control](#test-monitoring-and-control)
- [Test Analysis](#test-analysis)
- [Test Design](#test-design)
- [Test Implementation](#test-implementation)
- [Test Execution](#test-execution)
- [Test Completion](#test-completion)

<br><br>

### Testing

    Testing is Factual or computational operation used to investigate the validity of an assumption and an inference, the relevance of a procedure, or the validity of a correlation.

    Software testing is a way to assess the quality of the software and to reduce the risk of software failure in operation

<br>

### Debugging

    Debugging is the development activity that finds,analyzes,and fixes such defects.

<br>

### Defect

    A software bug arises when the expected result dont match with the actual results. ( fault-bug )
    Simply defined as a variance between expected and actual.
    The defect is a result of error.
    Error/Mistake ---> Defect/Fault/Bug ---> Failure

![Deffect](https://doyousue.com/wp-content/uploads/2015/12/Defect-lawyers1.jpg)

<br>

### Error

    An error is a mistake, misconception, or misunderstanding on the part of a software developer.
    In the category of software developer includes software engineers, programmers, analysts, and testers.

![Error](https://steamuserimages-a.akamaihd.net/ugc/957486694784677401/8EC2D9F49B6198F7252426CDF3F5C58962BEACA9/?imw=512&imh=288&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=true)

<br>

### Root Cause

    The root causes of defects are the earliest actions or conditions that contributed to creating the defects.

<br>

### Quality Control

    Quality Control(QC) involves various activities,including test activities,that support the achievement of appropriate levels of quality.
    QC cares about the final product itself.

<br>

### Quality Assurance

    Quality Assurance(QA) is typically focused on adherence to proper proceses.
    In QA we care about the process that we work on.

<br>

### Testware

    Testware is a sub-set of software with a special purpose, that is, for software testing, especially for software testing automation.

<br>

### Traceability

    Traceability is the ability to trace all processes from procurement of raw materials to production, consumption and disposal to clarify "when and where the product was produced by whom."
    Test conditions should be able to be linked back to their sources in the test basis, this is known as traceability.

<br>

### Validation

    Validation is determining if the system complies with the requirements and performs functions for which it is intended and meets the organization’s goals and user needs.
    Validation in testing is build the right product.

<br>

### Verification

    Verification makes sure that the product is designed to deliver all functionality to the customer.
    Verificaiton in testing is build the product right.

<br>

### Test Basis

    Test basis is defined as the source of information or the document that is needed to write test cases and also for test analysis
    Test Basis can also be defined as that data which is needed in order to start the analysis of the test.
    Typical Test Basis:
        * Requirement document
        * Test Plan
        * Codes Repository
        * Business Requirement

<br>

### Test Case

    A test case is a document, which has a set of test data, preconditions, expected results and postconditions, developed for a particular test scenario in order to verify compliance against a specific requirement.

<br>

### Test Suite

    Test suite is a container that has a set of tests which helps testers in executing and reporting the test execution status.

![Test Suites](https://www.tutorialspoint.com/software_testing_dictionary/images/test_suite.jpg)

<br>

### Test Objectives

    * To find defects and failures by reducing the level of risk of inadequate software quality.
    * Gaining confidence in and providing information to stakeholders about the level of quality.
    * To prevent defects.
    * To make sure that the end result meets the business and user requirements.
    * To gain the confidence of the customers by providing them a quality product.

<br>

### Test Data

    Test Data is data that is used to execute the tests on testware. Test data needs to be precise and exhaustive to uncover the defects.

<br>

### Test Procedure

    The document that describes the steps to be taken in running a set of tests and specifies the executable order of the tests is called a test procedure in IEEE 829, and is also known as a test script.

<br>

### Test Process

    Test process is a process rather than a single activity and it starts from test planning then designing test cases,preparing for execution and evulating status till the test closure.
        * Planning and Control
        * Analysis adn Design
        * Implementation and Execution
        * Evalutaing exit criteria and Reporting
        * Test Closure activities

![Test Process](https://cdn-images-1.medium.com/fit/t/1600/480/1*MyY0opFiV18C4ZwshJ1R3A.png)

<br>

### Test Oracle

    In computing, software engineering, and software testing, a test oracle (or just oracle) is a mechanism for determining whether a test has passed or failed. The use of oracles involves comparing the output(s) of the system under test, for a given test-case input, to the output(s) that the oracle determines that product should have. The term "test oracle" was first introduced in a paper by William E. Howden. Additional work on different kinds of oracles was explored by Elaine Weyuker.

<br>

### Test Condition

    Test Condition in software testing is the specification that a tester must follow for testing a software application. Test condition is a specific set of constraints which can contain functionalities like transactions, functions or structural elements for test cases in order to test the software application. Test conditions help to ensure that a software application is bug-free.

<br>

### Test Planning

    Test planning refers to planning the activities that must be performed during testing in order to achieve the objectives of the test.
    Test planning involces activities that define the objectives of testing abd the approach for meeting test objectives within constraints imposed by the context.

<br>

### Test Monitoring and Control

    Test monitoring involves the on-going comparison of actual progress aganist planned progress using any test monitoring metrics defined in the test plan.
        * Checking test results and logs aganist specified covreage criteria.
        * Assesing the level of componenet or system quality based on test result and logs.
        * Determining if more tests are needed.

<br>

### Test Analysis

    Test analysis is the process of looking at something that can be used to derive test information.
    Test analysis determines "what to test" in terms of measurable covreage criteria.

<br>

### Test Design

    Test design is a process that describes “how” testing should be done. It includes processes for the identifying test cases by enumerating steps of the defined test conditions.
    Test analysis answers the question "what to test?" while test design answers the quesiton "how to test?"
        * Designing and prioritizing test cases and sets of test cases
        * Identifying necessary test data to support test conditions and test cases
        * Desingning the test environment and identifying any required infastructure and tools
        * Capturing bi-directionnal traceability between the test basis,test conditions,and test cases

<br>

### Test Implementation

    The document that describes the steps to be taken in running a set of tests and specifies the executable order of the tests is called a test procedure in IEEE 829, and is also known as a test script.  When test Procedure Specification is prepared then it is implemented and is called Test implementation.
    Test design answers the question "how to test? while test implementation answers the quesiton "do we now have everything in place to run the tests?"
        * Developing ad prioritizing test procedures and potentially creating automated test scripts
        * Creating test suites from the test procedures and automated test scripts
        * Arranging the test suites within a test execution schedule in a way that results in efficient test execution
        * Building the test environment and verifying that everything needed has been set up correctly
        * Preparing test data and ensuring it is properly loaded in the test environment
        * Verifying and updating bi-directional traceability between the test basis,test conditions,test cases,test procedures,and test suites.

<br>

### Test Execution

    During the test execution, test suites are run in accordance with the test execution schedule
        * Executing tests either manually or by using test execution tool
        * Comparing actual results with expected results
        * Analyzing anomalies to establish their likely causes
        * Reporting defects based on the failures observed
        * Logging the outcome of test execution
        * Verifying and updating bi-directional traceability between the test basis,test conditions,test cases,test procedures,and test results

<br>

### Test Completion

    Test completion activities collect data from completed test activities to consolidate experince,testware,and any other relevant information.
        * Checking whether all defect reports are closed,entering change requests or product backlog items for any defects that remain unresolved at the end of test execuiton
        * Creating a test summary report to be communicated to stakeholders
        * Finalizing and archiving the test environment the test data the test infastructure and other testware for later reuse
        * Handing over the testware to the maintance teams,other project teams,and other stakeholders who could benefit from its use
        * Analyzing lessons learned from the completed test activities to determine changes needed for future itereations,releases and projects
        * Using the information gathered to improve test process maturity

<br>

---

**Last revision:** 09 June 2022

_Author_ [**mryesiller**](https://github.com/mryesiller)

