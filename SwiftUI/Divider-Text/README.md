# How Can I Create Text Between Two Divider?

<img height=100% src="https://github.com/kadir-ince/How-Can-I-Do/tree/master/SwiftUI/Divider-Text/Divider-Text.png" alt="What's like?">

```swift
HStack {
    VStack {
        Divider()
            .background(Color(.white))
    }
    Text("OR")
        .padding(.horizontal)
    VStack {
        Divider()
            .background(Color(.white))
    }
}
.padding(.horizontal)
.padding(.vertical)
```
