# Hex 作業

## CSS 切板任務

**遇到的問題**:  
試了很久不知道要怎麼把 span(中文的英文對照字)跟左方的 h2 垂直置中對齊?
試過 vertical-align 失敗了

**紀錄**:
第一版:3 小時  
看過老師的切版影片後  
第二版:盲寫 1.5 小時

第一版:  
第一版是用區塊一塊一塊往下寫的, 不是東西切不出來, 反而是花了比較多時間思考要把那些設定放在共通的標籤設定

第二版:  
有把一些常用的 margin/padding 獨立做 class 設定  
問題:什麼時候要在 div 裡面一起設定, 什麼時候直接去套用 .mb-2 之類的 class, 有點不知所措...感覺比較像是看當下的心情?

## FLEX 小節作業

**遇到的問題**: 如何把表格第一欄第二列開始的內容置中的同時又左邊切齊?

**細節問題**: 如果為了排版製造了很多 div 會不會不太好? 像是之前老師有說過 CSS 切版任務, 不會把 footer 的聯繫方式(FB, IG, Line)單獨放到一個 div, 因為這三個也是聯繫方式  
但在 Flex 排版的時候, 會需要用到 div 去做排版, 像是老師 Flex 影片把上面的 menu 去做兩個 div, 一個單純放 logo, 一個專門放 3 個 menu, 再去對兩個 div 做排版  
還是 Flex 的排版方式本身就會製造出很多 div 去做排版?

## FLEX 切版任務

**花費時間**: 4 小時

## RWD 切版任務

**花費時間**: 2 小時

**細節問題**:  
1.使用  
_,
_::before,
\*::after {  
 box-sizing: border-box;  
}

和在 body 內設  
body{
box-sizing: border-box;  
}  
的不同處在哪裡? (排版結果會不一樣, 但原因?)  
因為全部的東西也都放在 body 內不是嗎?

2.換圖: 用兩張圖去設計 hide & show 和使用 a 連結的 background 差在哪?  
主要是因為, 用 hide/show 都會下載兩張圖片  
如果用 a 的 background 去做換圖會去看裝置的解析度決定載哪一張而已?  
實測:  
a. 在 768px 以上, 只會下載 250 x 250  
b. 在 768px(含) 以下, 只會下載 150 x 150  
c. 如果在瀏覽器, 從 1000px 拉到 768px 以下  
就會發現, 一開始是載 250x250 沒錯, 不過到 768px 以下就會在下載 150x150 的圖  
(瀏覽器 F12-Network)
