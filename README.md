# Open Symbols

Open Symbols is a collection of [SF Symbols](https://developer.apple.com/sf-symbols/) converted from popular open source icon sets, making them seamlessly available for your Apple platform applications.

## ✨ Features

-   High-quality SF Symbols converted from trusted open source icon sets
-   Easy integration with SwiftUI, UIKit, and AppKit

## 📦 Symbol Sets

Currently available sets:

-   [RemixIcons](remix/README.md) - A collection of carefully designed icons from [RemixIcons](https://remixicon.com/)

> 🚀 More icon sets will be added soon! Follow this repository to stay updated.

## 🛠️ Usage

Download the symbols you want to use and add them to your Xcode assets catalog.

```swift
// Example usage with SwiftUI
Image(systemName: "android")
    .font(.largeTitle)
    .foregroundColor(.blue)

// Example usage with UIKit
let imageView = UIImageView()
imageView.image = UIImage(systemName: "android")?.withTintColor(.red)
```

## 📝 License

Each symbol set is released under the same license as the original icon set. Everything else in this repository is licensed under the MIT License.

## 🙏 Acknowledgments

Thanks to the creators of the original icon sets for their beautiful work!
