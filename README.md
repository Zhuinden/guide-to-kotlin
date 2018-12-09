# Guide to Kotlin

This tutorial has what I think is all the information you need if all you know is Java, but you want to learn Kotlin.

Please note that the resources are in the [**wiki page**](https://github.com/Zhuinden/guide-to-kotlin/wiki).

# Table of Content

## Syntax Quirks

- inverted argument order, `void` vs `Unit`, `Object` vs `Any?`

- semi-colons (or lack thereof)

- `fun`, `enum class`, `interface`s with `val`, `var` and `fun`

- `for` loops (`in` ranges, `until`)

- `object` for singleton

- statics via `companion object`, `const val`

- backticks for reserved keywords (`Mockito.\`when\``, `$`) and import aliases

- visibility in Kotlin (public by default, `private`, `protected`, `internal`)

- `is` instead of `instanceof`, `as` and `as?` for casting

- creating anonymous implementations for classes/interfaces

- there is no `condition ? true : false` ternary operator

- single-line functions can be used with `= ...` instead of `{ return ... }`

## Basic Kotlin Features

- typed nullability

- smart casting (and mutable vars gotcha)

- lateinit vars

- properties, backing fields (`set(value) { field = value ... }`, difference between `val x = ""` and `val x: String get() = ""`

- string interpolation and """multiline escaped ${strings}"""

- data classes

- null safety operators: safe-call (`?.`) and elvis (`?:`)

- `when` keyword (and complex conditions, such as ranges)

- control statement as expression (assignment of `when`, `return`, ...)

- generics (`<T: Blah>`, `in/out`, and star projection `<*>`)

## The Cool Stuff

- lambda types, trailing lambdas

- `typealias`

- lambdas with receivers

- extension functions

- standard library functions - scoping functions: `apply`, `let`, `also`, `run`, `with`

- standard library functions - more utility functions: `takeIf`, `takeUnless`

- revisited: single-line returns with `=` instead of `{ return ... }`

- `tailrec` keyword

- `inline` functions (`crossinline`, `noinline`)

- a glance at [the Collections API](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html#functions) 

- inline functions and `<reified T>`
  
- `sealed` classes

- `infix` keyword

- tuples (`to`) and destructuring

## The Tricky Stuff

- extension operators (`componentN`)

- property delegates (and built-in ones: `lazy`, `observable`/`vetoable`, `by map` for configurations via `Map<String, Any?>`)

- delegation by class

- JVM annotations: `@JvmOverloads`, `@JvmField`, `@JvmSuppressWildcards`, `@get:` and `@set:` and `@field:`

## Android-Specific Stuff

- synthetic view accessors with kotlin android extensions

- `@Parcelize data class` with experimental kotlin android extensions

## Stuff that needs to be more fleshed out in this tutorial

- coroutines

- channels?

- @DslMarker?

- multi-platform things: `expect` and `actual`?

# Feel like donating?

If you feel like this project helped you so much that you would have wanted to pay for it or something, well technically I won't get in your way. Here are two options if you want to go along with it.

## PayPal 

* **[Donate €4](https://www.paypal.me/Zhuinden/4)**: This sum lets me buy tibetan soup for lunch. If you ever visit Hungary, you should try it too, I know a really good place.
* **[Donate €8](https://www.paypal.me/Zhuinden/8)**: This is double the amount one above, and it's also yet another power of 2.
* **[Donate €12](https://www.paypal.me/Zhuinden/12)**: I think I've just ruined that sequence, but at least built another one.
* **[Donate €16](https://www.paypal.me/Zhuinden/16)**: I've seen projects add a $2799 tier, but if I get too much money, that'd result in more paperwork. So this is fine as the highest tier.

## Ethereum

I'm actually not sure how Ethereum works, but I do have a wallet thanks to Reddit. I just know it's possible to accept donations there, so I may as well add it here.

```
0x9cA7a7e0492Ba58bb52fb3B04a4E3C3864C20DBB |
```


# License

    Copyright 2018 Gabor Varadi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
