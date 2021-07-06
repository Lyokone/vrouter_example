# vrouter_example

A new Flutter project.

## Getting Started

To test the deeplinking on Android:

```
adb shell am start -a android.intent.action.VIEW \
    -c android.intent.category.BROWSABLE \
    -d "http://vrouter.com/settings"
```

It should properly redirect you on the settings page.
