# TeadsSDK-ios
Teads allows you to integrate a single SDK into your app, and serve premium branded "outstream" video ads from Teads SSP ad server. This sample app includes Teads iOS library and is showing integration examples.

## Run the sample app

Clone this repository, open it with Xcode, and run project.

## Install the Teads SDK iOS library

Teads SDK is currently distributed through CocoaPods. It include everything you need to serve "outstream" video ads.

### Cocoapods

```
target 'YourProject' do
    pod 'TeadsSDK', '4.8.0'
end
```

In terminal in the directory containing your project's `.xcodeproj` file and the Podfile, run `pod install` command. This will install Teads SDK along with our needed dependencies.
