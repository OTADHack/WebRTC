WebRTC API Sample
=========

Source code of a **WebRTC Sample** providing webRTC audio and video call.

Version
----

7.1

Usage
----

Follow this steps:

+ Request your credentials on the [Oracle's TADHack website](http://tadhack.optaresolutions.com).
+ Install [Maven](https://maven.apache.org/) in your machine
+ Download the source code included in this repository using the `Download ZIP button` or using the clone option
```sh
git clone https://github.com/OTADHack/WebRTC.git wscsample
cd wscsample
mvn jetty:run
```
+ Open http://localhost:8080
+ Click Login using your TADHack credentials
+ Click the Video Demo link in the sample application. In the Enter Your ID field, enter alice@example.com and click Register.
+ Open a new Chrome incognito window and browse to the address http://localhost:8080
+ Click the Video Demo link in the sample application. In the Enter Your ID field, enter bob@example.com and click Register.
+ In Alice’s browser window, in the Enter Your Callee field, enter bob@example.com and click Call and Allow.
+ In Bob’s browser window, click Accept alice@example.com Incoming Audio Call and Allow.

Documentation
----

WebRTC Documentation can be found at [Oracle's TADHack WebRTC website](http://tadhack.optaresolutions.com/?page_id=60).

Support
----

If you have any doubt, ask it in [the Issues section](https://github.com/OTADHack/WebRTC/issues).


License
----

Copyright © 2007, 2015, Oracle and/or its affiliates. All rights reserved. Usage only allowed for TADHack Developers.
