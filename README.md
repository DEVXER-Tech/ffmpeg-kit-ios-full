# ffmpeg-kit-ios-full
This repo is contains `xcframework` for https://github.com/arthenica/ffmpeg-kit version 6.0 for iOS

This repo is inspired from this discontinued ffmpeg-kit library: https://tanersener.medium.com/saying-goodbye-to-ffmpegkit-33ae939767e1

This repo is a replacement of `ffmpeg-kit` iOS

# Podfile

put this below in your `Podfile`, 
below is replaced from: `pod 'ffmpeg-kit-ios-full'` or `pod 'ffmpeg-kit-ios-full', '6.0'` because this repo is specifically use version 6.0 for iOS
```
pod 'ffmpeg-kit-ios-full', :podspec => 'https://raw.githubusercontent.com/DEVXER-Tech/ffmpeg-kit-ios-full/main/ffmpeg-kit-ios-full.podspec'
```

then just run this:
```
pod install && pod update
```
voila, your problem is gone
