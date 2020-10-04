# How Can I Image Masking?

<img height="500px" src="https://github.com/kadir-ince/How-Can-I-Do/blob/master/SwiftUI/Image-Masking/Image-Masking.png" alt="Image-Masking?">

```swift
Image("image-name")
    .resizable().aspectRatio(contentMode: .fit)
    .mask(Text("GLP"))
    .font(.system(size: 200, weight: .heavy, design: .rounded))
    .shadow(radius: 15)
```
