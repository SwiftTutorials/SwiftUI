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

```swift
VStack() {
    Text("Hello World")
    Text("Hello VStack")
}
```

## HStack

A view that arranges its children in a horizontal line.


```swift
HStack() {
    Text("Hello World")
    Text("Hello HStack")
}
```

## ZStack

A view that overlays its children, aligning them in both axes.

```swift
ZStack() {
    Text("Hello World")
    Text("Hello ZStack")
}
```

## List

 A container that presents rows of data arranged in a single column.

```swift
  List([0, 1, 2]) { index in
    Text("line:\(index)")
}
```

## Section
An affordance for creating hierarchical view content.
```swift
Section {
    Text("I am in a Section")
}

```

## Toggle

A control that toggles between on and off states.

```swift
struct FooView : View {
    @State var toggle: Bool
    
    var body: some View {
        
        Toggle(isOn: $toggle) {
            Text("$toggle")
        }
    }
}

```

## Stepper

A control used to perform semantic increment and decrement actions.
```swift
struct BarView : View {
    @State var stepper: Int
    
    var body: some View {
        Stepper(value:$stepper, in: 1...10) {
            Text("stepper")
        }
    }
}

```

## Button

A control that performs an action when triggered.

```swift
Button(action: { }) {
    Image("foo")
    Text("Button")
}

```

## Reference

[SwiftUI Doc](https://developer.apple.com/documentation/swiftui)

[wwdc2019 SwiftUI Essentials](https://developer.apple.com/videos/play/wwdc2019/216)