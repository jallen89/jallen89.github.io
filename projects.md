---
layout: page
title: Projects
---

## __Transparent Computing__

__Theia__  
A Defense Advanced Research Projects Agency (DARPA) and Air Force Research Laboratory (AFRL) funded project that researches how data is tracked between computers, Internet hosts, and browers to improve security.


## __Android Malware Anlaysis__

__pDroid (privateDroid)__  
What makes an application malicious? For the Android platform, this is a difficult question to answer. Behavior that may be suspicious or malicious in one application may be expected behavior in another application. It is reasonable for a messaging app to access a user's contacts, but if, for example, a flashlight app accesses a user's contacts it should raise suspicion. Therefore, the behavior that makes an application potentially malicious is not a particular pattern, but the behavior in an application that is inconsistent with the end user's expectation. We developed pDroid, a malware detection framework that compared an Android app's textual description to the sensitive dataflows found in an app. pDroid correctly classified 91.4% of malware with a false positive rate of 4.9%.  
[slides][pDroid_slides] [thesis][pDroid]

__APPE  Finding The Hidden Scene Behind Description Files for Android Apps__  
We developed a framework to detect Android applications that made permission requests that were inconsistent with the app's alleged behavior (textual description). Our framework verified permission requests with an accuracy of 82%.  

[pDroid]: http://trace.tennessee.edu/utk_gradthes/4020/
[pDroid_slides]: https://www.slideshare.net/slideshow/embed_code/key/DatqxFPb6Rmign
