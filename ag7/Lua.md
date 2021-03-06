Lua 是一種輕量小巧的腳本語言，用標準C語言編寫並以源代碼形式開放， 其設計目的是為了嵌入應用程序中，從而為應用程序提供靈活的擴展和定制功能。

Lua 是巴西里約熱內盧天主教大學（Pontifical Catholic University of Rio de Janeiro）裡的一個研究小組，由Roberto Ierusalimschy、Waldemar Celes 和Luiz Henrique de Figueiredo所組成並於1993年開發。

## Lua 特性

* **輕量級**
:它用標準C語言編寫並以源代碼形式開放，編譯後僅僅一百餘K，可以很方便的嵌入別的程序裡。
* **可擴展**
: Lua提供了非常易於使用的擴展接口和機制：由宿主語言\(通常是C或C++\)提供這些功能，Lua可以使用它們，就像是本來就內置的功能一樣。
* **其它特性**
:
* 支持面向過程\(procedure-oriented\)編程和函數式編程\(functional programming\)；
* 自動內存管理；只提供了一種通用類型的表（table），用它可以實現數組，哈希表，集合，對象；
* 語言內置模式匹配；閉包\(closure\)；函數也可以看做一個值；提供多線程（協同進程，並非操作系統所支持的線程）支持；
* 通過閉包和table可以很方便地支持面向對象編程所需要的一些關鍵機制，比如數據抽象，虛函數，繼承和重載等

## 關鍵詞

以下列出了Lua 的保留關鍵字。保留關鍵字不能作為常量或變量或其他用戶自定義標示符：

| and | break | do | else |
| :--- | :--- | :--- | :--- |
| elseif | end | false | for |
| function | if | in | local |
| nil | not | or | repeat |
| return | then | true | until |
| while | | | |

基本邏輯符號運算講解:[https://youtu.be/lFpWuZE2YN0](https://youtu.be/lFpWuZE2YN0)

雖然現在只學到一點點基本lua程式，相信以後會學到更多的東西，但是英文和數學真的還要再加強許多，不然面對一些基本的程式時，還要再花時間去查詢，以及「自學」真的很重要，程式這方面很多都要靠自己去尋找網路上的資料摸索，不然出社會面對的可不是還有很多時間讓你去學。

