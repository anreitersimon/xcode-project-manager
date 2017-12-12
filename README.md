# Xcode Project Manager

A macOS app to manage your modular Xcode projects.

<a href="https://swift.org/package-manager">
<img src="https://img.shields.io/badge/spm-compatible-brightgreen.svg?style=flat" alt="Swift Package Manager"/>
</a>
<a href="https://twitter.com/xcodedotswift">
  <img src="https://img.shields.io/badge/contact-@xcodedotswift-blue.svg?style=flat" alt="Twitter: @xcodedotswift" />
</a>
<a href="https://github.com/xcodeswift/xcode-project-manager/releases">
  <img src="https://img.shields.io/github/release/xcodeswift/xcode-project-manager.svg"/>
</a>
<a href="https://opensource.org/licenses/MIT">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License" />
</a>
<a href="http://xcodeswift.herokuapp.com/">
  <img src="https://xcodeswift.herokuapp.com/badge.svg">
</a>

## Continuous Integration ✅

- **Master:** [![Build Status](https://travis-ci.org/xcodeswift/xcode-project-manager.svg?branch=master)](https://travis-ci.org/xcodeswift/xcode-project-manager)

## Motivation 💅
Maintaining a modular Xcode project is very cumbersome. Modules projects share many things besides the build settings that cannot be extracted into xcconfig files *(e.g. targets or schemes)*. As a result having consistency across all the modules and automate the creation of them is something that cannot be done with Xcode.

Xcode Project Manager aims to facilitate this work. It provides an interface to define your projects *(using [XcodeGen](https://github.com/yonaskolb/XcodeGen) underneath)*. It removes the need to include Xcode projects in the git repositories and facilitates the creation of them whenever they are needed.


## Contribute 👨‍👩‍👧

1. Git clone `git clone git@github.com:xcodeswift/xcode-project-manager.git`.
2. Run `script/bootstrap`.
3. Open `XcodePM.xcworkspace`.


## References 📚

- [PathKit](https://github.com/kylef/PathKit)
- [Xcode Project File Format](http://www.monobjc.net/xcode-project-file-format.html)
- [xproj](https://github.com/xcodeswift/xcproj)
- [XcodeGen](https://github.com/yonaskolb/xcodegen)


## License

```
MIT License

Copyright (c) 2017 swift-code

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
