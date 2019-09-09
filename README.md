# ConcentricOnboarding

[![Version](https://img.shields.io/cocoapods/v/ConcentricOnboarding.svg?style=flat)](http://cocoapods.org/pods/ConcentricOnboarding)
[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-0473B3.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/cocoapods/l/ConcentricOnboarding.svg?style=flat)](http://cocoapods.org/pods/ConcentricOnboarding)
[![Platform](https://img.shields.io/cocoapods/p/ConcentricOnboarding.svg?style=flat)](http://cocoapods.org/pods/ConcentricOnboarding)

Animated page view control using clean SwiftUI. This project is maintained by [exyte](https://www.exyte.com).

<img src="http://i.imgur.com/o6tBKW6.gif" height="500"> <img src="http://i.imgur.com/Hg0GWAz.gif" height="500"> <img src="http://i.imgur.com/erRavyB.gif" height="500">

# Usage
1. Create `View`'s descendant class for your pages.
2. Create at least two pages and fill them with content.
3. Create an array of colors (same number as pages).
4. Create ConcentricOnboardingView and place it in your view hierarchy.
```swift
struct ContentView: View {
    var body: some View {
        return ConcentricOnboardingView(pages: <your_pages>, bgColors: <your_colors>)
    }
}
```
5. Pass duration as an argument if you want animation to be faster/slower
```swift
ConcentricOnboardingView(pages: <your_pages>, bgColors: <your_colors>, duration: 2.0)
```

## Customization

All source code is in one single file called ConcentricOnboardingView.swift. To modify something simply copy this file and apply necessary changes.

<img src="http://i.imgur.com/1JXF60f.gif" height="500">

## Examples

To try ConcentricOnboarding examples:
- Clone the repo `https://github.com/exyte/ConcentricOnboarding.git`
- Open terminal and run `cd <ConcentricOnboardingRepo>/Example/`
- Run `pod install` to install all dependencies
- Run open `ConcentricOnboardingExample.xcworkspace/` to open project in the Xcode
- Try it!

## Installation

*CocoaPods*

```ruby
pod "ConcentricOnboarding"
```

*Carthage*

## [Carthage](http://github.com/Carthage/Carthage)

```ogdl
github "Exyte/ConcentricOnboarding"
```

*Manually*

Drop [ConcentricOnboardingView.swift](https://github.com/exyte/ConcentricOnboarding/blob/master/Source/ConcentricOnboardingView.swift) in your project.

## Requirements

* iOS 13.0+
* Xcode 11.0 beta 4+

## Author

This project is maintained by [exyte](https://www.exyte.com). We design and build mobile and VR/AR applications.
