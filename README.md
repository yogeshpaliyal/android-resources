# Android-Resources
![android-resources-cover](./cover.jpeg)

<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fyogeshpaliyal%2Fandroid-resources&count_bg=%2379C83D&title_bg=%23555555&title=hits&style=for-the-badge%22" alt="visitCount">

This repository serves as a curated collection of valuable resources related to Android development. It aims to provide developers with a centralized hub to discover and explore informative content on various Android-specific topics, including, internals of android, performance optimization, architectural patterns, testing methodologies, popular libraries and tools, and best practices.

## Table of Contents
- [Internals](#internals)
  - [Android](#android)
  - [Kotlin](#kotlin)
  - [Popular Libraries](#popular-libraries)
    - [Coroutines](#coroutines)
- [Performance](#performance)
  - [Baseline Profiles](#baseline-profiles)
  - [Startup Profiles](#startup-profiles)
- [Build Tools](#build-tools)
  - [Gradle](#gradle)
  - [R8](#r8)
- [Tools](#tools)
  - [ADB](#adb)
- [Debugging](#debugging)
- [System Design](#system-design)

<hr/>  

## Internals
### Android
- [The internals of Android APK build process — Article](https://medium.com/androiddevnotes/the-internals-of-android-apk-build-process-article-5b68c385fb20)
- [Bytecode analysis for everyone!](https://youtu.be/6cYmdoeZ1OY)
- [Desugaring in Android](https://blog.mindorks.com/desugaring-in-android/)
- [Dalvik, ART, JIT, and AOT in Android](https://outcomeschool.com/blog/dalvik-art-jit-aot)
- [Updating Android UI from Worker Threads](https://github.com/Noddy20/UIThread-Android)
### Android View
- [Android Custom View Level 3 View Life-Cycle](https://proandroiddev.com/android-custom-view-level-3-81e767c8cc75)
### Jetpack Compose
- [Understanding Jetpack Compose — part 1](https://medium.com/androiddevelopers/understanding-jetpack-compose-part-1-of-2-ca316fe39050)
- [Understanding Jetpack Compose — part 2](https://medium.com/androiddevelopers/under-the-hood-of-jetpack-compose-part-2-of-2-37b2c20c6cdd)
### Kotlin
- [How to make kotlin compile 2x faster on a super large project?](https://www.droidcon.com/2024/08/11/how-to-make-kotlin-compile-2x-faster-on-a-super-large-project/)
- [Advanced Kotlin Flow Cheat sheet (for Android Engineer)](https://medium.com/@galou.minisini/advanced-kotlin-flow-cheat-sheet-for-android-engineer-cb8157d4f848)
- [inline, noinline, crossinline — What do they mean?](https://medium.com/android-news/inline-noinline-crossinline-what-do-they-mean-b13f48e113c2)
- [Exploring the Power of Kotlin Contracts for Better Code Quality](https://oguzhanaslann.medium.com/exploring-the-power-of-kotlin-contracts-for-better-code-quality-80bb279d7d2d)
### Popular Libraries
#### Coroutines
- [Coroutines Mastery: Tips, Best Practices, and Real-world Insights](https://www.droidcon.com/2024/08/30/coroutines-mastery-tips-best-practices-and-real-world-insights/)
#### ViewModel
- [How Android ViewModel works under the hood to survive to configuration change](https://proandroiddev.com/how-viewmodel-works-under-the-hood-52a4f1ff64cf)
- [How Android ViewModel works under the hood to survive to configuration change - 2](https://stackoverflow.com/questions/58903637/how-viewmodel-survives-configuration-change/58903803#58903803)

<hr/>

## Performance
#### Video
- [Unblocking The Main Thread: Solving ANRs and Frozen Frames](https://youtu.be/BSB7ZLNm9ac)
- [🔍 LeakCanary Masterclass with Pierre-Yves Ricau - Unraveling Android Memory Leaks 🐦 #LiveTechT](https://youtu.be/ZdZSGnJw3mY)
- [Perfetto Your App for Perfect Performance](https://www.droidcon.com/2024/08/30/perfetto-your-app-for-perfect-performance/)
- [Android Performance Patterns](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE)
#### Blog
- [Mastering Android App Performance: Analyzing Bottlenecks with Perfetto 🚦](https://blog.shreyaspatil.dev/mastering-android-app-performance-analyzing-bottlenecks-with-perfetto)
- [Weak Soft and Phantom references in Java and why they matter](https://medium.com/@ramtop/weak-soft-and-phantom-references-in-java-and-why-they-matter-c04bfc9dc792)
- [Android App Performance In a Nutshell](https://www.droidcon.com/2023/11/15/android-app-performance-in-a-nutshell/)
- [Using Java AspectJ tool to profile your Android Application performance](https://dashitesh.medium.com/android-method-profiler-tool-amp-using-aspectj-5c85af8ed599)
- [Top 10 Android Memory Leak Causes](https://medium.com/@dugguRK/top-10-android-memory-leak-causes-9cdd8cbd5489)
- [The real size of Android objects](https://dev.to/pyricau/the-real-size-of-android-objects-1i2e)
- [How we reduced our ANR by three times](https://medium.com/okcredit/how-we-reduced-our-anr-by-three-times-d9ae0b41ad94)
- [How I Fell in Kotlin’s RunBlocking Deadlock Trap, and How You Can Avoid It](https://medium.com/better-programming/how-i-fell-in-kotlins-runblocking-deadlock-trap-and-how-you-can-avoid-it-db9e7c4909f1)

### Baseline Profiles
- [Making apps blazing fast with Baseline Profiles](https://youtu.be/yJm5On5Gp4c)
- [Make your app faster with Baseline Profiles Perfetto and more - Rahul Ravikumar](https://youtu.be/7bLTmPpUIno)
- [Improve Your Android App Performance With Baseline Profiles](https://getstream.io/blog/android-baseline-profile/)

### Startup Profiles
- [Official Documentation](https://developer.android.com/topic/performance/baselineprofiles/dex-layout-optimizations)

<hr/>

## Build Tools
- [Creating Different Build Variants in Android](https://blog.mindorks.com/build-variants-in-android/)
### Gradle
### R8
- [What is R8 and how we enabled it](https://stefma.medium.com/what-is-r8-and-how-we-enabled-it-4f5764a7ff9c#:~:text=The%20R8%20compiler%20detects%20unused,also%20optimizes%20the%20source%20code.)
- [ProGuard — Everything You Need to Know](https://medium.com/@attilaptkai/proguard-everything-you-need-to-know-bb5ff9c04bcd)

<hr/>

## Tools
### ADB
- [What if ADB does not have to be that complicated?](https://youtu.be/auiGFhKBDAE)
- [PRACTICAL ADB USAGE TO ENHANCE YOUR LIFE! - Benjamin Kadel | Droidcon Italy 2023 Talk](https://youtu.be/KFnqoze9nZc)
 
## Debugging
- [DAAS: Debugging as a skill!](https://www.droidcon.com/2024/08/30/daas-debugging-as-a-skill/)


## System Design
- [Grokking the Mobile System Design interview](https://artem-goncharov.medium.com/grokking-the-mobile-system-design-interview-6a06fa94491b)
- [Mobile System Design Interviews (iOS and Android)](https://naxirmahmood.medium.com/mobile-system-design-interviews-ios-and-android-f5d360292c22)
- [An App Developer’s Guide to Mobile System Design Interviews](https://neelbakshi.medium.com/an-app-developers-guide-to-mobile-system-design-interviews-74cd552bd963)
- [Mobile System Design Exercise: Image Library](https://proandroiddev.com/mobile-system-design-exercise-image-library-83999eb0ad3c)

## How to Contribute

We welcome contributions from the community! Here are some ways you can contribute:

### Reporting Issues

If you encounter any issues or have suggestions for improvements, please open an issue on GitHub. Provide as much detail as possible to help us understand and address the problem.

### Suggesting New Resources

If you have come across valuable resources related to Android development that are not included in this repository, feel free to suggest them. You can do this by opening an issue or submitting a pull request with the details of the resource.

### Submitting Pull Requests

We encourage you to contribute to this repository by submitting pull requests. Here are the steps to follow:

1. Fork the repository.
2. Create a new branch for your contribution.
3. Make your changes and commit them with clear and descriptive commit messages.
4. Push your changes to your forked repository.
5. Open a pull request, providing a detailed description of your changes.

### Code of Conduct

Please note that we have a code of conduct in place to ensure a welcoming and inclusive environment for all contributors. We expect all contributors to adhere to this code of conduct. You can find the code of conduct [here](./CODE_OF_CONDUCT.md).
