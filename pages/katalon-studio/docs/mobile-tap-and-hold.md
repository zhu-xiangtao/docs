---
title: "[Mobile] Tap And Hold" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/mobile-tap-and-hold.html 
description: 
---
Description
===========

Tap and hold on a mobile element for a duration

Parameters
==========

<table><thead><tr><th>Parameter</th><th>Parameter Type</th><th>Mandatory</th><th>Description</th></tr></thead><tbody><tr><td><span>to</span></td><td><span>TestObject&nbsp;</span></td><td><span>Required</span></td><td>Represent a mobile element.</td></tr><tr><td><span>duration</span></td><td><span>Number&nbsp;</span></td><td><span>Required</span></td><td>Duration (in seconds) that the tap is held on the element, if set to &lt;= 0 then will use default duration.</td></tr><tr><td><span>timeout&nbsp;</span></td><td><span>int</span></td><td><p><span>Required</span></p></td><td>System will wait at most timeout (seconds) to return the result.</td></tr><tr><td><span>flowControl</span></td><td><span>FailureHandling</span></td><td><span>Optional</span></td><td><span>Spec</span><span>ify </span><a>failure handling</a><span> schema to determine whether the execution should be allowed to continue or stop.</span></td></tr></tbody></table>

Example
=======

You want to tap on 'App' control and hold it for 10 seconds.

```groovy
import static com.kms.katalon.core.testcase.TestCaseFactory.findTestCase
import static com.kms.katalon.core.testdata.TestDataFactory.findTestData
import static com.kms.katalon.core.testobject.ObjectRepository.findTestObject
import internal.GlobalVariable as GlobalVariable
import com.kms.katalon.core.configuration.RunConfiguration as RunConfiguration
import com.kms.katalon.core.mobile.keyword.MobileBuiltInKeywords as Mobile
import com.kms.katalon.core.util.internal.PathUtil as PathUtil
 
'Start application on current selected android\'s device'
Mobile.startApplication(GlobalVariable.G_AndroidApp, false)
 
'Tap and hold app control for 10 seconds'
Mobile.tapAndHold(findTestObject('Application/android.widget.TextView - App'),10, 10)
 
Mobile.tap(findTestObject('Application/App/android.widget.TextView-Activity'), 10)
 
Mobile.tap(findTestObject('Application/App/Activity/android.widget.TextView-Custom Dialog'), 10)
 
'Check on subscribe checkbox'
Mobile.checkElement(findTestObject('Application/App/Activity/android.widget.Check - Subscribe'), 10)
 
'Close application on current selected android\'s device'
Mobile.closeApplication()
```