關於Sublime text 3的使用
==============================

網路上已經有很多高手做的整理大家可以去看，都講得很詳細，例如：[保哥](http://blog.miniasp.com/post/2014/01/06/Useful-tool-Sublime-Text-3-Quick-Start.aspx)，[Chris Sevilleja](https://scotch.io/bar-talk/best-of-sublime-text-3-features-plugins-and-settings)...等等~

###:one: 基本必備安裝：
1. [Pakage control](https://packagecontrol.io/installation)
2. [Nodejs](https://nodejs.org/en/)，需順便安裝npm

###:thumbsup: 建議要裝的Package：  
1. **Alignment:**  自動對齊；快捷鍵`ctrl+ alt+ a`  
2. **AutoFileName:**  自動路徑提示  
3. **Bracket Highlighter:**  提示相對應的括弧  
4. **ChineseLoremIpsum:**  自動產出中文(切換`ctlorem/cslorem`)，`clorem + alt + c`    
5. **ColorPicker:**  跳出面板選顏色，`ctrl+ shift+ c`  
6. **ConvertToUTF:**  可顯示中文、韓文、日文；因為快捷鍵與ColorPicker衝突，所以要設定快捷鍵為`ctrl+ alt+ shift+ c`；另外，可將原本預設為簡體字改為繁體  
7. **Emmet:**  輸入code快捷鍵  
8. **HTML-CSS-JS-Pretiffy:**  存檔自動排版html, css, js；要先確認安裝nodejs完畢後，進入此套件的`Set 'node' Path`將"`format_on_save": false,`改成`"format_on_save": true,`；之後確認"node_path"內的路徑是否正確  
9. **jQuery:**  提示jQuery語法  
10. **SideBarEnhancements:**  提升邊攔作用  
11. **SublimeCodeIntel:**  提示諸多語言提示  
12. **SublimeLinter:**  幫你檢查code  
13. **SublimeLinter-jshint:**  幫你檢查javascript；需安裝`npm install -g jshint`  
14. **SublimeLinter-csslint:**  幫你檢查css；需安裝`npm install -g csslint`  

###:two: sublime基本操作：
1. **存檔:**  `ctrl+ s`
2. **註解:**  `ctrl+ /`
3. **Undo:** `ctrl+ z`
4. **Redo** `ctrl+ shift+ z`

###:three: sublime要會用的好功能：
1. **自動產出文字**  `lorem+ tab`，`lorem10+ tab`(10個字就好)  
2. **Multiple Selections:**  同時編輯多個地方；`ctrl+ d`或是`ctrl+ click`  
3. **Find:**  找出有關鍵字，但僅只本檔案；`ctrl+ f`
3. **Find in files:**  自動找出有關鍵字的檔案(邊欄內的所有檔案)；`ctrl+ shift+ f`  
4. **Go to anything:**  `ctrl+ p`  