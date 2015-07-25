[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Download](https://api.bintray.com/packages/wasabeef/maven/blurry/images/download.svg)](https://bintray.com/wasabeef/maven/blurry/_latestVersion)

![logo](art/blurry.png)

Demo
---

![Demo](art/blurry.gif)

How do I use it?
---

### Setup

##### Gradle
```groovy
dependencies {
    compile 'jp.wasabeef:blurry:0.0.1'
}
```

### Functions

**Overlay**
```java
Blurry.with(context).radius(25).sampling(2).onto(rootView);
```

**Into**
```java
Blurry.with(context).capture(view).into(imageView);
```

**Blur Options**
```java
Blurry.with(context)
  .radius(10)
  .sampling(8)
  .color(Color.argb(66, 255, 255, 0))
  .onto(rootView);
```

Requirements
--------------
Android 2.3+

Developed By
-------
Daichi Furiya (Wasabeef) - <dadadada.chop@gmail.com>

<a href="https://twitter.com/wasabeef_jp">
<img alt="Follow me on Twitter"
src="https://raw.githubusercontent.com/wasabeef/art/master/twitter.png" width="75"/>
</a>

License
-------

    Copyright 2015 Wasabeef

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
