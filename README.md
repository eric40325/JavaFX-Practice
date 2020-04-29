# Assignment 7

# 說明

請實作助教提供的範例程式。

這次請用javafx的canvas實作~

# 程式流程簡單介紹

這是一個GUI和\(一點點\)物件導向 的簡單練習。

按下上下左右，圖片會開始”順暢的”移動。

用滑鼠點擊人物，人物右方會產生文字。

# 程式碼微說明

所有的遊戲物件都在GameManager這個class裡儲存著，而GameManager也管理一些遊戲的事件，像是方向鍵被按下時的行為，或是滑鼠點擊的行為等等。

而Controller則是負責將觸發事件傳給GameManager，讓GameManager去做相對應的處理。

遊戲物件的基本元件是GameObject，它包含了遊戲物件所有的基本功能和屬性，像是位置，移動的函式等等。

遊戲的物件都繼承GameObject\(在這個程式中只有Player，但未來可能會有enemy或是其他的遊戲物件等等\)。

