# cordova-plugin-carthage-support


## Supported Platforms
- iOS

## Supported version
Ruby(>=2.3.0)  
Node(>=6.13.1)  
Cordova(>=6.5)  
Carthage(>=0.2)  

## Requirement
https://github.com/Carthage/Carthage  
https://github.com/CocoaPods/Xcodeproj  
https://github.com/Leonidas-from-XIV/node-xml2js  

## Installation
```
cordova plugin add https://github.com/nrikiji/cordova-plugin-carthage-support.git
```

## Usage、Example



plugin.xml
```
<carthage>
  <cartfile>github "line/line-sdk-ios-swift" ~> 5.0</cartfile>
  <framework src="LineSDK.framework"/>
  <framework src="LineSDKObjC.framework"/>
</carthage>
```

2. `cordova prepare ios
