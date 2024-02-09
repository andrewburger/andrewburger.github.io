---
layout: post
title: 📔 100 Days of SwiftUI (Day 36)
permalink: notes-100-days-of-swiftui-day-36
---

Finished [Day 36](https://www.hackingwithswift.com/100/swiftui/36) in [100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui).

This section explores data sharing and data persistence with [UserDefaults](https://developer.apple.com/documentation/foundation/userdefaults) in [SwiftUI](https://developer.apple.com/documentation/swiftui). I learned about the  [@Environment](https://developer.apple.com/documentation/swiftui/environment) and  [@AppStorage](https://developer.apple.com/documentation/swiftui/appstorage) property wrappers, the [@Observable](https://developer.apple.com/documentation/observation/observable()) macro in the [Observation](https://developer.apple.com/documentation/observation) framework, and [encoding or decoding custom data types](https://developer.apple.com/documentation/foundation/archives_and_serialization/encoding_and_decoding_custom_types) with [Codable](https://developer.apple.com/documentation/swift/codable).

We covered key concepts with custom types and Codable using [JSONEncoder](https://developer.apple.com/documentation/foundation/jsonencoder) to encode data. Then, we removed data with  [onDelete](https://developer.apple.com/documentation/swiftui/dynamicviewcontent/ondelete(perform:)), the  [EditButton](https://developer.apple.com/documentation/swiftui/editbutton), and [remove(atOffSets)](https://developer.apple.com/documentation/swift/rangereplaceablecollection/remove(atoffsets:)). Finally, we learned how to programmatically dismiss a sheet using [sheet(isPresented)](https://developer.apple.com/documentation/swiftui/view/sheet(ispresented:ondismiss:content:)).

Data storage and persistence is foundational for most apps, so I expect to use these pieces a lot.
