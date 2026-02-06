# Android-JetPack-Compose-Course
## What is Android Development?

Android development is a software creation process that focuses on applications, better known as apps, that are compatible with devices running the Android operating system (OS).
The Android SDK tools compile your code along with any data and resource files into an APK, or Android package, which is an archive file that uses an .apk suffix.
One APK file contains all Android app contents used by devices to install your app. When the app is complete and ready for release, Android developers can upload their apps to the Google Play Store for users to download.

## What is Android SDK and why is it important?

1. Android SDK refers to the Android Software Development Kit.

2. Android SDK is a collection of tools that have been released and supported for the express purpose of creating Android software. Through the Android SDK, programmers can collect, create, and manage their code. It is a comprehensive development environment that is well-supported, not only by the Android team but also by its community.

## What Will We Learn?

We will learn:
1. Kotlin Programming Language
2. Android Studio
3. Android Ecosystem
4. Android Components
5. Developing Two Android Apps
6. Publishing Apps on the Google Play Store

## What is Jetpack Compose?

1. It is a toolkit for building native UI.
   
2. It simplifies and accelerates UI development with:
    (a) Less code
    (b) Powerful tools
    (c) Intuitive Kotlin APIs

3. With Jetpack Compose, we no longer need to design UI with XML. We create their views directly within the Kotlin class, just like we write code.
   
4. We use Jetpack compose because it allows us to write less code; it is intuitive; it accelerates the development process; it is powerful. 

## What is Kotlin?

1. It is an Open-source and static language. It takes its name from Kotlin Island, a russain island in the Gulf of Finland.

2. It supports both object-oriented and functional programming.
 
4. It runs on the Java Virtual Machine (JVM).
 
5. It's syntax similar to languages such as java, C#, Scala.

## What is Static and Dynamic Language?
1. Static Programming languages are languages in which variables types determined before runtime (at compile time).

2. Dynamic Programming languages are languages in which variable types determined at program runtime.


## Kotlin Overview

1. Interoperable with Java programming language.

2. You can easily convert between Kotlin and Java codes.

3. There is also an autmatic Java-to-Kotlin converter built into Android Studio.

## By Using Kotlin:

1. Fewer Lines of code

2. Faster compilation

3. Much simpler and more understandable structure.

4. You can develop Web, Desktop and Android Applications wiith Kotlin.

## Basic Programming Terms

1. Package: used to organize classes that belong to the same category or provide related functionality.

2. Class: refers to set of related objects with common properties in object oriented programming

3. Object: It is a combination of related variables, constants, and other data structure which can be selected and manipulated together.

4. Object Oriented Programming: It is a model defined by programmers that revolve around objects and data rather than actions and logic.

5. Function or method: It is a block of codes that can be referenced by name to run the code it contains.

6. Argument or parameter: It is a value that is passed into a command or a function.

## JDK, JRE and JVM
<img width="1573" height="925" alt="image" src="https://github.com/user-attachments/assets/cdc2c9e4-574f-4562-9c32-d47bdfd6bae7" />

## Components in JetPack Compose

Components in JetPack Compose are:

1. Layout : It is an interface that we use to place android components on the android application. We use layouts to establish components in a particular order. Basically three main layouts are: Column (Vertically aligns), Row (Horizonatally aligns) and Box (Top of one Another aligns).
   
2. Arrangements:  Arrangement refers to how child elements are positioned and spaced inside a layout container along its main direction (horizontal in Row and vertical in Column). It controls how space is distributed between and around components.

3. Alignments: Alignment refers to how child elements are placed relative to the cross direction of a layout container (vertical alignment in Row and horizontal alignment in Column). It controls how elements line up perpendicular to the main direction.

### Alignments and Arrangments

#### Row

1. *horizontalArrangement* → controls spacing horizontally

2. *verticalAlignment* → controls alignment vertically

#### Column

1. *verticalArrangement* → controls spacing vertically

2. *horizontalAlignment* → controls alignment horizontally

### Note: Row manages elements horizontally, so it uses horizontal arrangement and vertical alignment. Column manages elements vertically, so it uses vertical arrangement and horizontal alignment.

## Row Layout Properties

### horizontalArrangement (Main Direction → Horizontal) : Controls spacing between elements inside a Row.

1. Arrangement.Start → Items placed at the beginning

2. Arrangement.End → Items placed at the end

3. Arrangement.Center → Items placed at the center

4. Arrangement.SpaceBetween → Equal space between items, no space at ends

5. Arrangement.SpaceAround → Equal space around items (edges get half space)

6. Arrangement.SpaceEvenly → Equal space everywhere (including edges)

### verticalAlignment (Cross Direction → Vertical) : Controls vertical alignment of items inside a Row.

1. Alignment.Top → Align items to top

2. Alignment.CenterVertically → Align items in vertical center

3. Alignment.Bottom → Align items to bottom

## Column Layout Properties

### verticalArrangement (Main Direction → Vertical) : Controls spacing between elements inside a Column.

1. Arrangement.Top → Items placed at the top

2. Arrangement.Bottom → Items placed at the bottom

3. Arrangement.Center → Items placed at the center

4. Arrangement.SpaceBetween → Equal space between items

5. Arrangement.SpaceAround → Equal space around items

6. Arrangement.SpaceEvenly → Equal space everywhere


### horizontalAlignment (Cross Direction → Horizontal) : Controls horizontal alignment of items inside a Column.

1. Alignment.Start → Align items to left/start

2. Alignment.CenterHorizontally → Align items in horizontal center

3. Alignment.End → Align items to right/end


## Spacer : What should we do if we want to leave the desired distance between components?

For leaving the desired distance between components, we use a composable function called *spacer*.
A Spacer is a structure we use to keep distance between components.
