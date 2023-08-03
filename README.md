# Useful-links

## What works for me

### 1. SHA key generation android
### Debug

```
keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass android
```
### Release

```
* Need to give exact key jks path

keytool -list -v -keystore /Users/macbook/upload-keystore.jks -alias test
```

### 2. PNG Crush for compression of png images
### For MAC OS

```
link--> https://developer.android.com/topic/performance/reduce-apk-size

Execute below command for installation

1:  brew install pngcrush
2:  pngcrush -reduce -brute <source.png>  <destination.png>
  e.g
  pngcrush -reduce -brute /Users/macbook/IdeaProjects/jamaica-flutter/lib/assets/images/jamaica/gruppe_1.png  test1.png

```













