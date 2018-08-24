---
title: "Setup/Teardown for Test Suite and Test Case" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/setupteardown-for-test-suite-and-test-case.html 
description: 
---
> Available since Katalon Studio v5.3
> 
> For full lifecycle of Tests in Katalon Studio, refer to this [documentation](https://docs.katalon.com/x/7zhO).

Every test suite from your projects now has been equipped with the ability to run either **SetUp** or **Teardown** methods, which are groups of your own defined test steps before or after executing a Test Suite. This feature is another great extension besides [Test Listener](https://docs.katalon.com/pages/viewpage.action?pageId=5126383) to extend your current testing flow as much as possible.

There will a **new tab** called '**Script**' in **Test Suite**'s interface. This interface will generate sample **Setup** and **TearDown** methods to be used.

![](../../images/katalon-studio/docs/setupteardown-for-test-suite-and-test-case/image2018-1-8 16_25_42.png)**Supported methods**

<table><thead><tr><th>Method</th><th>Description</th><th>Trigger Condition</th><th>Common Usages</th></tr></thead><tbody><tr><td><p>setUp</p></td><td><p>Setup test suite environment<br><br></p></td><td>Before executed test suites</td><td><p>Prepare testing environment</p><p>Call required test cases for the executed test suite</p></td></tr><tr><td>setUpTestCase</td><td>Run before each test case starts</td><td>Before executed test cases</td></tr><tr><td><p>tearDown</p></td><td><p>Clean test suites environment</p></td><td>After executed test suites</td><td><p>Clean-up testing environment</p><p>Call TearDown test cases for the executed test suite</p><p>&nbsp;</p><p>&nbsp;</p></td></tr><tr><td><p>tearDownTestCase</p></td><td><p>Run after each test case ends</p></td><td><p>After executed test cases</p></td></tr></tbody></table>

### How it works

By default, these **Setup** and **Teardown** methods will not be triggered even if they match with provided trigger condition above. You need to **set skipped value from false** to true to activate related methods.

### Methods consideration

*   Execution progress from these methods still have execution logs as usual and they will be stored in execution logs files of Katalon Studio.
    
*   You can't see setUp and teardown executed reports from generated Test Suite report. Only **setUpTestCase** and **tearDownTestCase** can be seen in generated Test Suite report
*   Test Listeners will always be triggered first if you define both Test Listeners and activate Setup / Teardown methods at the same time.  
    ![](../../images/katalon-studio/docs/setupteardown-for-test-suite-and-test-case/Screen Shot 2018-01-05 at 14.24.23.png)