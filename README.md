## [Click this link to go to the Wiki page](https://github.com/Zhuinden/guide-to-kotlin/wiki)

# Guide to Kotlin

This tutorial assumes that all you know is Java, but you want to learn Kotlin.

Please note that the resources are in the [**wiki page**](https://github.com/Zhuinden/guide-to-kotlin/wiki).

# Additional resources

A few things that are worth watching to know more about Kotlin.

## More resources to read

- By me: [Odd things to look out for when converting code to Kotlin](https://android.jlelse.eu/odd-things-to-look-out-for-when-converting-code-to-kotlin-a00b6239828c)

- By me: [Code clean-up with Kotlin](https://proandroiddev.com/code-clean-up-with-kotlin-19ee1c8c0719)

- By me (newer article!): [An opinionated guide on how to make your Kotlin code fun to read and joy to work with](https://proandroiddev.com/an-opinionated-guide-on-how-to-make-your-kotlin-code-fun-to-read-and-joy-to-work-with-caa3a4036f9e)

- Android KTX source code: [Github snapshot](https://github.com/android/android-ktx/tree/136ba4cdb3b6ece7470cbddeaf6a168021a69a30/src/main/java/androidx/core) or [AOSP (actively developed)](https://android.googlesource.com/platform/frameworks/support/+/master/core/ktx/src/main/java/androidx/core)

## More resources to watch

- [Jake Wharton: Instrumentation Testing Robots](https://academy.realm.io/posts/kau-jake-wharton-testing-robots/)

- [How to Kotlin - from the Lead Kotlin Language Designer (Google I/O '18)](https://www.youtube.com/watch?v=6P20npkvcb8)

- [Droidcon NYC 2018: Advanced Kotlin](https://www.youtube.com/watch?v=ECglKui0hpc)

- [Google I/O 2017 - Jake Wharton / Christina Lee: Life is Great and Everything will be OK: Kotlin is here](https://www.youtube.com/watch?v=fPzxfeDJDzY)

## Style-guide and reference for common mistakes to avoid 

https://www.reddit.com/r/androiddev/comments/77sl1c/devs_who_review_kotlin_regularly_what_are_things/dorsk3i/

# Table of Content

## Major Syntax Differences

- [inverted argument order, no semi-colons, void vs Unit, Object vs Any?, fun](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#inverted-argument-order-no-semi-colons-void-vs-unit-object-vs-any-fun)

- [interfaces with val, var and fun](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#interfaces-with-val-var-and-fun)

- [constructors, inheritance](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#constructors-inheritance)

- [lateinit vars](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#lateinit-vars)

- [enum class](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#enum-class)

- [annotation class](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#annotation-class)

- [final by default vs open](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#final-by-default-vs-open)

- [for loops (in ranges, until)](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#for-loops-in-ranges-until)

- [object for singleton](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#object-for-singleton)

- [statics via companion object, const val](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#statics-via-companion-object-const-val)

- [visibility in Kotlin (public by default, private, protected, internal)](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#visibility-in-kotlin-public-by-default-private-protected-internal)

- [static nested class in Java vs inner class in Kotlin](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#static-nested-class-in-java-vs-inner-class-in-kotlin)

- [backticks for reserved keywords (Mockito.when, $) and import aliases](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#backticks-for-reserved-keywords-mockitowhen--and-import-aliases)

- [is instead of instanceof, as and as? for casting](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#is-instead-of-instanceof-as-and-as-for-casting)

- [creating anonymous implementations for classes/interfaces](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#creating-anonymous-implementations-for-classesinterfaces)

- [there is no condition ? true : false ternary operator](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#there-is-no-condition--true--false-ternary-operator)

- [arrayOf and arrayOfNulls and listOf and mutableListOf and linkedMapOf](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#arrayof-and-arrayofnulls-and-listof-and-mutablelistof-and-linkedmapof)

- [array literals in annotations (for vararg parameters)](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#array-literal-in-annotations-even-for-single-argument-vararg-parameter)

- [operator conventions (get() vs [], .equals() vs ==)](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#operator-conventions-get-vs--equals-vs-)

- [there are no checked exceptions, try-with-resources as .use {}](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#there-are-no-checked-exceptions-use)

- [@Volatile and synchronized](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#volatile-is-replaced-with-volatile)

- [multiple generic bounds](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Major-Syntax-Differences#multiple-generic-bounds)

## Basic Kotlin Features

- [typed nullability, and null-safety operators (?., ?:)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#typed-nullability-and-null-safety-operators--)

- [smart casting (and mutable vars gotcha)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#smart-casting-and-mutable-vars-gotcha)

- [lateinit vars](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#lateinit-vars)

- [properties, backing fields](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#properties-backing-fields)

- [string interpolation and """multiline escaped ${strings}"""](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#string-interpolation-and-multiline-escaped-strings)

- [data classes](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#data-classes)

- [`when` keyword (and complex conditions, such as ranges)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#when-keyword)

- [control statement as expression (assignment of `when`, `return`, ...)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#control-statement-as-expression-assignment-of-when-return)

- [named arguments, default arguments](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#named-arguments-default-arguments)

- [vararg and the * spread operator](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#vararg-and-the--spread-operator)

- [interfaces and default implementation](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#interfaces-and-default-implementation)

- [generics (`<T: Blah>`, `in/out`, and star projection `<*>`)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#generics-t-blah-inout-and-star-projection-)

## The Cool Stuff

- [lambda types, trailing lambdas](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#lambda-types-trailing-lambdas)

- [method reference](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#method-reference)

- [`typealias`](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#typealias)

- [lambdas with receivers](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#lambdas-with-receivers)

- [extension functions, extension properties](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#extension-functions-extension-properties)

- [standard library functions - scoping functions: `apply`, `let`, `also`, `run`, `with`](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#standard-library-functions---scoping-functions-apply-let-also-run-with)

- [standard library functions - more utility functions: `takeIf`, `takeUnless`](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#standard-library-functions---more-utility-functions-takeif-takeunless)

- [`tailrec` keyword](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#tailrec-keyword)

- [`inline` functions (`crossinline`, `noinline`)](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#inline-functions-crossinline-noinline)

- *[a glance at the Collections API](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#a-glance-at-the-collections-api) ([see API here](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html#functions))

- [`inline fun <reified T>`](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#inline-fun-reified-t)
  
- [`sealed` classes](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#sealed-classes)

- [`infix` keyword](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#infix-keyword)

- [tuples (`to`) and destructuring](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#infix-keyword)

## The Tricky Stuff

- [*extension operators (`componentN`)](https://github.com/Zhuinden/guide-to-kotlin/wiki/4.\)-The-Tricky-Stuff#extension-operators-componentn)

- [*property delegates (and built-in ones: `lazy`, `observable`/`vetoable`, `by map` for configurations via `Map<String, Any?>`)](https://github.com/Zhuinden/guide-to-kotlin/wiki/4.\)-The-Tricky-Stuff#property-delegates-and-built-in-ones-lazy-observablevetoable-by-map-for-configurations-via-mapstring-any)

- [delegation by class](https://github.com/Zhuinden/guide-to-kotlin/wiki/4.\)-The-Tricky-Stuff#delegation-by-class)

- [*JVM annotations: `@JvmOverloads`, `@JvmField`, `@JvmSuppressWildcards`, `@get:` and `@set:` and `@field:`](https://github.com/Zhuinden/guide-to-kotlin/wiki/4.\)-The-Tricky-Stuff#jvm-annotations-jvmoverloads-jvmfield-jvmstatic-jvmsuppresswildcards-get-and-set-and-field)

## Android-Specific Stuff

- [~~synthetic view accessors with kotlin android extensions~~ (deprecated)](https://github.com/Zhuinden/guide-to-kotlin/wiki/5.\)-Android-Specific-Stuff#synthetic-view-accessors-with-kotlin-android-extensions)

- [`@Parcelize data class` with experimental kotlin android extensions](https://github.com/Zhuinden/guide-to-kotlin/wiki/5.\)-Android-Specific-Stuff#parcelize-data-class-with-experimental-kotlin-android-extensions)

# Stuff that is currently not covered, and should eventually be added in this tutorial

- Coroutines, coroutines on Android, `suspend fun`

- Channels: LinkedListChannel, BroadcastChannel

- @DslMarker

- multi-platform things: `expect` and `actual`

- contracts

# License

    Copyright 2018-2020 Gabor Varadi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
