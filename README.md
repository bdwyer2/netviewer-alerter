# Call alerting for Intergraph I/NetViewer

This repository contains a TamperMonkey extension written for Syracuse
University Ambulance to parse calls from the Onondaga 911 center and play an
alert tone if the call is in the SUA service area.


*Note:* for this script to work in Google Chrome go to
chrome://flags/#autoplay-policy and set `Autoplay policy` to "No user gesture is
required".


## Examples
Here are some example pages for testing the extension. You will have to delete your cookies after each test.

* [Valid Call (alert tone)](https://bdwyer2.github.io/netviewer-alerter/valid_call.html)
* [Invalid Call (beep only)](https://bdwyer2.github.io/netviewer-alerter/invalid_call.html)
* [Both Type (alert tone)](https://bdwyer2.github.io/netviewer-alerter/both_calls.html)
* [No Calls (no tones)](https://bdwyer2.github.io/netviewer-alerter/no_calls.html)


