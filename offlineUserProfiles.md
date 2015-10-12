---
layout: doc
title:  "Offline User Profiles"
permalink: /docs/offlineUserProfiles.html
---

This document will introduce how to start the offline processing on user profiles. Assume Eagle has been installed and [Eagle service](http://sandbox.hortonworks.com:9099/eagle-service)
is started. Two options are provided.

###Option 1: Command line

Step 1: Start Spark if not started
![Start Spark](/images/docs/startSpark2.png)

Step 2: start offline training process

    cd <eagle-home>/bin
    bin/eagle-userprofile-scheduler.sh --site sandbox start

###Option 2: Eagle UI

Step 1: Start Spark if not started
![Start Spark](/images/docs/startSpark2.png)

Step 2: Start offline training process, and click "ops" on the right corner

![Click "ops"](/images/docs/step1.png)
![Click "Update Now"](/images/docs/step2.png)
![Click "Confirm"](/images/docs/step3.png)
![Check](/images/docs/step4.png)
