# Week 07 Photo Media

## [[Previous](./06_data.md)] [[Next](./08_video.md)]

## Plan

- review homework
- questions
- summarize your progress (and challenges) on your wiki page
- feedback
- break
- photo library access

### Demo Apps

- [07-Instafilter](https://github.com/molab-itp/07-Instafilter)
  - A photo manipulation program using Core Image filters
  - uses PhotosPicker from import PhotosUI
- [07-PhotoPickBlender](https://github.com/molab-itp/07-PhotoPickBlender)
  - use Vision framework VNGeneratePersonSegmentationRequest to blend two photos
  - using legacy api via UIViewControllerRepresentable
- [07-FaceMesh](https://github.com/molab-itp/07-FaceMesh)
  - Face Mesh with ARKit and SwiftUI
  - using legacy api via UIViewControllerRepresentable

### Resources

- [PhotosPicker Apple Sample Code](https://developer.apple.com/documentation/photokit/bringing-photos-picker-to-your-swiftui-app)
  - click on pencil to edit profile pict
- [@Observable class - iOS 17](https://developer.apple.com/documentation/swiftui/managing-model-data-in-your-app)
- [from ObservableObject interface to @Observable macro](https://developer.apple.com/documentation/swiftui/migrating-from-the-observable-object-protocol-to-the-observable-macro)
- **hackingwithswift**
- [sharing-swiftui-state-with-observable](https://www.hackingwithswift.com/books/ios-swiftui/sharing-swiftui-state-with-observable)
- [adding-codable-conformance-to-an-observable-class](https://www.hackingwithswift.com/books/ios-swiftui/adding-codable-conformance-to-an-observable-class)

#### Legacy api's - prior to iOS 17

- [What’s the difference between @ObservedObject, @State, and @EnvironmentObject?](https://www.hackingwithswift.com/quick-start/swiftui/whats-the-difference-between-observedobject-state-and-environmentobject)
- [managing-model-data-in-your-app - apple dev doc](https://developer.apple.com/documentation/swiftui/managing-model-data-in-your-app)
- [Meet the new Photos picker - wwdc video tutorial](https://developer.apple.com/videos/play/wwdc2020/10652/)
- [Selecting Photos and Videos in iOS - apple dev doc](https://developer.apple.com/documentation/photokit/selecting_photos_and_videos_in_ios)
- [Creates a background color based on the average color of an image](https://github.com/bbaars/UIImageAverageColor)
  - [Article](https://medium.com/swlh/swiftui-read-the-average-color-of-an-image-c736adb43000)
- [CoreImageFilterReference ](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/index.html)

## Final Project Inspiration and Resources

- [Create 3D models with Object Capture - wwdc video 2021](https://developer.apple.com/videos/play/wwdc2021/10076/)
- [augmented-reality realitykit](https://developer.apple.com/augmented-reality/realitykit/)
- [augmented-reality object-capture/](https://developer.apple.com/augmented-reality/object-capture/)

## [More Final Project Inspiration and Resources](https://github.com/molab-itp/content-2026-itp/blob/main/weeks/06_data.md#final-project-inspiration-and-resources)

## Homework Week07

- Part 1: midterm check list
- Part 2: create an app to access or manipulate photos
  - you can base it on one of the resources presented in class, adding your own twist
- create a Week07 folder for your project and add link to it here:
  - [wiki home page week07](https://github.com/molab-itp/content-2026-itp/wiki#week-07-homework)
  - update your wiki page with your
    - progress | problems | plans | questions
- Part 3: research final project - explore WWDC videos and sample code - dream: what's possible only on the phone?

<!-- ### Github .gitignore file

```
# How to establish global .gitignore file for github.com accouint
# create .gitignore in home directory
code ~/.gitignore
.DS_Store
**/xcuserdata/
node_modules

# verify created
more .gitignore

# establish global gitigore
git config --global core.excludesfile ~/.gitignore

# verify settings
more .gitconfig
...
[user]
        name = John Henry Thompson
        email = 78864877+jht9629-nyu@users.noreply.github.com
[core]
        excludesfile = /Users/jht2/.gitignore

``` -->
