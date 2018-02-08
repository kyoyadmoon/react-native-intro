# react-native-intro
## React Native

Build native mobile apps using JavaScript and React

2015 release

- iOS
- Android
- Apple TV
- Android TV



##　移動應用方案

### Web 

- RWD
- Single Page Application 單頁式應用 (React, Vue, Angular...)

### Hybrid (Native App with Webview)

- PhoneGap
- Cordova
- Ionic

### CrossPlatform-Native

選擇一種語言來作為開發語言，編寫應用程式中主要的商業邏輯（和平台無關的邏輯），和平台有關的部分，再透過此抽象層呼叫調用已經封裝好的原生元件和 API。

- React Native
- Weex
- NativeScript
- Xamarin (C#)



![](https://s3.amazonaws.com/media-p.slid.es/uploads/40413/images/2912262/1171077-75412d65af198cf5.png)

### Native

- 完全原生
- 每個平台都獨立開發













## React Native 特點

- 開源
- 跨平台
- 接近原生的體驗
- **文件、學習資源完整**
- **生態資源**
- 開發及除錯工具整合完整
- 與 Web 開發流程非常相似 (JavaScript, JSX, 類CSS樣式, flexbox )
- HMR 提高開發速度
- 模組化、重用性　提高程式碼維護容易度
- 有優化和擴充的彈性
- Hot Deploy，不用審查提交就更新上架的 App









## 該選擇什麼專案初始化方式

### react-native-cli

需要原生專案環境設定 (需要有macOS才能開發 iOS)

對原生有完全的控制權

### Expo

整合了常用套件/功能的套餐，但是不能自己加點

自動打包

[`Snack`](https://snack.expo.io/)

- 使用手機下載 Expo App 就能開發 ( windows, linux 開發 iOS )
- 不會有原生專案，無法編寫 Native Code 和增加 Native module
- 不能把 app assets 打包成靜態檔案
- 不支援部份的 API Level
- 最終產生的 App 檔案較大
- 所有的程式碼都會先存放一份在 Expo server

back to react-native [Detaching](https://docs.expo.io/versions/latest/guides/detach.html)

### CRNA

- 體驗用的 playground，無法編寫 Native Code 和增加 Native module
- 簡化版的 Expo
- 不需要 iOS 和 Android 的編譯環境
- 仍然需要 node.js
- 創建最快速

back to react-native [Eject](https://github.com/react-community/create-react-native-app/blob/master/EJECTING.md)



