---
title: "[WS] Verify Element Text" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/ws-verify-element-text.html 
description: 
---
Description
===========

Verify that there is an element with expected text appeared in the returned data from a web service call.

Parameters 
===========

<table><thead><tr><th>Parameter</th><th>Parameter Type</th><th>Mandatory</th><th>Description</th></tr></thead><tbody><tr><td><span>response&nbsp;</span></td><td><span>ResponseObject&nbsp;</span></td><td><span>Required</span></td><td><span>Represent an HTTP Response, the user can get responded content type, data, header properties (sometimes the user may want to get cookies from response header)</span></td></tr><tr><td><span>locator&nbsp;</span></td><td><span>String&nbsp;</span></td><td><span>Required</span></td><td><span>An expression Katalon will use to go through and look for the expected element(s), please refer to our user guide on how to write it:&nbsp;</span><a>Handle Web Service Response object</a></td></tr><tr><td><span>text&nbsp;</span></td><td><span>String&nbsp;</span></td><td><span>Required</span></td><td><span>The expected text of element you want to verify in the responded data (usually is JSON/XML)</span></td></tr><tr><td><span>flowControl&nbsp;</span></td><td><span>FailureHandling&nbsp;</span></td><td><span>Optional</span></td><td><span>Spec</span><span>ify </span><a>failure handling</a><span> schema to determine whether the execution should be allowed to continue or stop.</span></td></tr></tbody></table>

Returns
=======

*   **true**, if your element text is found, otherwise; **false**.

Example
=======

You want to verify converted weight after sending request is correct or not.

```groovy
import static com.kms.katalon.core.testcase.TestCaseFactory.findTestCase
import static com.kms.katalon.core.testdata.TestDataFactory.findTestData
import static com.kms.katalon.core.testobject.ObjectRepository.findTestObject
import internal.GlobalVariable as GlobalVariable
import com.kms.katalon.core.testobject.ConditionType as ConditionType
import com.kms.katalon.core.testobject.RequestObject as RequestObject
import com.kms.katalon.core.testobject.TestObjectProperty as TestObjectProperty
import com.kms.katalon.core.webservice.keyword.WSBuiltInKeywords as WebAPI
import com.kms.katalon.core.webui.keyword.WebUiBuiltInKeywords as WebUI
import com.kms.katalon.core.mobile.keyword.MobileBuiltInKeywords as Mobile
import com.kms.katalon.core.webservice.keyword.WSBuiltInKeywords as WS
import static com.kms.katalon.core.checkpoint.CheckpointFactory.findCheckpoint
import com.kms.katalon.core.model.FailureHandling as FailureHandling
import com.kms.katalon.core.testcase.TestCase as TestCase
import com.kms.katalon.core.testdata.TestData as TestData
import com.kms.katalon.core.testobject.TestObject as TestObject
import com.kms.katalon.core.checkpoint.Checkpoint as Checkpoint

'Send a SOAP request and returns its response'
def response = WS.sendRequest(findTestObject('SOAP_ConvertWeight'))

'Verify converted weight after sending request is correct or not'
WS.verifyElementText(response, 'ConvertWeightResult', '3000')
```