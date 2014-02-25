
About
---------

**RenderScriptPlayground** is an exemplary Android app showing how to use RenderScript with Android Studio and Gradle. Application is using RenderScript support library so it should works with Android Froyo (2.2). 
Getting Started
------------

#### 1. Clone project
```
git clone https://github.com/mrmike/RenderScriptPlayground.git
```

#### 2. Define environmental variables
```
~$ export ANDROID_HOME=path/to/android/sdk
~$ export ANDROID_NDK_HOME=path/to/android/ndk
```

If you do not want to use env variables you can always create local.properties file in project root folder.
```
// local.properties
sdk.dir=path/to/android/sdk
ndk.dir=path/to/android/ndk
```

### 3. Bulding project
```
~$ ./gradlew assemble
```

### 4. Installing app
```
~$ ./gradlew installArmDebug
```

Example
------------

![Image](./rs_blur_example.png?raw=true)![Image](./rs_mono_example.png?raw=true)

Photo: http://www.flickr.com/photos/29468339@N02/4542603519

License
=======

    Copyright 2014 Michał Moczulski

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.