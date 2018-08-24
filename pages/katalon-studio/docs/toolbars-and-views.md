---
title: "Toolbars and Views" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/toolbars-and-views.html 
description: 
---
Toolbar
=======

Since version 5.6

![](../../images/katalon-studio/docs/toolbars-and-views/image2018-8-1 14_57_20.png)

The main **Toolbar** contains the most common actions which you usually perform (e.g. creating test resources or executing automation tests).

<table><thead><tr><th>Icon</th><th>Description</th></tr></thead><tbody><tr><td><div><p><span><img></span></p></div></td><td>Save the current opened test artifact.</td></tr><tr><td><div><p><span><img></span></p></div></td><td>Save all opened test artifacts.</td></tr><tr><td><div><p><span><img></span></p></div></td><td><p>Create new test artifacts. You can select these options by selecting from dropdownlist:</p><ul><li>Folder</li><li>Test Case</li><li>Test Suite</li><li>Test Suite Collection</li><li>Test Object</li><li>Web Service Request</li><li>Test Data</li><li>Checkpoint</li><li>Package</li><li>Keyword</li></ul></td></tr><tr><td><div><p><span><img></span></p></div></td><td>Open <strong>Web</strong> <strong>Object Spy</strong> dialog for capturing elements on websites.</td></tr><tr><td><div><p><span><img></span></p></div></td><td>Open <strong>Mobile Object Spy</strong> dialog for capturing elements on mobile applications.</td></tr><tr><td><div><p><span><img></span></p></div></td><td>Open <strong>Web</strong> <strong>Record</strong> dialog for recording WebUI test cases.</td></tr><tr><td><div><p><span><img></span></p></div></td><td>Open <strong>Mobile Recorder</strong> dialog for recording Mobile test cases.</td></tr><tr><td><div><p><span><img></span></p></div></td><td><p>Run the current open test case. You can select these options by selecting from dropdownlist:</p><ul><li>Chrome</li><li>Firefox</li><li>IE</li><li>Safari</li><li>Edge</li><li>Remote</li><li>Headless</li><li>Android</li><li>iOS (on macOS)</li><li>Custom</li></ul></td></tr><tr><td><div><p><span><img></span></p></div></td><td><p>Debug the current open test case. You can select these options by selecting from dropdownlist:</p><ul><li>Chrome</li><li>Firefox</li><li>IE</li><li>Safari</li><li>Edge</li><li>Remote</li><li>Headless</li><li>Android</li><li>iOS (on macOS)</li><li>Custom</li></ul></td></tr><tr><td><div><p><span><img></span></p></div></td><td>Stop the current execution</td></tr><tr><td><div><p><span><img></span></p></div></td><td>Open <strong>Command Builder</strong> for generating commands for console execution</td></tr><tr><td><div><p><span><img></span></p></div></td><td><p>Command for Git activities. You can select these options by selecting from dropdownlist (after <a>enabling Git</a>):</p><ul><li>Clone Project</li><li>Share Project</li><li>Show History</li><li>Manage Branches</li><li>Commit</li><li>Push</li><li>Pull</li><li>Fetch</li></ul></td></tr><tr><td><div><p><span><img></span></p></div></td><td>Import test case from JIRA integrated account</td></tr><tr><td><div><p><span><img></span></p></div></td><td>Execution profile (testing environments) ro be applied when run tests</td></tr><tr><td><div><p><span><img></span></p></div></td><td>Allowing you to search for help on Katalon Documentation and our Forum</td></tr><tr><td><div><p><span><img></span></p></div></td><td>If you have any further questions, you can also submit it in our Gitter channel. Katalon experts and users will try to help you as soon as possible.</td></tr></tbody></table>

Tests Explorer View
===================

The **Tests Explorer** view allows you to browse the structure of your projects and access all test artifacts quickly. Using the context menu on the view, you can create new artifacts, organize the view's items or drag and drop them to certain editor views if needed.

![](../../images/katalon-studio/docs/toolbars-and-views/image2018-4-3 15_38_1.png)

where:

<table><thead><tr><th>Group</th><th>Description</th></tr></thead><tbody><tr><td>Test Cases</td><td>List all <a>test cases</a> within current project</td></tr><tr><td>Object Repository</td><td>List all <a>test objects</a> of the current project</td></tr><tr><td>Test Suites</td><td>List all <a>test suites</a> and <a>test suite collections</a> of the current project</td></tr><tr><td>Data Files</td><td>List all <a>test data</a> of the current project</td></tr><tr><td>Checkpoints</td><td>List all <a>checkpoints</a> of the current project</td></tr><tr><td>Keywords</td><td>List all <a>custom keywords</a> of the current project</td></tr><tr><td>Reports</td><td>List all generated <a>reports</a> of the current project</td></tr><tr><td>Profiles</td><td>List all execution profiles of the current project</td></tr></tbody></table>

Keywords Browser View
=====================

The **Keywords Browser** view displays all available keywords supported by Katalon Studio. You can drag and drop the keywords here to the Test Case editor when scripting.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 17_26_5.png)

Editors
=======

The editor is used to modify the detailed information of an object. Each test artifact has its own editor.

![](../../images/katalon-studio/docs/toolbars-and-views/image2018-4-3 15_42_1.png)

Test Case Editor
----------------

When you open a test case, its detailed information is shown in the editor that contains the following tabs:

*   Manual tab
*   Script tab
*   Variables tab
*   Integration tab
*   Properties tab

### Manual tab

The Manual tab displays the Manual view where the basic keyword-driven-configuration allows novice users to create automation tests effortlessly. Refer to [Manual View](/display/KD/Manual+View) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-29 15_30_14.png)

