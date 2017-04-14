Color With Hex String in Swift
===============

- Simply drag file `Colors.swift` into your project
- Add new color
```swift
static let NEWCOLOR = colorWithHexString("new hex number")
```
or
```swift
extension COLORS {
    static let NEWCOLOR = colorWithHexString("new hex number")
}
```
- Using
```swift
let newColor = COLORS.NEWCOLOR
```
