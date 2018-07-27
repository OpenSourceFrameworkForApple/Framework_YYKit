Framework_YYKit
==============

[![License MIT](https://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://raw.githubusercontent.com/ibireme/YYKit/master/LICENSE)&nbsp;
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)&nbsp;
[![CocoaPods](http://img.shields.io/cocoapods/v/YYKit.svg?style=flat)](http://cocoapods.org/pods/YYKit)&nbsp;
[![CocoaPods](http://img.shields.io/cocoapods/p/YYKit.svg?style=flat)](http://cocoadocs.org/docsets/YYKit)&nbsp;
[![Support](https://img.shields.io/badge/support-iOS%206%2B%20-blue.svg?style=flat)](https://www.apple.com/nl/ios/)&nbsp;
[![Build Status](https://travis-ci.org/ibireme/YYKit.svg?branch=master)](https://travis-ci.org/ibireme/YYKit)


Framework_YYKit is a framework of YYKit.

It's so huge that I split it into several independent components:

* [YYModel](https://github.com/ibireme/YYModel) — High performance model framework for iOS.
* [YYCache](https://github.com/ibireme/YYCache) — High performance cache framework for iOS.
* [YYImage](https://github.com/ibireme/YYImage) — Image framework for iOS to display/encode/decode animated WebP, APNG, GIF.
* [YYWebImage](https://github.com/ibireme/YYWebImage) — Asynchronous image loading framework.
* [YYText](https://github.com/ibireme/YYText) — Powerful rich text component for iOS.
* [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager) — Access keyboard view and track keyboard animation.
* [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) — iOS utility class to manage global dispatch queue.
* [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) — iOS utility classes for asynchronous rendering and display.
* [YYCategories](https://github.com/ibireme/YYCategories) — A set of useful categories for Foundation and UIKit.


Installation
==============

### CocoaPods

1. add `source 'https://github.com/OpenSourceFrameworkForApple/OpenSourceFrameworkSpecs.git'` to your Podfile.
1. Add `pod 'Framework_YYKit'` to your Podfile.
2. Run `pod install` or `pod update`.
3. Import \<YYKit/YYKit.h\>.



### Manually

1. Download all the files in the `Framework_YYKit` subdirectory.
2. Add the YYKit.framework and the `Vendor/WebP.framework` to your Xcode project.
3. Link with required frameworks:
    * UIKit
    * CoreFoundation
    * CoreText
    * CoreGraphics
    * CoreImage
    * QuartzCore
    * ImageIO
    * AssetsLibrary
    * Accelerate
    * MobileCoreServices
    * SystemConfiguration
    * sqlite3
    * libz
4. Import \<YYKit/YYKit.h\>..


Documentation
==============
Full API documentation is available on [CocoaDocs](http://cocoadocs.org/docsets/YYKit/).<br/>
You can also install documentation locally using [appledoc](https://github.com/tomaz/appledoc).


Requirements
==============
This library requires `iOS 6.0+` and `Xcode 8.0+`.

Notice
==============
I want to use the APIs as if it was provided by system, and I don't add prefix in
these categories. I do not recommend using the `YYKit` directly, you should try the separated components first.

License
==============
Framework_YYKit is provided under the MIT license. See LICENSE file for details.