### Script tab

This tab displays the Script view where advanced users with programming background can modify test scripts easily using either Groovy or Java. Refer to [Script View](/display/KD/Script+View) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-29 15_30_45.png)

### Variables tab

The Variables tab shows all variables defined for the test case. Refer to [Public Variables](/display/KD/Variable+Types#VariableTypes-Publicvariables) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-29 15_31_50.png)

### Integration tab

Information regarding your test case integration with qTest is displayed in this tab. Refer to [Integrate test case](/display/KD/Integrate+test+case) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-10-11 13_32_45.png)

### Properties tab

General information about the test case is displayed in this tab.

*   **Description:** Users can add or edit this field to provide detail information about a test case
*   **Comment: **This field is **read-only**. The content is extracted and populated from [Comment](/display/KD/%5BCommon%5D+Comment) keyword in the test case. Business users can leverage comment field to involve in development process by providing the requirements. The example below shows the description of a test case that verify successful login and comment field shows the scenario written in BDD's Gherkin syntax.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-23 15_41_54.png)

Test Object Editor
------------------

When you open a test object, its detailed information including properties and object identification mechanism is displayed in the Test Object editor. Refer to [Spy Object](/display/KD/Spy+Object) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-10-11 13_34_57.png)

Web Service Editor
------------------

### RESTful Request Object Editor

When you open a RESTful request object, its detailed information including the resource URL, request methods, parameters... is displayed in the editor. Refer to [RESTful](/pages/viewpage.action?pageId=5125144) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 16_44_23.png)

### SOAP Request Object Editor

When you open a SOAP request object, its detailed information including the resource URL, request methods, parameters... is displayed in the editor. Refer to [SOAP](/pages/viewpage.action?pageId=13697583) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-29 15_42_43.png)

Test Suite Editor
-----------------

When you open a test suite, its detailed information is displayed in the Test Suite editor that contains the following tabs:

*   Main tab
*   Integration tab

### Main tab

The main tab displays basic information about the test suite such as the test cases to be executed, the execution mechanism and data binding. Refer to [Execute a test suite](/display/KD/Execute+a+Test+Case+or+a+Test+Suite) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 16_49_18.png)

### Integration tab

Information regarding your test suite integration with qTest is displayed in this tab. Refer to [Integrate test suite](/display/KD/Integrate+test+suite) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 16_54_47.png)

Test Suite Collection Editor
----------------------------

Basically, a Test Suite Collection contains a set of test suites to allow users to execute test suites together. Refer to [Test suite collection](/display/KD/Test+Suite+Collection) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-10-11 13_39_22.png)

Data File Editor
----------------

When you open a data file, its detailed information including the data source and preview data set... is displayed in the editor. Refer to [Manage Test Data](/display/KD/Manage+Test+Data) for more details.

*   If the test data is from an Excel file:  
    ![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 17_7_38.png)

*   If the test data is from a CSV file:  
    ![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 17_6_7.png)

*   If the test data is defined internally inside your test project:  
    ![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 17_9_51.png)
*   If the test data is from a database query:  
    ![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 17_9_21.png)  
      
    

Checkpoint Editor
-----------------

When you open a checkpoint, its detailed information including the data source and its taken snapshot... is displayed in the editor. Refer to [Manage a Checkpoint](/display/KD/Manage+a+Checkpoint) for more details.

*   If the data source is from an Excel file:  
    ![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-28 15_46_42.png)
*   If the data source is from a CSV file:  
    ![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-28 15_48_0.png)
*   If the data source is from a database:  
    ![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-28 15_48_46.png)
*   If the data source is from existing test data:  
    ![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-28 15_49_42.png)

Keyword Editor
--------------

When you open a custom keyword, its content is displayed in the scripting editor. This scripting editor is similar to the Script view of test cases where you can define new custom keywords easily using Groovy or Java. Refer to [Introduction to Custom Keywords](/display/KD/Introduction+to+Custom+Keywords) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 17_20_0.png)

Global Variables View
=====================

The Global Variables view allows you to browse the list of available global variables defined in your project. Refer to [Global Variables](/display/KD/Variable+Types#VariableTypes-Globalvariables) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-29 15_49_54.png)

Job Progress View
=================

The Job Progress view allows you to see the progress of executing test cases and test suites.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 17_31_18.png)

Problems View
=============

The Problems view shows errors and warning messages raised when you are setting up a project or designing the test case, test suite, test object or test data.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-29 15_51_15.png)

The messages displayed in the Problems view can be configured via the drop-down menu of this view.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-20 17_42_36.png)

Console View
============

The Console view shows the system logs of all run-time activities performed while the automation test is being executed. The console output generated from test scripts is also displayed here.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-29 15_52_58.png)

Log Viewer View
===============

The Log Viewer view shows the real-time report/log of the test execution. Refer to [View Execution Log](/display/KD/View+Execution+Log) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-29 15_54_23.png)

Search View
===========

The Search view shows the search results from the search function. You can double-click on a search entry to navigate to the corresponding position in the editor.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-6-29 15_55_30.png)

Report View
===========

The Report view allows you to view detailed information of a completed test execution for a certain test suite. Refer to [Test Suite Report](/display/KD/Test+Suite+Report) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-21 16_42_16.png)

Test Suite Collection Report view
=================================

The Test Suite Collection Report view allows you to view detailed information of a completed test execution for a certain test suite collection. Refer to [Test Suite Collection Report](/display/KD/Test+Suite+Collection+Report) for more details.

![](../../images/katalon-studio/docs/toolbars-and-views/image2017-2-28 15_52_37.png)