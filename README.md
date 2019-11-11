# Facebook 分享連結產生器

設定連結、主題標籤和引文，Facebook 分享連結產生器就可以快速產生分享連結，讓你的用戶一鍵輕鬆分享貼文！

[Facebook 分享連結產生器]()

[2019 八月中之後，Facebook 拿掉了 Messenger 聊天機器人原生的分享按鈕](https://developers.facebook.com/docs/messenger-platform/send-messages/buttons#share)，因此目前 Chatfuel 和 ManyChat 上已經無法再使用分享按鈕功能，但還好 Facebook 有提供[「分享」對話方塊](https://developers.facebook.com/docs/sharing/reference/share-dialog/) 功能，在網址後加入參數，就可以簡單分享貼文到用戶的的動態時報。

做法主要有兩種：

- 傳統做法 sharer.php，較簡單，本專案採用此做法。  
  https://www.facebook.com/sharer/sharer.php 網址後加入參數。
  - u
  - hashtag
  - quote
- [使用 Facebook 應用程式](https://developers.facebook.com/docs/sharing/reference/share-dialog/)，可以額外設定 redirect_uri，用戶點擊分享按鈕後會重新導向此網址。
  https://www.facebook.com/dialog/share 網址後加入參數。

## Screenshot

![Screenshot]()
![Share-post-display]()
