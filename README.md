# Call alerting for Intergraph I/NetViewer

This repository contains a TamperMonkey extension written for Syracuse
University Ambulance to parse calls from the Onondaga 911 center and play an
alert tone if the call is in the SUA service area.


*Note:* for this script to work in Google Chrome go to
chrome://flags/#autoplay-policy and set `Autoplay policy` to "No user gesture is
required".


## Examples
Here are some example pages for testing the extension. You will have to delete your cookies after each test.

[Valid Call (alert tone)](http://htmlpreview.github.io/?https://github.com/bdwyer2/netviewer-alerter/blob/master/examples/valid_call.html)
[Invalid Call (beep only)](http://htmlpreview.github.io/?https://github.com/bdwyer2/netviewer-alerter/blob/master/examples/invalid_call.html)
[Both Type (alert tone)](http://htmlpreview.github.io/?https://github.com/bdwyer2/netviewer-alerter/blob/master/examples/both_calls.html)
[No Calls (no tones)](http://htmlpreview.github.io/?https://github.com/bdwyer2/netviewer-alerter/blob/master/examples/no_calls.html)


