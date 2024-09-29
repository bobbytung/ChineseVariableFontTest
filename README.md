# ChineseVariableFontTest
Test Chinese Variable Font on browsers

- [文鼎晶熙黑測試頁面](https://bobbytung.github.io/ChineseVariableFontTest/index.html)
- [思源黑體VF測試頁面](https://bobbytung.github.io/ChineseVariableFontTest/index_SHsans.html)
- [思源宋體VF測試頁面](https://bobbytung.github.io/ChineseVariableFontTest/index_SHserif.html)
- [Noto Serif測試頁面](https://bobbytung.github.io/ChineseVariableFontTest/index_notoserif.html)
- [Noto Sans測試頁面](https://bobbytung.github.io/ChineseVariableFontTest/index_notosans.html)
- [自行測試頁面](https://bobbytung.github.io/ChineseVariableFontTest/index_test.html)

（2022/11/6更新，以上頁面思源體指定Local Font，但Safari 16.1 [macOS Ventura 13.0]起可能因為隱私問題，不會調用Local Font，所以請用其他瀏覽器測試。）

## Browser support for CSS font-variation-settings property

- Safari (11.0.2（13604.4.7.1.3）on macOS High Sierra 10.13.2（17C88）)

預設開啟，同時font-weight直接控制wght值，也就是直接使用font-weight就可以控制variable font的字重。

- Chrome（63.0.3239.84 mac 64bit）

正式版本的實驗性功能，需要透過chrome://flags 啟用：

    Experimental Web Platform features
    (#enable-experimental-web-platform-features)

- Firefox （57.0.1 mac 64bit）

正式版本的實驗性功能，需要透過about:config 啟用：

    layout.css.font-variations.enabled
    gfx.downloadable_fonts.keep_variation_tables
    gfx.downloadable_fonts.otl_validation


## Sample Varible Font

文鼎晶熙黑 is provided by Arphic, under EULA @ http://www.arphic.com.tw/zh-tw/home/about#view_post/181
