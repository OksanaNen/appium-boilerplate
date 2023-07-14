"spec" Reporter:
------------------------------------------------------------------
[emulator-5554 Android 14 #0-0] Running: emulator-5554 on Android 14 executing D:\GitHub\QA Course\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 14 #0-0] Session ID: 2612be81-8d49-45c9-a65d-554273ca7379
[emulator-5554 Android 14 #0-0]
[emulator-5554 Android 14 #0-0] » \tests\specs\app.biometric.login.spec.ts
[emulator-5554 Android 14 #0-0] WebdriverIO and Appium, when interacting with a biometric button,
[emulator-5554 Android 14 #0-0]    ? should be able to login with a matching touch/faceID/fingerprint
[emulator-5554 Android 14 #0-0]    ✖ "before each" hook for WebdriverIO and Appium, when interacting with a biometric button,
[emulator-5554 Android 14 #0-0]
[emulator-5554 Android 14 #0-0] 1 failing (1m 7.6s)
[emulator-5554 Android 14 #0-0]
[emulator-5554 Android 14 #0-0] 1) WebdriverIO and Appium, when interacting with a biometric button, "before each" hook for WebdriverIO and Appium, when interacting with a biometric button, 
[emulator-5554 Android 14 #0-0] element ("android=new UiSelector().textContains("NEXT")") still not displayed after 45000ms
[emulator-5554 Android 14 #0-0] Error: element ("android=new UiSelector().textContains("NEXT")") still not displayed after 45000ms
[emulator-5554 Android 14 #0-0]     at D:\GitHub\QA Course\appium-boilerplate\node_modules\webdriverio\build\commands\browser\waitUntil.js:66:23
[emulator-5554 Android 14 #0-0]     at async Element.wrapCommandFn (D:\GitHub\QA Course\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 14 #0-0]     at async Element.elementErrorHandlerCallbackFn (D:\GitHub\QA Course\appium-boilerplate\node_modules\webdriverio\build\middlewares.js:24:32)
[emulator-5554 Android 14 #0-0]     at async Element.wrapCommandFn (D:\GitHub\QA Course\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 14 #0-0]     at async Element.wrapCommandFn (D:\GitHub\QA Course\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 14 #0-0]     at async Element.elementErrorHandlerCallbackFn (D:\GitHub\QA Course\appium-boilerplate\node_modules\webdriverio\build\middlewares.js:24:32)
[emulator-5554 Android 14 #0-0]     at async Element.wrapCommandFn (D:\GitHub\QA Course\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 14 #0-0]     at async AndroidSettings.waitAndTap (D:\GitHub\QA Course\appium-boilerplate\tests\screenobjects\AndroidSettings.ts:113:9)
[emulator-5554 Android 14 #0-0]     at async AndroidSettings.fingerPrintWizardEightOrHigher (D:\GitHub\QA Course\appium-boilerplate\tests\screenobjects\AndroidSettings.ts:32:13)
[emulator-5554 Android 14 #0-0]     at async AndroidSettings.enableBiometricLogin (D:\GitHub\QA Course\appium-boilerplate\tests\screenobjects\AndroidSettings.ts:137:13)
------------------------------------------------------------------
[emulator-5554 Android 14 #0-1] Running: emulator-5554 on Android 14 executing D:\GitHub\QA Course\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 14 #0-1] Session ID: 4dd00b9e-26e7-4967-8400-fc50a1800df6
[emulator-5554 Android 14 #0-1]
[emulator-5554 Android 14 #0-1] » \tests\specs\app.deep.link.navigation.spec.ts
[emulator-5554 Android 14 #0-1] WebdriverIO and Appium, when navigating by deep link
[emulator-5554 Android 14 #0-1]    ✓ should be able to open the webview
[emulator-5554 Android 14 #0-1]    ✓ should be able to open the login form screen
[emulator-5554 Android 14 #0-1]    ✓ should be able to open the forms screen
[emulator-5554 Android 14 #0-1]    ✓ should be able to open the swipe screen
[emulator-5554 Android 14 #0-1]    ✓ should be able to open the drag and drop screen
[emulator-5554 Android 14 #0-1]    ✓ should be able to open the home screen
[emulator-5554 Android 14 #0-1]
[emulator-5554 Android 14 #0-1] 6 passing (1m 30.9s)
------------------------------------------------------------------
[emulator-5554 Android 14 #0-2] Running: emulator-5554 on Android 14 executing D:\GitHub\QA Course\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 14 #0-2] Session ID: d37a1ff3-3b98-4125-831b-90de31da4e13
[emulator-5554 Android 14 #0-2]
[emulator-5554 Android 14 #0-2] » \tests\specs\app.drag.and.drop.spec.ts
[emulator-5554 Android 14 #0-2] WebdriverIO and Appium, when using drag and drop
[emulator-5554 Android 14 #0-2]    ✓ should be able to solve the puzzle by dragging the pieces into the puzzle
[emulator-5554 Android 14 #0-2]
[emulator-5554 Android 14 #0-2] 1 passing (30s)
------------------------------------------------------------------
[emulator-5554 Android 14 #0-3] Running: emulator-5554 on Android 14 executing D:\GitHub\QA Course\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 14 #0-3] Session ID: 8c951eed-53b5-4dad-b56c-5b259fe7fb1f
[emulator-5554 Android 14 #0-3]
[emulator-5554 Android 14 #0-3] » \tests\specs\app.forms.spec.ts
[emulator-5554 Android 14 #0-3] WebdriverIO and Appium, when interacting with form elements,
[emulator-5554 Android 14 #0-3]    ✓ should be able type in the input and validate the text
[emulator-5554 Android 14 #0-3]    ✓ should be able turn on and off the switch
[emulator-5554 Android 14 #0-3]    ✓ should be able select a value from the select element
[emulator-5554 Android 14 #0-3]    ✓ should be able to open the alert and close it with all 3 buttons
[emulator-5554 Android 14 #0-3]    ✓ should be able to determine that the inactive button is inactive
[emulator-5554 Android 14 #0-3]
[emulator-5554 Android 14 #0-3] 5 passing (54.6s)
------------------------------------------------------------------
[emulator-5554 Android 14 #0-4] Running: emulator-5554 on Android 14 executing D:\GitHub\QA Course\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 14 #0-4] Session ID: 795ee124-2903-46f4-be8a-ff3be3cdb21e
[emulator-5554 Android 14 #0-4]
[emulator-5554 Android 14 #0-4] » \tests\specs\app.login.spec.ts
[emulator-5554 Android 14 #0-4] WebdriverIO and Appium, when interacting with a login form,
[emulator-5554 Android 14 #0-4]    ✓ should be able login successfully
[emulator-5554 Android 14 #0-4]    ✓ should be able sign up successfully
[emulator-5554 Android 14 #0-4]
[emulator-5554 Android 14 #0-4] 2 passing (37.3s)
------------------------------------------------------------------
[emulator-5554 Android 14 #0-5] Running: emulator-5554 on Android 14 executing D:\GitHub\QA Course\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 14 #0-5] Session ID: 4f92de73-5759-4e31-8622-d7770463e212
[emulator-5554 Android 14 #0-5]
[emulator-5554 Android 14 #0-5] » \tests\specs\app.swipe.spec.ts
[emulator-5554 Android 14 #0-5] WebdriverIO and Appium, when using swiping
[emulator-5554 Android 14 #0-5]    ✓ should be able to swipe horizontal by swiping the carousel from left to right
[emulator-5554 Android 14 #0-5]    ✓ should be able to swipe vertical by finding the surprise
[emulator-5554 Android 14 #0-5]
[emulator-5554 Android 14 #0-5] 2 passing (1m 44.4s)
------------------------------------------------------------------
[emulator-5554 Android 14 #0-6] Running: emulator-5554 on Android 14 executing D:\GitHub\QA Course\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 14 #0-6] Session ID: da8a4ed9-65dc-476e-a33a-83eaa2a93f36
[emulator-5554 Android 14 #0-6]
[emulator-5554 Android 14 #0-6] » \tests\specs\app.tab.bar.navigation.spec.ts
[emulator-5554 Android 14 #0-6] WebdriverIO and Appium, when using navigation through the tab bar
[emulator-5554 Android 14 #0-6]    ✓ should be able to open the webview
[emulator-5554 Android 14 #0-6]    ✓ should be able to open the login form screen
[emulator-5554 Android 14 #0-6]    ✓ should be able to open the forms screen
[emulator-5554 Android 14 #0-6]    ✓ should be able to open the swipe screen
[emulator-5554 Android 14 #0-6]    ✓ should be able to open the drag and drop screen
[emulator-5554 Android 14 #0-6]    ✓ should be able to open the home screen
[emulator-5554 Android 14 #0-6]
[emulator-5554 Android 14 #0-6] 6 passing (1m 10s)
------------------------------------------------------------------
[emulator-5554 Android 14 #0-7] Running: emulator-5554 on Android 14 executing D:\GitHub\QA Course\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 14 #0-7] Session ID: 93f7074c-6681-4efe-85c2-f2eaf4d12e03
[emulator-5554 Android 14 #0-7]
[emulator-5554 Android 14 #0-7] » \tests\specs\app.webview.spec.ts
[emulator-5554 Android 14 #0-7]    ✓ should be able to switch between webview, native and webview
[emulator-5554 Android 14 #0-7]
[emulator-5554 Android 14 #0-7] 1 passing (3m 3.1s)
------------------------------------------------------------------
[emulator-5554 Android 14 #0-8] Running: emulator-5554 on Android 14 executing D:\GitHub\QA Course\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 14 #0-8] Session ID: fe54b3e6-48e5-4146-817c-e8762dbc0ae2
[emulator-5554 Android 14 #0-8]
[emulator-5554 Android 14 #0-8] » \tests\specs\app.webview.xpath.spec.ts
[emulator-5554 Android 14 #0-8] WebdriverIO and Appium, when interacting with a webview through XPATH
[emulator-5554 Android 14 #0-8]    ✓ should be able to verify that the WebView is shown by xpath
[emulator-5554 Android 14 #0-8]    ✓ should be able to verify that the WebView is shown by switching to the WebView
[emulator-5554 Android 14 #0-8]
[emulator-5554 Android 14 #0-8] 2 passing (37.7s)


Spec Files:      8 passed, 1 failed, 9 total (100% completed) in 00:14:34