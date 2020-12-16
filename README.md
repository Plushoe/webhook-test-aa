# webhook-test-aa
For testing webhooks with jenkins
Test 9 / ?

2: Changed urlencoded to json/application
3: Changed jenkins settings
4: Added trailing '/' to jenkins settings
5: Changed json/application back to urlencoded
6: Added trailing '/' to payload URL, changed back to json/application
7: 6 fixed the webhook, now the Jenkins is acting up... Doing a single resend to see if that fixes it
8: Webhook was still configured to urlencoded, unlike the intended change back in #6. No build was triggered on test #7.
9: Removed trailing '/'s from jenkins settings added in test #4
10: Removed 'github project' option from jenkins settings
