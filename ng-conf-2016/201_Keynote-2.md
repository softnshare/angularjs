# <img src="http://www.ng-conf.org/images/newlogo.png" height="80"/> 2.01 Keynote 2



### 資源
[影片](https://www.youtube.com/watch?v=bSssb9AmiJU)｜[投影片](https://docs.google.com/presentation/d/1pqn5uhqg1km1AXR15qugtAYV-bnMtDl_HC1HnK9b1xQ/edit#slide=id.g12e00921d2_20_10)



### 摘要 - 前方的路(Road Ahead)

【離線編譯】
- 目前 Angular2 只需要45k左右，非常的小且漂亮

比較compiling
- Angular1 使用多態(Polymorphic) 由xhr(browser) > parser(browser) > dom(browser) > ng1(js)
- Angular2 使用單態(Monomorphic)
build 【template(file) > parser(node) > ast(node) > souce(js)】
source(browser) > ng2(js)

流程
- Offline compile > Inline modules > Tree-shake > Minify
- Offline compile：在compile的時候就會告訴你那邊有問題，不用等到程式run起來
- Inline modules：不像ng1是都掛在app底下，app、ngCore、ngCommon、ngCompiler是一致的
- Tree-shake：少了ngCompiler
- Minify：把app、ngCore、ngCommon最小化為一個munge

優點
- Request 次數少
- 壓縮過的size小
- 讀取時間短
- 比以前的ng1或是ng2都還要更小更漂亮(未來會更小?)
『Angular大膽的目標：10k』

【初步呈現Initial Rendering - Universal】
可運作於各種平台ASP.NET、node.js、Java、PHP()各種平台合作方式不同)

【進階素材Advanced Material】
- 除了昨天講過的素材Material component、我們正在建立Advanced Material 2提供使用，或是建立你自己的component libraries。
- Material core 有像是mobile、a11y、i18n、overlay...等等
- Advanced Material 2有像是：Google API、影像播放器video player、文字編輯器text-editor、自動表單生成automatic form generation、圖表生成chart、資料表生成data-table generation
- 我們希望製作高性能，且非常容易使用的工具，希望令你感到驚訝。

【無痛升級Effortless Upgrades】
- 你準備好angular 3了嗎？我們不想要製作angualr 3，因為了因為網頁平台的改變，我們需要保持這個框架可以被更新，所以我們不能只待在2.0。

- 更新對於某些人來說是很難的，但我們的support會被分散在許多版本中，你們仍然要面對比較舊版本的瀏覽器所產生的問題，如果使用者都是使用最新版本，你不就可以更好的利用自己的時間了嗎？所以，使用長青瀏覽器（evergreen browsers）是你比較好的選擇。
- 長青瀏覽器evergreen browsers：指的是自動升級到未來的版本，而不是從製造商的新版本發佈而被更新。
- 在ng2中的google相關app，我們會持續保持他們在最新的版本，我們會對很多app進行升級。
- Refactoring Tool：提供無痛升級，無須改寫ng2程式，你的內部程式將會被更新為最新版本！

Thank you！
