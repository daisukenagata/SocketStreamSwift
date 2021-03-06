# SocketStreamSwift

[![CI Status](https://img.shields.io/travis/daisukenagata/SocketStreamSwift.svg?style=flat)](https://travis-ci.org/daisukenagata/SocketStreamSwift)
[![Version](https://img.shields.io/cocoapods/v/SocketStreamSwift.svg?style=flat)](https://cocoapods.org/pods/SocketStreamSwift)
[![License](https://img.shields.io/cocoapods/l/SocketStreamSwift.svg?style=flat)](https://cocoapods.org/pods/SocketStreamSwift)
[![Platform](https://img.shields.io/cocoapods/p/SocketStreamSwift.svg?style=flat)](https://cocoapods.org/pods/SocketStreamSwift)


<p align="center">
<img width="300" height="400" src="https://user-images.githubusercontent.com/16457165/62090081-80feac80-b2a6-11e9-8193-bbc5c0c6294d.png">
</p>

# [Reference](https://github.com/daisukenagata/SocketStreamSwift/wiki)

Effort to implement default chat application in Swift5.

開発環境　Swift5.0 Python3.7.3  how to python3 install
[PythonFile](https://github.com/daisukenagata/PythonFile)
```
command enter
$ cd SocketStreamSwift 
you have Python3.7.3  
$ python soc.py
```
set ip address
```
SocketStream(url: URL(string:"wss://localhost")!, hostNumber: UInt32(8000))
```
 
<img src="https://user-images.githubusercontent.com/16457165/58570199-82920100-8272-11e9-8a12-d71bb34b9f37.gif"  width="1100"  height="500">

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

SocketStreamSwift is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'SocketStreamSwift'
```

## [Charthage](https://github.com/Carthage/Carthage)

Officially supported: Carthage 0.33 and up.

Add this to Cartfile
```
github "daisukenagata/SocketStreamSwift"
```

Terminal command
```bash
$ carthage update --platform iOS
```

## Author

daisukenagata, dbank0208@gmail.com

## License

SocketStreamSwift is available under the MIT license. See the LICENSE file for more info.
