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
