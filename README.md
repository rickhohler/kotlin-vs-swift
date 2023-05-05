# Kotlin vs Swift Comparison

[Swift](swift/README.md) is a modern programming language created by Apple. Interopability with Objective-C is a primary feature of Swift supporting a transition from previously built MacOS and iOS apps.

JetBrains created the Kotlin programming language. [Kotlin](kotlin/README.md) is modern language designed to run on a Java Virtual Machine (JVM) and compiles natively. Java language interopabilty is support with Kotlin. Java developers now have a modern language to implement Android and server-side apps.

## In Common

| Concept                 | Kotlin        | Swift         |
| ----------------------- | ------------- | ------------- |
| Constants declaration | val | let | 
| Mutable declaration | var | var |
| Function declaration | fun | func |
| Initialization | constructor | init |
| Absence of a value  | null | nil |
| Return separator | : | -> |
| Any object | Any | AnyObject |
| Asserts that an expression is non-null | !!  | ! |


## Functions

### Swift

```swift
func calcSum(a: Int, b: Int) -> Int {
    return a + b        // return keyword is optional
}

func formatName(first: String, last: String) -> String {
    "\(first) \(last)"  // String Interpolation
}
```

[String Interpolation](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/stringsandcharacters#String-Interpolation)

### Kotlin

```kotlin
fun calcSum(a: Int, b: Int): Int {
    return a + b
}

fun formatName(first: String, last: String): String {
    return "$first $last"   // String Templates 
}
```

[String Templates](https://kotlinlang.org/docs/strings.html#string-templates)


