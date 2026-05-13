# 📱 Android Jetpack Compose Course Notes

---

## 📌 1. Introduction to Android Development

Android development is the process of building applications (apps) for devices running the Android Operating System (OS).

* Android apps are packaged as **APK (Android Package)** files
* APK contains:

  * Code
  * Resources
  * Assets

👉 Developers upload APKs to the **Google Play Store** for distribution.

---

## 📦 2. Android SDK (Software Development Kit)

The Android SDK is a collection of tools required to build Android applications.

### Key Points:

* Provides APIs, libraries, and debugging tools
* Helps in building, testing, and managing apps
* Fully supported by Google and the developer community

---

## 🎯 3. Course Learning Objectives

In this course, we will learn:

1. Kotlin Programming Language
2. Android Studio (IDE)
3. Android Ecosystem
4. Core Android Components
5. Building Real Android Applications
6. Publishing Apps on Play Store

---

## 🎨 4. Jetpack Compose

Jetpack Compose is a modern toolkit for building native Android UI.

### Features:

* Less code
* Powerful tools
* Intuitive Kotlin APIs

### Key Idea:

👉 UI is created using **@Composable functions** in Kotlin
👉 No need for XML layouts

---

## 💻 5. Kotlin Programming Language

Kotlin is a **statically typed, open-source programming language**.

### Features:

* Supports OOP + Functional Programming
* Runs on JVM (Java Virtual Machine)
* Interoperable with Java

### Syntax:

Similar to Java, C#, and Scala

---

## ⚖️ 6. Static vs Dynamic Languages

* **Static Language:** Variable type is determined at compile time
* **Dynamic Language:** Variable type is determined at runtime

---

## 🔄 7. Kotlin Overview

* Fully interoperable with Java
* Easy conversion between Java ↔ Kotlin
* Built-in Java-to-Kotlin converter in Android Studio

### Advantages:

* Less code
* Faster development
* Clean and readable syntax
* Supports Web, Desktop, and Android development

---

## 🧠 8. Basic Programming Concepts

* **Package:** Organizes related classes
* **Class:** Blueprint for objects
* **Object:** Instance of a class (contains properties + functions)
* **OOP:** Programming based on objects and data
* **Function:** Reusable block of code
* **Parameter/Argument:** Value passed to a function

---

## ☕ 9. JDK, JRE, JVM

* **JDK:** Development tools
* **JRE:** Runtime environment
* **JVM:** Executes Java/Kotlin programs

---

## 🧩 10. Jetpack Compose Fundamentals

### 🔹 Layouts

Used to arrange UI components:

* **Row** → Horizontal layout
* **Column** → Vertical layout
* **Box** → Stack layout (overlapping elements)

---

### 🔹 Arrangement & Alignment

👉 **Main Direction = Arrangement**
👉 **Cross Direction = Alignment**

#### Row:

* `horizontalArrangement`
* `verticalAlignment`

#### Column:

* `verticalArrangement`
* `horizontalAlignment`

---

## 📐 11. Row Layout Properties

### Horizontal Arrangement:

* Start
* End
* Center
* SpaceBetween
* SpaceAround
* SpaceEvenly

### Vertical Alignment:

* Top
* CenterVertically
* Bottom

---

## 📐 12. Column Layout Properties

### Vertical Arrangement:

* Top
* Bottom
* Center
* SpaceBetween
* SpaceAround
* SpaceEvenly

### Horizontal Alignment:

* Start
* CenterHorizontally
* End

---

## ➖ 13. Spacer

Spacer is used to create empty space between UI components.

### Types:

* Fixed space → `width()`, `height()`, `size()`
* Flexible space → `weight()`

### Usage:

* Add spacing between elements
* Push components apart
* Control layout spacing

---

## 🔘 14. Button in Jetpack Compose

A Button is a clickable UI component used to perform actions.

### Basic Syntax:

```kotlin
Button(onClick = { }) {
    Text("Click Me")
}
```

### Important Properties:

* `onClick` → Action handler
* `modifier` → Layout & styling
* `colors` → Button colors
* `enabled` → Enable/disable button
* `shape` → Corner design
* `elevation` → Shadow
* `border` → Outline
* `content` → UI inside button

---

## 📝 15. TextField (User Input)

TextField is used to take input from the user.

### State Management:

```kotlin
var text by remember { mutableStateOf("") }
```

### Important Properties:

* `value` → Current text
* `onValueChange` → Updates text
* `label` → Hint text
* `modifier` → Layout control
* `colors` → Styling

---

## 🔄 16. Recomposition (Very Important)

When state changes, Compose automatically updates only the affected UI.

👉 No manual UI refresh required

---

## 🧱 17. Modifier System

Modifiers are used to customize UI elements.

### Example:

```kotlin
Modifier
    .fillMaxWidth()
    .padding(16.dp)
    .background(Color.Gray)
```

👉 Modifiers can be chained together

---

## 🖼️ 18. Image in Compose

Used to display images from different sources:

* Drawable resources
* Bitmap
* Painter
* URL (using libraries like Coil)

### Important Properties:

* `painter`
* `contentDescription`
* `modifier`
* `contentScale`
* `alignment`

---

## ☑️ 19. CheckBox

A CheckBox is a two-state component:

* Checked
* Unchecked

Used for selections and user input.

---

## 📌 20. Switch

A Switch in Jetpack Compose is a UI component used to toggle between two states — ON and OFF. It is commonly used in settings screens for enabling or disabling features.

It works using a boolean state (true or false) and updates through the onCheckedChange callback when the user interacts with it.

---

## 🧠 21. Stateful vs Stateless Composables

* **Stateful:** Manages its own state
* **Stateless:** Receives state from outside

---

##  📌 22. DropdownMenu

`DropdownMenu` is used in Jetpack Compose to display a list of selectable menu items in a popup menu.

### Properties of DropdownMenu

* `expanded` → Controls whether the menu is visible or hidden.
* `onDismissRequest` → Called when the menu should close (outside click/back press).
* `modifier` → Used to style or position the menu.
* `offset` → Changes the menu position relative to its anchor.
* `properties` → Controls additional popup behavior.

---

## 📌 23. DropdownMenuItem

`DropdownMenuItem` represents a single selectable option inside a `DropdownMenu`.

### Properties of DropdownMenuItem

* `text` → Displays the content/text of the item.
* `onClick` → Executes when the item is selected.
* `leadingIcon` → Adds an icon at the start.
* `trailingIcon` → Adds an icon at the end.
* `enabled` → Enables or disables item selection.
* `colors` → Customizes item colors.
* `contentPadding` → Adjusts spacing inside the item.

---
