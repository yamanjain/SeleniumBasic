# SeleniumBasic -- Multiuser patch
A Selenium based browser automation framework for VB.Net, Visual Basic Applications and VBScript
Exception on line 89 in Syswaiter.cs #146
https://github.com/florentbr/SeleniumBasic/issues/146
Seleniumbasic from vba code on an access database, but is only working for one user at the time, once one user/session uses it, it would throw the Exception on line 89 to all other sessions.

Patch Usage:
Install seleniumbasic as usual. Next simply replace all the files in the zip file in the Seleniumbasic (C:\ProgramFiles\SeleniumBasic usually) folder and then register the new dll using regasm (run attached bat file using cmd as administrator).

Don't forget to update chromedriver to match your chrome version. Replace chromedriver.exe in Seleniumbasic folder with the latest from:
https://chromedriver.chromium.org/
