# OCR提取的文字内容

## 终端命令
```bash
curl -X POST https://hook.us2.make.com/pribs08hatx34qxzra69pgqk10ht9suw -H "Content-Type: application/json" -d '{
"destination": "Dxxxxxxxxxxxxxxxxxx",
"events": [
  {
    "type": "message",
    "message": {
      "type": "text",
      "id": "1716352325123",
      "text": "https://www.youtube.com/watch?v=g2_RiC25gCo"
    },
    "webhookEventId": "01F274A000000000000000000",
    "deliveryContext": {
      "isRedelivery": false
    },
    "timestamp": 1716352325123,
    "source": {
      "type": "user",
      "userId": "0yyyyyyyyyyyyyyyyyy"
    },
    "replyToken": "dummyReplyTokenabc123xyz",
    "mode": "active"
  }
]
}'
```

## 中文说明文档

1. Apify是一個類似市場的平台，提供超過450個預建的網路爬蟲（actors），用於網路資料擷取與自動化。

2. Actor基本上是預先寫好的腳本，可以傳送請求來執行特定任務，像是爬取TikTok影片、LinkedIn職缺、Google地圖商家資訊等。

3. 使用者可以根據需求來選擇不同的Actor來作，也可以直接點選想要爬取的網站，點選等就能直接使用。

4. 介紹了如何選擇Apify的運營與折扣價（30 Note Herk）來節省成本，並獲得30%的折扣。

5. 造作流程包括個人步驟：允許送信來獲取資料，接著他獲得爬取器來爬取想要的結果。

6. 示範如何Google地圖爬取餐廳的資訊資料，並在控制台查看爬取結果與項目，包括地址、網站、電話等資訊。

7. 進一步示範如何運營頻道、分析下載和保存的數據（例如比較的頻道系列）和結果。

8. 配置界面允許用戶自由設定想要爬取的內容，並可加入額外設定如產品或影片等爬取適當定條件。

9. 透過Actor制網，使用"run actor"來歷動爬蟲，並用"get last run data get items"來取得爬取結果。

10. 示範如何用HTTP請求（POST）來獲得JSON格式的爬取結果，獲得詳細讀取爬取ID。

11. 整個GET請求，重覆並收集所有獲取的資料數量（如25個或50個）。

12. 說明同步異性同步執行方式的差異，推薦使用先獲取結果，來確保準資料完整。

13. 提到等待時間的設定，建議依據網頁雲端服務等待時間（如2229）以確保順取完成。

14. 示範如何調整過濾參數（如增加或修改部）只獲得排序篩選人條評可。

15. 談論非網路技巧如"polling"，即定期檢查爬取合成分，適用於大量資料的情況。

16. 推薦用戶可以在免費計費中取得每例器案，並自行行進學習API運行。

17. 強調此流程可以用來搭建收集、爬取登客戶資料，進行後續行銷或研究。

18. 最後對整站點審支持影片，並歸檔經是運營 - joseph_styleiinstance-20250515-172807: -$
