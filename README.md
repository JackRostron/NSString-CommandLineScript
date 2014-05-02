NSString+CommandLineScript
==========================

Category on NSString which returns the output of the command if run in Terminal


## How to run a command

Set an `NSString` variable with the command that you would like to execute. Call `commandLineOutput` on that string to execute. The return value is a NSString with the terminal output.

```objc
NSString *commandToRun = @"xcodebuild -showsdks";
NSLog(@"%@", [commandToRun commandLineOutput]);
```
