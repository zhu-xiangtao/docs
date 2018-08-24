---
title: "Version 4.0.1" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/version-401.html 
description: 
---
**General**

Add 'Offline Activation' feature on Activation Screen

**Console mode execution**

Add additional parameters to console mode execution. You can use this parameters for activation automatically when running on console mode:

<table><thead><tr><th>Param name</th><th>Description</th></tr></thead><tbody><tr><td>-email</td><td>Registered email on Katalon Studio site</td></tr><tr><td>-password</td><td>Your password tied to the above email</td></tr></tbody></table>

**Example**

```groovy
katalon -runMode=console -consoleLog -projectPath="D:\Project\Katalon\Katalon_projects\Regression Test\RegressionTest\RegressionTest.prj" -retry=0 -testSuitePath="Test Suites/New Test Suite78" -browserType="Chrome" -email="vinhtest@gmail.com" -password="12345678"
```