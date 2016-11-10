# HGCircularSlider

[![Twitter: @GhazouaniHamza](https://img.shields.io/badge/contact-@GhazouaniHamza-blue.svg?style=flat)](https://twitter.com/GhazouaniHamza)
[![CI Status](http://img.shields.io/travis/HamzaGhazouani/HGCircularSlider.svg?style=flat)](https://travis-ci.org/Hamza Ghazouani/HGCircularSlider)
[![Version](https://img.shields.io/cocoapods/v/HGCircularSlider.svg?style=flat)](http://cocoapods.org/pods/HGCircularSlider)
[![License](https://img.shields.io/cocoapods/l/HGCircularSlider.svg?style=flat)](http://cocoapods.org/pods/HGCircularSlider)
[![Platform](https://img.shields.io/cocoapods/p/HGCircularSlider.svg?style=flat)](http://cocoapods.org/pods/HGCircularSlider) <br />

[![Readme Score](http://readme-score-api.herokuapp.com/score.svg?url=https://github.com/hamzaghazouani/hgcircularslider/)](http://clayallsopp.github.io/readme-score?url=https://github.com/hamzaghazouani/hgcircularslider/tree/develop)
[![codebeat badge](https://codebeat.co/badges/c4db03f5-903a-4b0e-84bb-98362fc5bd7a)](https://codebeat.co/projects/github-com-hamzaghazouani-hgcircularslider)

## Example

![](/Screenshots/Clock.gif) ![](/Screenshots/Player.gif) ![](/Screenshots/OClock.gif)  ![](/Screenshots/BasicExample.gif)

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

- iOS 7.1+
- Xcode 7.3

## Installation

HGCircularSlider is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

``` ruby
# Swift 2.2 - Xcode 7.3.1
pod 'HGCircularSlider', '~> 0.1.1'
```
## Usage

1. Change the class of a view from UIView to CircularSlider, RangeCircularSlider or MidPointCircularSlider
2. Programmatically:

```
let circularSlider = CircularSlider(frame: myFrame)
 ``` 
 OR
```
let circularSlider = RangeCircularSlider(frame: myFrame)
 ``` 
 OR
```
 let circularSlider = MidPointCircularSlider(frame: myFrame)
```
## Documentation
You can  install documentation locally using [jazzy](https://github.com/realm/jazzy).
<!-- Full API documentation is available on [CocoaDocs](http://cocoadocs.org/docsets/HGCircularSlider/).<br/> -->

## References 
The UI examples of the demo project inspired from [Dribbble](https://github.com/realm/jazzy).

 [Player](https://dribbble.com/shots/3062636-Countdown-Timer-Daily-UI-014)
 [BasicExample](https://dribbble.com/shots/2153963-Dompet-Wallet-App)
 [OClock](https://dribbble.com/shots/2671286-Clock-Alarm-app)

The project is Inspired from [UICircularSlider](https://github.com/Zedenem/UICircularSlider)

## Author

Hamza Ghazouani, hamza.ghazouani@gmail.com

## License

HGCircularSlider is available under the MIT license. See the LICENSE file for more info.
