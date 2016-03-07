# JRMFloatingAnimation

[![CI Status](http://img.shields.io/travis/Caroline Harrison/JRMFloatingAnimation.svg?style=flat)](https://travis-ci.org/Caroline Harrison/JRMFloatingAnimation)
[![Version](https://img.shields.io/cocoapods/v/JRMFloatingAnimation.svg?style=flat)](http://cocoapods.org/pods/JRMFloatingAnimation)
[![License](https://img.shields.io/cocoapods/l/JRMFloatingAnimation.svg?style=flat)](http://cocoapods.org/pods/JRMFloatingAnimation)
[![Platform](https://img.shields.io/cocoapods/p/JRMFloatingAnimation.svg?style=flat)](http://cocoapods.org/pods/JRMFloatingAnimation)

## About

JRMFloatingAnimation is an ObjC library used to create floating image views:

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

To create the animation view:

	self.floatingView = [[JRMFloatingAnimationView alloc] initWithStartingPoint:self.view.center];
	[self.floatingView addImage:[UIImage imageName:@"myImage"];
	[self.view addSubview:self.floatingView];

To animate the view:

	[self.floatingView animate];

There are a variety of different settings you can add to your animation view.

* `startingPointWidth` - Varies the x of the starting point, with the starting point y being the middle. default is 0.
* `maxAnimationHeight` - The maximum height that the animation may go. Default is the distance from the top of the frame to the starting point y value.

## Installation

JRMFloatingAnimation is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "JRMFloatingAnimation"
```

In your code 

## Author

Caroline Harrison, caroline@jackrabbitmobile.com

## License

JRMFloatingAnimation is available under the MIT license. See the LICENSE file for more info.
