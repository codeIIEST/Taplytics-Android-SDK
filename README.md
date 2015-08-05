#Taplytics-Android SDK

_Taplytics is a native mobile A/B testing and push notification platform that helps you optimize your Android app!_

**[Get started with Taplytics](https://taplytics.com/docs/android-sdk/getting-started)**

###**Current Version: [1.5.8](https://github.com/taplytics/Taplytics-Android-SDK/releases/tag/1.5.8)**

## Getting Started

_How do I, as a developer, start using Taplytics?_ 

1. _Sign up for a free account at [Taplytics.com](https://taplytics.com?utm_source=github&utm_campaign=documentation&utm_medium=content)._
2. _Install the SDK. Steps [here](/START.md)._
3. Create [Experiments](/EXPERIMENTS.md) or send [Push Notifications](/PUSH.md) to your users!

## Changelog

**[1.5.8](https://github.com/taplytics/Taplytics-Android-SDK/releases/tag/1.5.8)**

1. Added indicator for when the device is not connected to the internet or Taplytics.
2. Added ability to disable the border from the shakemenu, for QA purposes
3. Added socket connection retries
4. Connections to Taplytics made more stable. 

**[1.5.7](https://github.com/taplytics/Taplytics-Android-SDK/releases/tag/1.5.7)**

1. PushTokenListener proguarding issues fixed.

**[1.5.6](https://github.com/taplytics/Taplytics-Android-SDK/releases/tag/1.5.6)**

1. Event reconciliation! If you were notcing more events in Taplytics than your other sources, this update fixes things from now on. 

**[1.5.5](https://github.com/taplytics/Taplytics-Android-SDK/releases/tag/1.5.5)**

1. Just some safety around starting Taplytics. 

**[1.5.4](https://github.com/taplytics/Taplytics-Android-SDK/releases/tag/1.5.4)**

1. Button goals no longer limited to only buttons. Anything with an onClickListener will be selectable.

**[1.5.3](https://github.com/taplytics/Taplytics-Android-SDK/releases/tag/1.5.3)**

1. Added a method to grab the GCM push token of the user if needed.
2. Removed session time limit. 

**[1.5.2](https://github.com/taplytics/Taplytics-Android-SDK/releases/tag/1.5.2)**

1. Added a flurry analytic method to track flurry events to Taplytics 
2. Generate unique ID if the phone does not contain one.
3. Taplytics push now works nicer alongside other push services
4. Push notifications can now route to Activities other than main.


## Questions or Need Help

_The Taplytics team is available 24/7 to answer any questions you have. Just email support@taplytics.com or visit [our docs page](https://taplytics.com/docs?utm_source=github&utm_campaign=documentation&utm_medium=content) for more detailed installation and usage information._
