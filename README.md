#  # Device
A lightweight Swift Package extension for `UIDevice` that maps hardware identifiers (e.g., `iPhone17,2`) to human-readable device marketing names (e.g., `iPhone 17 Pro`).

## Features
- 📱 Converts internal device identifiers into official marketing names.
- ⚡️ Lightweight with zero third-party dependencies.
- 🔄 Easy integration via Swift Package Manager (SPM).
- 🧪 Supports simulator detection (returns simulated device model with indicator).

## Requirements
- iOS 18+
- Swift 5.9+
- Xcode 15.0+

## Installation
### Swift Package Manager
You can add this package to your project using Xcode:
1. Open your project in Xcode.
2. Go to **File > Add Package Dependencies...**
3. Paste the repository URL:
```swift
https://github.com/vitya87ua/Device.git
```

## Usage
```swift
import Device

// Get the friendly device name
let deviceName: String = UIDevice.modelName
print(deviceName) // Output: "iPhone 17 Pro Max" or "iPad Pro M5 13-inch"
```
