# Week 03 Swift UI 1, Images

## [[Previous](./02_swift.md)] [[Next](./04_swiftui.md)]

## Plan

- review homework
- questions
- Xcode tips
- intro to SwiftUI
- install sample app on to your phone

## XCode tips

- Command-D replacement

```
"Find > Select Next Occurance (opt + cmd + E)".
Edit in Xcode settings
remove duplicate
```

- Xcode Tips video
  - [31 Xcode Tips & Tricks - 2023](https://www.youtube.com/watch?v=40imnmzsmxk&list=PL8seg1JPkqgEM8oeVghYq_-Go1pVhTGko&index=3)
  - [Xcode + ChatGPT - 2024](https://www.youtube.com/watch?v=zhRyjt6jwPs)

## Resources (from last week)

- [markdownguide quick summary](https://www.markdownguide.org/cheat-sheet/)

- [Swift The Basics - docs.swift.org](https://docs.swift.org/latest/documentation/the-swift-programming-language/thebasics)
- [Optionals](https://docs.swift.org/latest/documentation/the-swift-programming-language/thebasics/#Optionals)
- [Enumerations](https://docs.swift.org/latest/documentation/the-swift-programming-language/enumerations)

<!--
## Othe Swift Language Resources
- [Developer App](https://apps.apple.com/us/app/apple-developer/id640199958)
- google / chat-G: "hacking with swiftui **topic**"
- [swift-cookbook](https://www.kodeco.com/books/swift-cookbook/v1.0/)
-->

## Test Your Swift Programming Skills

- [unwrap app](https://apps.apple.com/us/app/unwrap/id1440611372)
  - works on iPhone iOS and macOS desktops with Apple silicon
- [00-molab-2026-jht](https://github.com/molab-itp/00-molab-2026-jht)
  - playgrounds with TRY: challenges exercises
  - solutions in z-TRIED folder
  - watch out for playground anomlies
    - other pages may execute
    - variables must be set before used
    - show results to see any failures

## Playground review

- Decoding the Apple documentation
  - [03-closures-ints-strings](https://github.com/molab-itp/03-closures-ints-strings)

## SwiftUI Resources

### Getting start with SwiftUI

- [apple documentation swiftui](https://developer.apple.com/documentation/swiftui/)
  - [swiftui/get-started](https://developer.apple.com/swiftui/get-started/)
- [hackingwithswift 100 days](https://www.hackingwithswift.com/100/swiftui)
  Days 16-18: Starting SwiftUI - Project 1 - We Split
  - source: https://github.com/twostraws/HackingWithSwift/tree/main/SwiftUI/project1

## State Counter App Build along

- in class exercise
- [03-counter-state]()
  - Intro to state management with @State
  - Example of using enums

## SwiftUI Example Repo

**build to simulator and to your device**

- [03-About-Me](https://github.com/molab-itp/03-About-Me)
  - https://developer.apple.com/tutorials/sample-apps/aboutme
  - using SwiftUI to display information across multiple tab views
- [03-ImageUiDemo-1-symbols](https://github.com/molab-itp/03-ImageUiDemo-1-symbols)
  - Using Image systemName symbols to demonstrate SwiftUI
- [03-ImageUiDemo-2-urls](https://github.com/molab-itp/03-ImageUiDemo-2-urls)
  - Using NavigationView to create list of images references using URL
- [03-Canvas-Explore](https://github.com/molab-itp/03-Canvas-Explore)
  - explore SwiftUI Canvas and TimelineView for computed graphic animation
- [03-UIGraphics-View](https://github.com/molab-itp/03-UIGraphics-View)
  - Display a computed image in SwiftUI View using UIGraphicsImageRenderer
- [03-ClockRemake](https://github.com/molab-itp/03-ClockRemake)
  - Using Canvas to recreate the design used for the Clock app

### SwiftUI full documentation and examples

**From Apple WWDC 2019 - the birth of SwiftUI**

- [WWDC 2019 Introducing SwiftUI: Building Your First App](https://developer.apple.com/videos/play/wwdc2019/204/) ~55min
- [wwdcnotes wwdc19 Introducing SwiftUI: Building Your First App](https://wwdcnotes.com/documentation/wwdcnotes/wwdc19-204-introducing-swiftui-building-your-first-app)
- https://developer.apple.com/videos/play/wwdc2019/204/
  - Introducing SwiftUI: Building Your First App ~55min
- https://developer.apple.com/videos/play/wwdc2019/216/
  - SwiftUI Essentials ~58min
- https://developer.apple.com/videos/play/wwdc2019/226/
  - Data Flow Through SwiftUI ~37min

**From Apple pre-2027 - the middles ages of SwiftUI**

- [Introducing SwiftUI](https://developer.apple.com/tutorials/swiftui)
  - complete up to but not including [interfacing-with-uikit](https://developer.apple.com/tutorials/swiftui/interfacing-with-uikit) - 4hr 25min Estimated Time

**Apple 2027 - new approach - some samples Xcode 27**

- https://developer.apple.com/tutorials/develop-in-swift/welcome-to-swiftui
  - Welcome to SwiftUI
- https://developer.apple.com/documentation/swiftui/
- https://developer.apple.com/documentation/swiftui/wishlist-planning-travel-in-a-swiftui-app
  - Wishlist: Planning travel in a SwiftUI app
  - requires Xcode 27

**From Paul Hudson - hacking with swift**

- https://www.hackingwithswift.com/books/ios-swiftui
  - Hacking with iOS: SwiftUI Edition - 21 projects
- https://github.com/twostraws/hackingwithswift
- Hacking with Swift source code
- Project 1: WeSplit source:
  - https://github.com/twostraws/HackingWithSwift/tree/main/SwiftUI/project1
- Project 14: Bucket List
  - https://www.hackingwithswift.com/books/ios-swiftui/bucket-list-introduction
  - https://www.hackingwithswift.com/books/ios-swiftui/writing-data-to-the-documents-directory
    - reading and writing JSON to local storage - using MapKit - source:
    - https://github.com/twostraws/HackingWithSwift/tree/main/SwiftUI/project14/Bucketlist
- **https://www.hackingwithswift.com/100/swiftui**
  - 19 projects -- looks like projects are shared with books/ios-swiftui
- [hackingwithswift](https://www.hackingwithswift.com/books/ios-swiftui)
  - [github hackingwithswift](https://github.com/twostraws/hackingwithswift)
  - project based, select the project(s) that you find interesting
- [www.hackingwithswift.com -- 100 days of swiftui](https://www.hackingwithswift.com/100/swiftui)
  - source: https://github.com/twostraws/HackingWithSwift/tree/main/SwiftUI

## Homework Week03

**Part 0. (Optional) exercises**

- complete any of the TRY: exercises in
- [00-molab-2026-jht](https://github.com/molab-itp/00-molab-2026-jht)
- don't peek at solutions
- work out solution on paper before entering code
- avoid all use of AI, except to look up or explain documentation

**Part 1.**

- complete any missing work
- continue exploring swift fundatmentals
- update your wiki page with a description of how you approached learning swift fundatmentals and your weekly progress.
- begin swiftui tutorials
  - pick a path thats best for you
- create a multi view SwiftUI app that displays an image that is composed of random elements
  - similar to 10print in
  - [03-Canvas-Explore](https://github.com/molab-itp/03-Canvas-Explore)
  - make use of arrays and random numbers
  - ok to run in simulator
- add a link to your project stored in your Week03 folder on
  - [wiki home page week03](https://github.com/molab-itp/content-2026-itp/wiki#week-03-homework)
- document your progress and questions on your wiki page
