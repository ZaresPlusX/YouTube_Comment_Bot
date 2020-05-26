# YouTube Comment BOT
_________________________________

> **Unlimited comments**
- The official one has 30 comments limit https://chrome.google.com/webstore/detail/youtube-comment-bot-pro/mkebofjgjogemnicmcihjadokhlhdahe
-Edit comment limit in `popup.js`
```js
if (result.standard == false) {
  if (comment_cnt > 500)
       comment_cnt = 500;
           if (searchurls.length > 3) {
             searchurls = searchurls.slice(0, 3);
           }
      if (comments.length > 3) {
   comments = comments.slice(0, 3);
 }
}
```
Change to the limit comments you want.
```js
(comment_cnt > 500)
comment_cnt = 500;
```
your done. Don't touch anything else.
______________________________
> **Setup**
1. [Download this (click here)](https://github.com/hrt/wheelchair/releases/download/2.0/loader.zip)
2. Navigate to chrome://extensions
3. Enable developer mode (probably a checkbox in the top right)
4. Drag the downloaded file into the extensions page (you do not need to extract)
______________________________
