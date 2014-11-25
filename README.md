# rtc-sip

This is an experiment at providing an integration between the rtc.io modules
and the [SIP.js](https://github.com/onsip/SIP.js) library.  This is done by
providing a custom SIP.js `mediaHandlerFactory` that can be used to override
the default WebRTC behaviour of SIP.js


[![NPM](https://nodei.co/npm/rtc-sip.png)](https://nodei.co/npm/rtc-sip/)



## NOTE: Incomplete

This package has been implemented to the point that it is usable for the
following purpose:

- Using a SIP endpoint to attach to a WebRTC call for the purposes of
  recording audio.

While other features will be implemented over time, these is not as high
a priority as other implementation tasks within the rtc.io suite.

## Example Usage

To be completed.

## License(s)

### Apache 2.0

Copyright 2014 Damon Oehlman <damon.oehlman@nicta.com.au>

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
