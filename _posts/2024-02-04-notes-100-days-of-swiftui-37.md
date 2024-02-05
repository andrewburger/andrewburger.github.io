---
layout: post
title: 📔 100 Days of SwiftUI (Day 37)
permalink: notes-100-days-of-swiftui-day-37
---

Completed [Day 37](https://www.hackingwithswift.com/100/swiftui/37) in [100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui).

This section revisits the data concepts from yesterday and added a few common ways these [SwiftUI](https://developer.apple.com/documentation/swiftui) elements. We defined a second [View](https://developer.apple.com/documentation/swiftui/view) in a separate source file and called it from the main `ContentView` in the app. We used [JSONDecoder](https://developer.apple.com/documentation/foundation/jsondecoder) to [decode](https://developer.apple.com/documentation/foundation/jsondecoder/2895189-decode) previously saved data from disk. Finally, we used a custom data structure that conforms to the [Codable](https://developer.apple.com/documentation/swift/codable) and [Identifiable](https://developer.apple.com/documentation/swift/identifiable) protocols to create, store, and retrieve unique  data specified from a shared custom class.

It was enlightening to incrementally build a working application that showcases all these components working together.
