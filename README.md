# **Table of Contents**

* [Nomenclature](#nomenclature)
    * [Packages](#packages)

# **Nomenclature**
On the whole, naming should follow Java standards, as Kotlin is a JVM-compatible language.

## **Packages**
Package names are similar to Java: all lower-case, multiple words concatenated together, without hypens or underscores:<br/>
BAD:<br/>
`vn.ViettelPay.network`<br/>
GOOD:<br/>
`vn.viettelpay.network`<br/>

## **Classes & Interfaces**
Written in UpperCamelCase. For example BaseCallAdapter.

## **Methods**
Written in lowerCamelCase. For example setValue.

## **Fields**
Generally, written in lowerCamelCase. Fields should not be named with Hungarian notation, as Hungarian notation is erroneously thought to be recommended by Google.<br/>
Example field names:<br/>
```kotlin
class MyClass {
    var publicField: Int = 0
    val person = Person()
    private var privateField: Int?
}
```
Constant values in the companion object should be written in uppercase, with an underscore separating words:
```kotlin
companion object {
  const val THE_ANSWER = 42
}
```

## **Variables & Parameters**

