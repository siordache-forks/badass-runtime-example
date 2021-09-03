[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/beryx-gist/badass-runtime-example/blob/master/LICENSE)
[![Build Status](https://github.com/beryx-gist/badass-runtime-example/workflows/Gradle%20Build/badge.svg)](https://github.com/beryx-gist/badass-runtime-example/actions?query=workflow%3A%22Gradle+Build%22)


## Badass Runtime Plugin Example ##

A small application that shows how to use the [Badass Runtime Plugin](https://github.com/beryx/badass-runtime-plugin/).

### Usage
**Running with gradle:**
```
./gradlew run
```

The following text should appear on your screen:
```
LOG: Hello, non-modular java!
```


**Creating and executing a custom runtime image:**
```
./gradlew runtime
cd build/image/bin
./hello
```

The following text should appear on your screen:
```
LOG: Hello, non-modular java!
```
