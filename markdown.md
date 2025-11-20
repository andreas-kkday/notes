1. 小章協理會開 api 給 app 另外打訊息到聊天室, 訊息格式 markdown。但是, 兩端訊息顯示不一樣, 像是一端顯示無回應, 一端顯示未接來電。要怎麼處理？
   格式像這樣嗎？
   ```
   {
    "uNo" : "對應的 markdown 內容",
    "tNo" : "對應的 markdown 內容"
   }
   ```

   Web 的話他們要怎麼把訊息 strip 成純文字。

   ```
   {
    "uNo" : {
        "markdown": "markdown...",
        "text" :"純文字 for web"
    }
    "tNo" : {
        "markdown": "markdown...",
        "text" :"純文字 for web"
    }
   }
   ```


<div style="display: flex; align-items: center; gap: 20px; background-color: lightgray; border-radius: 10px; padding: 10px;">
    <div style="flex-shrink: 0;">
        <img src="https://picsum.photos/24/24" alt="Placeholder Image" style="width: 24px; height: 24px; display: block;">
    </div>
    <div style="flex-shrink: 0;color:blue">
    未接來電
    </div>
</div>

<br>

# 問了 Gemini, markdown 沒有什麼垂直置中的語法, 還是用表格？還是有人可以幫忙寫 HTML ？

<br><br>
1.  關權 API, 開單給客服系統 (為什麼不是求才工程去開？？還是客服自己開？？？) 抱怨流程 使用者->客服->App??->求才工程->客服系統