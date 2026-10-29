# Week 09 Multi User Experience 1

## [[Previous](./08_video.md)] [[Next](./10_multi.md)]

## COURSE OBJECTIVES -- reminder --

- At the completion of this course, the student should be able to:
- use the Swift language to create iOS apps that use native hardware capabilities
- research Apple developer documentation and sample code to use Apple developer frameworks effectively
- research open source libraries to rapidly add features to native iOS apps
- become familiar with the Xcode development workflow
- [evaluation](https://github.com/molab-itp/content-2026-itp#evaluation)

## Plan

- discussion
  - **what has iphone apps enabled ?**
- review homework
- questions
- summarize your challenges (and progress) on your wiki page
- saving data local on the device and remotely in the cloud
- Testflight update of MoGallery confirm - post an image

## Sample Apps

**tracking time**

- [Slide Show Delay](https://github.com/molab-itp/09-SlideShowDelay)
  - slide show with slider for delay

**Using MapKit**

- [09-Location](https://github.com/molab-itp/09-Location)
  - in Simulator > Location > Features > Custom Location
- [09-Bucketlist](https://github.com/molab-itp/09-Bucketlist)
  - Saves data to local Documents folder as SavedPlaces JSON file

**Saving Data - Local**

- [06-ChipsSaveJSON](https://github.com/molab-itp/06-ChipsSaveJSON)
- [07-ImageEditDemoJSON](https://github.com/molab-itp/07-ImageEditDemoJSON)

**Saving Data - Cloud**

- [09-AnonLobbyCloud](https://github.com/molab-itp/09-AnonLobbyCloud)
  - Anonymous Lobby for Firebase
  - in private class repo
- [09-ChipsLobbyCloud](https://github.com/molab-itp/09-ChipsLobbyCloud)
  - in private class repo
  - prior version

**Firebase big picture docs**

- [video - Firebase Fundamentals](https://www.youtube.com/watch?v=p9pgI3Mg-So&list=PLl-K7zZEsYLnfwBe4WgEw9ao0J0N1LYDR&index=7) ~40 minutes
- [video - Getting started with Cloud Firestore on Apple platforms](https://www.youtube.com/watch?v=1Fg7cwkmj_c&list=PLl-K7zZEsYLnfwBe4WgEw9ao0J0N1LYDR&index=30)
- [Firebase cloud firestore](https://firebase.google.com/docs/firestore?authuser=0)
- [Firebase storage ](https://firebase.google.com/docs/storage/ios/start?hl=en&authuser=0)
- [Firebase auth](https://firebase.google.com/docs/auth?hl=en&authuser=0)

<!-- - [Firebase database](https://firebase.google.com/docs/database/ios/read-and-write?hl=en&authuser=0) -->
<!-- - [Getting started with Cloud Firestore for the web](https://www.youtube.com/watch?v=BjtxPj6jRM8&list=PLl-K7zZEsYLnfwBe4WgEw9ao0J0N1LYDR&index=54) -->
<!-- - [Getting started with the Firebase Realtime Database on the web](https://www.youtube.com/watch?v=pP7quzFmWBY) ~11 minutes -->

## MoGallery App

- [98-MoGallery-Private](https://github.com/molab-itp/98-MoGallery-Private)
  - private repo with MoGallery/MoGallery/GoogleService-Info.plist
  - run on the your iOS device to access firebase project configured for this class
  - Use MoLobby project for Lobby only functions
- [98-MoGallery](https://github.com/molab-itp/98-MoGallery)
  - public repo, no GoogleService-Info.plist
  - must create your own [firebase project - a container for you app](https://firebase.google.com/)

## MoGallery cloud data

- [firebase cloud firestore](https://console.firebase.google.com/u/0/project/molab-485f5/firestore/databases/-default-/data/~2Fgstore~2Fmo-5)
- [firebase storage](https://console.firebase.google.com/u/0/project/molab-485f5/storage/molab-485f5.appspot.com/files/~2F-mo~2Fmo-1)
<!-- - [firebase realtime database](https://console.firebase.google.com/u/0/project/molab-485f5/database/molab-485f5-default-rtdb/data/~2Fmo-1) -->

## Re-using Example Code

- in class exercises
- removed unused code
- renaming project

## Firebase Resources

**Firebase Offical Docs**

- https://firebase.google.com/docs/auth
- https://firebase.google.com/docs/firestore
- https://firebase.google.com/docs/storage
<!-- - https://firebase.google.com/docs/database -->

**Firebase Tutorial - FireCards**

- https://www.kodeco.com/11609977-getting-started-with-cloud-firestore-and-swiftui
  - FireCards Firebase Console
    - https://console.firebase.google.com/u/0/project/firecards-77c11/firestore
- **FireCards project updated for current SDK in class private repo**
  - https://github.com/molab-itp/09-FireCards

### Firebase Tutorial - MakeItSo

- https://peterfriese.github.io/MakeItSo/tutorials/makeitso/
  - Chapter 1 to chapter 4
    - https://peterfriese.github.io/MakeItSo/tutorials/makeitso/#building-a-simple-ui
    - https://peterfriese.github.io/MakeItSo/tutorials/makeitso/#storing-data-in-the-cloud
  - Skip
    - https://peterfriese.github.io/MakeItSo/tutorials/makeitso/02-developing-locally-with-the-emulator-suite
  - MakeItSo Firebase Console
    - https://console.firebase.google.com/u/0/project/makeitso-faa35/firestore
- **MakeItSo project updated for current SDK in class private repo**
  - https://github.com/molab-itp/09-MakeItSo

## combine-vs-async docs

- https://peterfriese.dev/blog/2022/combine-vs-async/
  - https://github.com/peterfriese/SwiftUI-Concurrency-Essentials
- https://peterfriese.dev/blog/2022/firebase-async-calls-swift/

## Homework Week09

- Part 1:
  - Prepare first draft of your final project proposal. Ok to entertain more than one initial concept.
- Part 2:
  - **Option 1:**
  - setup a firebase project and build one of the firebase tutorial apps
  - use our class repo to get the appropriate Firebase SDK version for the tutorial
    - FireCards
      - https://github.com/molab-itp/09-FireCards
    - MakeItSo
      - https://github.com/molab-itp/09-MakeItSo
  - **Option 2:**
  - customize the **MoLobby** app in
    - [98-MoGallery-Private](https://github.com/molab-itp/98-MoGallery-Private)
    - with your own multi-user experience twist
    - fork the repo and create a branch labeled with your name
- create a Week09 folder for your project and add link to it here
- [wiki home page week09](https://github.com/molab-itp/content-2026-itp/wiki#week-09-homework)
  - update your wiki page with your
    - progress | problems | plans | questions

<!-- - [05-ImageEditDemo](https://github.com/molab-itp/05-ImageEditDemo) -->

<!-- ## Guest developer
- Adam Jonah
  - [cleanandchecked2 app](https://github.com/supertutorai/demoproject)
    - scan bar code of product to get nut
  - https://apps.apple.com/us/app/tutto-get-flirty/id6471154924
    - tuttO - get flirty!
  - https://apps.apple.com/us/app/big-signal-summon-help-1click/id6472224823
    - BIG SIGNAL: SUMMON HELP 1CLICK
    - [source adamjonah](https://github.com/adamjonah/bigsignalapps)
    - [source molab-itp](https://github.com/molab-itp/bigsignalapps)
      - preparing for open source collaboration -->

<!-- - [CaptureRecorder](https://github.com/jht9629-nyu/CaptureRecorder.git)
  - apply core image filters to live video stream from camera
  - record button to save video to Photo library
  - minminal ObservableObject Model
  - no need for Combine! -->
