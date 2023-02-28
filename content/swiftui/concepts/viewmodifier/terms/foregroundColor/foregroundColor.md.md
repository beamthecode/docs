﻿---
Title: '.foregroundColor()'
Description: 'The .foregroundColor()  modifier sets the foreground color displayed in a view.'
Subjects:
 - 'SwiftUI'
Tags: 
 - 'SwiftUI'
 - 'Modifier'
 - 'View'
 CatalogContent:
 - 'learn-swiftUI'
 - docs/content/swiftui/concepts/viewmodifier/terms/foregroundColor
---

The **`.foregroundColor()`** modifier sets the foreground color displayed in a [View](https://www.codecademy.com/resources/docs/swiftui/views).

## Syntax

```
struct MyView: View {
  var body: some View {
   Text("We are setting the foreground color to green!")
    .foregroundColor(.green)
	}
 }
 ```

The `.foregroundColor(green)` is applying the color green to the `Text` (which conforms to the `View` protocol). 

## Example

```
struct ContentView: View {
 var body: some View {
  Text("We are setting the foreground color to green!")
   .foregroundColor(.green)
	}
 }
 ```

In the above example, the `foregroundColor(.green)` modifier is called on the `Text` view. This applies the color green to all characters within the `Text`.

This will display the following:

![SwiftUI ViewModifier .foregroundColor()](https://raw.githubusercontent.com/Codecademy/docs/main/media/SwiftUI-foregroundColor-display.png)
