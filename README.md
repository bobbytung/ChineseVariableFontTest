# ChineseVariableFontTest
Testcase for Chinese Variable Font on browsers (With Arphic JingXiHei VF)

## Browser support for CSS font-variation-settings property

- Safari (11.0.2（13604.4.7.1.3）on macOS High Sierra 10.13.2（17C88）)

預設開啟，同時font-weight直接控制wght值，也就是直接使用font-weight就可以控制variable font的字重。

- Chrome（63.0.3239.84 mac 64bit）

正式版本的實驗性功能，需要透過chrome://flags 啟用：

```Experimental Web Platform features
(#enable-experimental-web-platform-features)```

- Firefox （57.0.1 mac 64bit）

正式版本的實驗性功能，需要透過about:config 啟用：

```layout.css.font-variations.enabled
gfx.downloadable_fonts.keep_variation_tables
gfx.downloadable_fonts.otl_validation```

Varible Font is provided by Arphic, EULA @ http://www.arphic.com.tw/zh-tw/home/about#view_post/181
