# iOS 64bit Parse Module for Titanium

<h2> About Module </h2>
This module is for iOS 64bit supporting. It is copied part of the functions from <a href="https://github.com/raymondkam/ios-parse-titanium-module">Raymond</h> and <a href="https://github.com/ewindso/ios-parse-titanium-module"> ewindso </a> with 2 new functions as below

<b>-(void)registerForSinglePushChannel</b>
subscribe to single channel with no need to unsuncribe from current channel first. ONLY the new channel passed to this function will exist after execution.

-(void)unsubscribeFromAllChannels
unsubscribe from all channels with no need to get current sucscribtions.

Limitation
ONLY part of the functions from the <a href="https://github.com/ewindso/ios-parse-titanium-module"> ewindso </a>'s version have been implemented. Specifically, only functions regarding Objects and Push notification implemented in this module. 
