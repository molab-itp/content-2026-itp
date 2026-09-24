# 04_DataModel

## [[Previous](./04_swiftui.md)] [[Next](./05_data.md)]

### Managing model data in your app

- iOS 17.0+ | iPadOS 17.0+ | macOS 14.0+ | Xcode 15.0+

- [managing-model-data-in-your-app](https://developer.apple.com/documentation/swiftui/managing-model-data-in-your-app)

[] expand

# -

[] retire

### monitoring-model-data

- iOS 16.2+ | iPadOS 16.2+ | macOS 13.1+ | Xcode 14.3+

- [monitoring-model-data](https://developer.apple.com/documentation/swiftui/monitoring-model-data-changes-in-your-app)

- [Migrating from the Observable Object protocol to the Observable macro](https://developer.apple.com/documentation/swiftui/migrating-from-the-observable-object-protocol-to-the-observable-macro)

#### the basics

- ObservableObject
- @Published
- @StateObject

```
class DataModel: ObservableObject {
    @Published var name = "Some Name"

    @StateObject private var model = DataModel() // Create the state object.
```

#### sharing data between views

- environmentObject
- @EnvironmentObject
- @ObservedObject

```
struct BookReaderApp: App {
    @StateObject private var library = Library()
    LibraryView()
        .environmentObject(library)

class Library: ObservableObject {
    @Published var books: [Book] = [Book(), Book(), Book()]

class Book: ObservableObject, Identifiable {
    @Published var title = "Sample Book Title"

struct LibraryView: View {
    @EnvironmentObject var library: Library

struct LibraryView_Previews: PreviewProvider {
        LibraryView()
            .environmentObject(Library())

struct BookView: View {
    @ObservedObject var book: Book

struct BookEditView: View {
    @ObservedObject var book: Book

```
