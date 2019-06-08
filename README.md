# SwiftUI

## Text

```swift
Text("Text")
    .font(.subheadline)
    .foregroundColor(.secondary)

```

## ForEach

```swift
ForEach([0, 1, 2, 3]) { index in
    Text("line:\(index)")
}
```

## if

```swift
if true {
    Text("Hello true")
} else {
    Text("Hello false")
}
```

## VStack

A view that arranges its children in a vertical line.

## HStack

A view that arranges its children in a horizontal line.

## ZStack

A view that overlays its children, aligning them in both axes.

## List

 A container that presents rows of data arranged in a single column.

```swift
  List([0, 1, 2]) { index in
    Text("line:\(index)")
}
```

## Section

```swift
Section {
    Text("I am in a Section")
}

```
