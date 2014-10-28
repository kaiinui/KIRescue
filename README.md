KIRescue
========

Quickly gives users help &amp; apologize when the user faces crash.

In your `AppDelegate:didFinishLaunchingWithOptions:`,

```objc
[KIRescue rescueWithPath:@"https://YOURDOMAIN.com/"];
```

or if you do not need the crash report,

```objc
[KIRescue rescue];
```

References
---

- raven-objc/RavenClient.m at master · getsentry/raven-objc : https://github.com/getsentry/raven-objc/blob/master/Raven/RavenClient.m#L310
- NSSetUncaughtExceptionHandler - Foundation Functions Reference : https://developer.apple.com/library/mac/documentation/Cocoa/Reference/Foundation/Miscellaneous/Foundation_Functions/#//apple_ref/c/func/NSSetUncaughtExceptionHandler
