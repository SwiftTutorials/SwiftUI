# SwiftUI

##Text
```swift
Text("Text")
    .font(.subheadline)
    .foregroundColor(.secondary)

```
##ForEach

```swift
ForEach([0, 1, 2, 3]) { index in
    Text("line:\(index)")
}
```

##if

```swift
if true {
    Text("Hello true")
} else {
    Text("Hello false")
}
```

##VStack
##HStack
##ZStack
##List

```swift
  List([0, 1, 2]) { index in
    Text("line:\(index)")
}
```

##Section

```swift
Section {
    Text("I am in a Section")
}

```
