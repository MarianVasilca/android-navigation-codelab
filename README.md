Android Navigation codelab solution
===================================

This repository contains the solution code for the [Navigation Codelab](https://codelabs.developers.google.com/codelabs/android-navigation/)

Introduction
------------

At I/O 2018 Google announced [Android Jetpack](https://developer.android.com//jetpack/), a collection of libraries, tools and architectural guidance to accelerate and simplify the development of great Android apps. One of those libraries is the [Navigation library](https://developer.android.com/topic/libraries/architecture/navigation/). The Navigation Architecture Component simplifies the implementation of navigation in an Android app. You can learn more by reading the [Navigation documentation](https://developer.android.com/topic/libraries/architecture/navigation/).


Pre-requisites
--------------

* Android Studio 3.2 Canary 14 or later and you know how to use it.

* Make sure Android Studio is updated, as well as your SDK and Gradle.
Otherwise, you may have to wait for a while until all the updates are done.

* A device or emulator that runs API level 27

You need to be solidly familiar with the Kotlin programming language,
object-oriented design concepts, and Android Development Fundamentals.
In particular:

* Basic layouts and widgets
* Some familiarity with fragment transitions and deeplinking

Getting Started
---------------

1. [Install Android Studio](https://developer.android.com/studio/install.html),
if you don't already have it.
2. Download the example.
2. Import the example into Android Studio.
3. Build and run the example.

Navigation
------------

The Navigation Architecture Component helps you easily implement common, but complex navigation requirements, while also helping you visualize your app's navigation flow. The library provides a number of benefits, including:

1. Handling fragment transactions
2. Handling up and back correctly by default
3. Provides defaults for animations and transitions
4. Deep linking is a first class operation
5. Navigation UI patterns like navigation drawers and bottom nav with little additional work
6. Type safety when passing information while navigating
7. Android Studio offers tooling for visualizing and editing the navigation flow of an app

What I learned?
---------------

I learned about:

1. Navigation graph structure
2. NavHostFragment and NavController
3. How to navigate to specific destinations
4. How to navigate by action
5. How to pass arguments between destinations, including using the new safe args plugin
6. Navigating using menus, bottom navs, and navigation drawers
7. Navigating via deep link


Important
---------

Version '1.0.0-alpha01' of Navigation library has a [bug](https://issuetracker.google.com/issues/79407969) that creates overlapping fragments when using the Overflow menu. This issue is reported by Marian Vasilca.

License
-------

Copyright 2018 Google, Inc and Marian Vasilca

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the LICENSE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.