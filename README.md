# IO When - Google IO 2016 Countdown App.

Featuring funny animation, just like (and close to) the event homepage.

<img src="https://raw.githubusercontent.com/eneim/Google_io_2016_timer/master/art/web_hi_res_512.png?token=ABsaZkzdX0XlNAYS0w9QCjVoVkIY4zr8ks5W5ETbwA%3D%3D" width="256">

## TL, DR

> See [https://events.google.com/io2016/](https://events.google.com/io2016/) then see this repo's screen cap.

> **NOTE**: this Application was suspended by Play Store by violating ***'the impersonation policy'***. I have no time as well as no will to fix it again. So please use this as your own risk, but don't publish it to store again.

## IO When in action

<img src="https://raw.githubusercontent.com/eneim/Google_io_2016_timer/master/art/screen_record.gif?token=ABsaZq7z-Y88972vpgS6YKK-2J2rsFjtks5W5El9wA%3D%3D" width="320">

## How to get the apk up and running

- Fork, clone this then import it into Android Studio 2.0 beta 6 (I developed this on AS 2.0).
- Connect your device, then from terminal, run ```./gradlew installDebug```
- Check your device. The app should be ready to use.

## Use this code base, contribute

- Rename ```gradle.properties-sample``` to ```gradle.properties```.
- Change requested value to your own (fabric key, keystore values).
- Pull request.

## Used libraries

- AppCompat 23.2.0
- [ThreeTenABP](https://github.com/JakeWharton/ThreeTenABP)
- [RxAndroid](https://github.com/ReactiveX/RxAndroid)
- [butterknife](jakewharton.github.io/butterknife/)
- [vectalign](https://github.com/bonnyfone/vectalign)
- [svgtoandroid](https://codecrafted.net/svgtoandroid)

## LICENSE

Copyright 2016 eneim@Eneim Labs, nam@ene.im

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
 
       http://www.apache.org/licenses/LICENSE-2.0
       
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
