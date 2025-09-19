# Iconix
[![](https://jitpack.io/v/danimahardhika/candybar-library.svg)](https://jitpack.io/#danimahardhika/candybar-library) [![Build Status](https://travis-ci.org/danimahardhika/candybar-library.svg?branch=master)](https://travis-ci.org/danimahardhika/candybar-library) [![CircleCI](https://circleci.com/gh/danimahardhika/candybar-library.svg?style=svg)](https://circleci.com/gh/danimahardhika/candybar-library) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/108f01d34ab2456b866c5700f03591a5)](https://www.codacy.com/app/danimahardhika/candybar-library?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=danimahardhika/candybar-library&amp;utm_campaign=Badge_Grade) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) 
<br>Android Icon Pack Material Dashboard
<p><a href='https://play.google.com/store/apps/details?id=cue.iconix'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' width="200"/></a></p>

# Gradle Dependency
The minimum API level supported by this library is API 19

Add JitPack repository to root ```build.gradle```
```Gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
Add the dependency
```Gradle
dependencies {
    implementation 'com.github.danimahardhika.candybar-library:core:3.5.0-b4'
}
```
Or use a snapshot
```Gradle
dependencies {
    implementation('com.github.danimahardhika.candybar-library:core:-SNAPSHOT') {
        changing = true
    }
}
```

# Documentations
Take a look inside [Wiki Site](https://github.com/danimahardhika/candybar-library/wiki)

# Previews
<img src="https://lh3.googleusercontent.com/K__o7yPPne2aDCTFcb_NdN_5rdITcMsLJr34YVgVcJCP1JNSjM3AQDEaFubTAEo8hg=w958-h937-rw?.jpg" width="215"/> <img src="https://lh3.googleusercontent.com/NgKBfmJSzrQFjcsb7lzVrdhJO7hHEPx4ycBap3m9kucyvIhyM_6WBmjFCTZYdu-D7mQ=w958-h937-rw?.jpg" width="215"/> <img src="https://lh3.googleusercontent.com/3Iw26epznHx5x_mdjXPllPyJwM6r_-b77twnH3N1WdawcaZxVMs-ZpsLo_uz0RkaiEwq=w958-h937-rw?.jpg" width="215"/> <img src="https://lh3.googleusercontent.com/5t5gVmIVlczla0OxQN1kdDi1ZIniAiG_etPdONz4oV_7XdXRjttHueuUlvbihComcqKl=w958-h937-rw?.jpg" width="215"/>
<img src="https://lh3.googleusercontent.com/9qmVssXaN4FILsjTGrr7cmCcfUnzFMZtwardF7drIlpnYmw0n7QRpkdLqamhSZu2aq4=w958-h937-rw?.jpg" width="215"/> <img src="https://lh3.googleusercontent.com/OkuTrPhKfsYqpuPV5WTp6qdtSrr1gl-KqvYnKzwRsJYEvh1ta-gbJHjUOXKpKpk48eA=w958-h937-rw?.jpg" width="215"/>

# Features
* License Checker
* Apply: 23 launchers
  * [List of Supported Launchers](https://github.com/danimahardhika/candybar-library/wiki/List-of-Supported-Launcher)
* Icon Picker: see all icons included with sections and search
* Icon Request
  * Regular Request: disabled
  * Premium Request: pay to request
* Cloud Based Wallpaper
  * Preview wallpaper
  * Apply wallpaper: inbuilt wallpaper crop
  * Download wallpaper
* Settings
  * Clear Cache
  * Switch to Dark Theme
  * Restore Purchases: restore premium request after reinstalling
* Frequently Asked Questions: with search
* About
* Donation
* Changelog: show changelog every update
* Muzei Live Wallpaper: disabled
* Localization: supports more than 10 languages

**NOTE:** This is just Icon Pack Dashboard, not Icon Pack template or Icon Pack tutorial. You need to add required XML for Icon Pack by yourself.

# Support Development
Support development by making donation through demo app at Google Play


# License
```
Copyright (c) 2014-2016 Dani Mahardhika

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
