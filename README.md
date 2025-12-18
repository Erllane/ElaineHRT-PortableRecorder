# ElaineHRT-PortableRecorder

An opensourced portable android app of HRT recorder for trans, followed by project [Oyama-s-HRT-Tracker](https://github.com/SmirnovaOyama/Oyama-s-HRT-Tracker). The idea of enrolling it into Android environment came from my need to record but failed in opening the website by google chrome browser, and thus failed in sending it to desktop app in Android. However，modifying React/TypeScript codes to Android Native (especially Kotlin) may cost too much, this is a compromise.

HRT记录器的安卓便携版本, 原项目见[Oyama-s-HRT-Tracker](https://github.com/SmirnovaOyama/Oyama-s-HRT-Tracker)。启动这个项目的初衷是希望其在便携端的安卓生态下也能够正常使用, 本人在安卓端的Chrome浏览器无法正确打开该网站、且发送到桌面失败促成了这个app的落地。将React/TypeScript框架语言代码移植到原生安卓(尤其是Kotlin)应该是一个大工程, 所以这也是一个折衷的选择了。

---

## User Definitions 用户自定义

- **Change target websites**: Forehead project is able to be deployed on ones private sites, thus custom your own site to this app is feasible. Open `app/src/main/java/com/elainehrt/app/MainActivity.kt` and modify(default: [website](https://hrt.misaka23323.com))

  **更改目标网址** 前置项目是允许用户将其部署在私人网站上的，所以在这里自定义app中的目标网站也是完全可行的。打开 `app/src/main/java/com/elainehrt/app/MainActivity.kt` 修改 (默认:[网址](https://hrt.misaka23323.com))
  ```
  webView.loadUrl("https://yourwebsite.com")
  ```


- **Change App Icons**: Use Image Asset Tools in Android Studio to custom your app-icons in your favour.

  **修改图标**: 用Android Studio内置的Image Asset工具自定义你喜欢的图标(反正是一个开源的简单Webview项目).

---
  
## Ending 结语

  Wish mw happy! Back atcha! ( > v < )

  祝我开心! 你也一样! ( > v < )
