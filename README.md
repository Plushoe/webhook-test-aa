# webhook-test-aa
For testing webhooks with jenkins
Test 21 / 20

2: Changed urlencoded to json/application
3: Changed jenkins settings
4: Added trailing '/' to jenkins settings
5: Changed json/application back to urlencoded
6: Added trailing '/' to payload URL, changed back to json/application
7: 6 fixed the webhook, now the Jenkins is acting up... Doing a single resend to see if that fixes it
8: Webhook was still configured to urlencoded, unlike the intended change back in #6. No build was triggered on test #7.
9: Removed trailing '/'s from jenkins settings added in test #4
10: Removed 'github project' option from jenkins settings
11: Cleared workspace from jenkins that I manually built
12: Changed back to urlencoded... again again
13: Changed repo url in jenkins to end in .git
14: Deleted and readded the jenkins job. Same name and configuration.
15: Build showed up in Jenkins, but failed with the same error code as in test #7
16: Added a picture to git repo cos... why not (no readme update, the picture was the update)
17: Wrote entry 16 + 17
18: Re-ticked the Jenkins setting 'github project' with the url 'https://github.com/Plushoe/webhook-test-aa/'
19: Added github credentials to jenkins (even though this repo isn't set to private?)
20: Changed the branch settings from '/\*master' to instead be blank
21: Showing it works!
