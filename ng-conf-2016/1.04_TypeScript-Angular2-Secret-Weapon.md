# 1.04 TypeScript: Angular 2's Secret Weapon


### 講者：Dan Wahlin


#### Agenda:
* Types 型別
* Tooling
* Interfaces 介面
* Generics 泛型
* Future


### Types
* "If you [screw] up it'll tell you"
* 在編譯過程中，TSC 編譯器會幫你進行型別檢查，部分 IDE 透過整合，可以讓你在寫 code 的時候就發現錯誤，非 runtime。


### Key Tooling Support Features 主要工具支援特色
* Code Help / Intellisense - 程式碼自動完成（透過偵測，給你可能的選項）
* Refactoring - 重構（原本 Javascript 是鬆散型別語言所以很難重構）
* Peek / Go To - 提示 / 跳入到 reference 的程式碼位置
* Find References


### Interfaces 介面
備註1：這部分建議看影片，文字很難說明。（影片時間區段 8:38 ~ 12:33）


### Generics 泛型
* 影片中簡單介紹「泛型」的好處與用途，不過如果沒有相關的經驗可能看不懂
* 泛型並不是新的東西，在 java c# 都有，沒有經驗的人建議先看網路上的介紹
* TS 因為有了泛型，就可以減少使用 any 型別。

### Future
* 除了 es5 之外，也陸陸續續加入新功能到 TypeScript
* 例如現在已經可以使用 decorator 功能，這部分是屬於 es6 的規範
* 未來計畫加入 async/await ... 等等新功能
* 有興趣的人可以參考 TypeScript [未來開發計畫](https://github.com/Microsoft/TypeScript/wiki/Roadmap)
