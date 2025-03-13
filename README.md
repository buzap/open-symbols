# Open Symbols

Open Symbols is a collection of [SF Symbols](https://developer.apple.com/sf-symbols/) converted from popular open source icon sets, making them seamlessly available for your Apple platform applications.

Symbols are converted using [SymbolKit App](https://symbolkit.app) developed by me. The app is still under development, you can sign up to receive notifications when it's ready from it's website.

## 📦 Symbol Sets

Currently available sets:

- [Heroicons](heroicons/README.md) - Beautiful hand-crafted SVG icons, by the makers of Tailwind CSS.
<img width="1276" alt="image" src="https://github.com/user-attachments/assets/8d39f19c-2565-4fab-b6f8-c53b9f869129" />

- [Font Awesome](font-awesome/README.md) - Font Awesome is the Internet's icon library and toolkit, used by millions of designers, developers, and content creators.
<img width="850" alt="image" src="https://github.com/user-attachments/assets/6be51cce-1c52-4325-93b8-69a467e546fd" />

- [Lucide](lucide/README.md) - Beautiful & consistent icons made by the community.
<img width="527" alt="image" src="https://github.com/user-attachments/assets/6e0ca1c3-b7be-4595-a66b-93b322f743d8" />

- [RemixIcons](remix/README.md) - A collection of carefully designed icons.
<img width="1188" alt="image" src="https://github.com/user-attachments/assets/2f36af50-21fc-49e1-9c08-b6bf92026d19" />

🚀 More icon sets will be added soon! Follow this repository to stay updated.

## 🛠️ Usage

Download the symbols you want to use and add them to your Xcode assets catalog.

To download symbols right now, you can use the 'Download raw file' button on the GitHub page, or clone the repository to your local machine and copy the files you want to use.

In the future, you can search and download symbols from [https://opensymbols.dev](https://opensymbols.dev).

```swift
// Example usage with SwiftUI
Image(systemName: "android")
    .font(.largeTitle)
    .foregroundColor(.blue)

// Example usage with UIKit
let imageView = UIImageView()
imageView.image = UIImage(systemName: "android")?.withTintColor(.red)
```

## 🚧 Limitations

Right now, the symbols have no weight variation. I'm working on adding weight variations to symbol sets.

## 💜 Sponsor

If you like this project, please consider sponsoring me. It motivates me to continue working on it! You can sponsor me on [Buy Me a Coffee](https://buymeacoffee.com/shawnchen).

## 📝 License

Each symbol set is released under the same license as the original icon set. Everything else in this repository is licensed under the MIT License.

## 🙏 Acknowledgments

Thanks to the creators of the original icon sets for their beautiful work!
