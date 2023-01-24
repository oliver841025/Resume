## 簡介

Hi 你好，我是黃靖軒，前端工程師（React），過去曾任職於交易所約 1.2y。

### 發問與分享的環境
願意主動分享新知、新技術，認為討論是大家進步最快的方式，在講解概念時，最好不使用到專有名詞來解釋，將自己回歸白紙的思考，就會知道該如何去分享新知，也以此指導過新進同仁，在工作上也逐步看到成長，發問時也能先定義好問題邊界，提出自己認為的可能解法來做討論。

### 多人協作
熟悉 git 多人協作，多人環境協做下，知道何時該 pull, push, 規範每一次的 commit message 甚至是分支名稱, 解衝突, rebase, cherry-pick....等，主要是對於普遍的 git / gitlab 協作沒有問題，遇過沒處理過的狀況也能跟別人討論或是上網爬文而推敲出方向。

在前公司也有跑 gitflow，大致如下 :
- production: 發布用分支，會處在 production-ready 的狀態，禁止直接 commit 到此分支，也因為是穩定版本，會於此分支上的 commit 貼上版本標籤。
- develop: 開發用分支，所有的開發分支會從此分支切出去，開發完成再合併回來，而需要發布時，需要將 develop 合併進 production。
- hotfix: 修復用分支，從 production 切出來，修復完合併進 production 跟 develop。
- pre-production: 測試用分支，從 develop 切出來，主要給 ts 做測試。
- feature: 新增功能分支，從 develop 切出來，完成後再合併回 develop。

### 跨部門溝通
再更過去曾擔任過設計師，知道跟 UI 設計師該如何有效溝通，或是以他們的角度提出可能的解法，再來有開過資料庫，寫過 node.js 跟 Express，瞭解資料從後端傳遞到前端的流程，能有效跟後端討論 API 規格，在減少 server 負擔下，跟前端網頁效能間做個最適當的解法，也會盡量了解 API 再做串接。

### 職涯中的期許
主要是在工作上偶爾會記錄下一些比較深刻的狀況，大多是需要爬文做研究、跟別人討論的，可以從這邊看到一些:
- [React 多環境建置開發](https://medium.com/@oliver8410252594/react-%E5%A4%9A%E7%92%B0%E5%A2%83%E5%BB%BA%E7%BD%AE%E9%96%8B%E7%99%BC-fb9d30915b49)
- [串接 Firebase SDK 做 Google OAuth 第三方登入](https://medium.com/@oliver8410252594/%E4%B8%B2%E6%8E%A5-firebase-sdk-%E5%81%9A-google-oauth-%E7%AC%AC%E4%B8%89%E6%96%B9%E7%99%BB%E5%85%A5-3b8f39752423)
- [為什麼我們需要使用 Axios](https://medium.com/@oliver8410252594/%E7%82%BA%E4%BB%80%E9%BA%BC%E6%88%91%E5%80%91%E9%9C%80%E8%A6%81%E4%BD%BF%E7%94%A8-axios-d8e24fd34065)

再來因為非本科系，但在工作後想了解更底層的事，有回北科大再去修習了資料結構、物件導向、線性代數等大學部的課，也都順利通過。在團隊協作中願意主動溝通、分享新知、釐清需求，也能獨立完成專案功能的前端工程師，期許能在未來五年中成為前端團隊的 tech lead。

[線上版詳細履歷](https://www.cakeresume.com/oliver8410252594) 可以看這邊

簡單摘要先前工作使用過的技術如下：
- React / Redux
  基本使用 React hooks 沒有問題，基於效能優化，進階的 useMemo, useCallback 也使用過，專案從一開始使用 Redux，到後來由我提議使用 RTK 做狀態管理，畢竟 Redux 最讓人覺得麻煩的就是前置作業，也會有原則的整理 custom hooks。

- Axios
  打 API 時為了更好的封裝與統一整理 API，使用 Axios 取代原生 fetch 寫法

- UI Library
  能快速使用現有 UI Library 打造網站樣式，之前主要是使用 Ant design 做後臺系統，需要比較客製的部分，可以上網爬文做處理。
  
- 第三方服務
  使用 Firebase 做第三方登入，根據不同會員身分做權限控管(JWT)，使用 cloudStorage 做部署。
  
- 多環境建置
  刪除不必要的打 API 部分，根據不同環境寫 script，避免人為操作失誤。

其餘部分例如資料處理、切版，日常都會做，這邊就不特別提及。

## 工作地點

台北 / 新北

## 其他補充

- 非資訊本科生，透過「程式導師實驗計畫第五期」訓練轉職
- 有自建的[技術部落格](https://codemonkey.coderbridge.io/)，目前以紀錄學習到的技術為主，未來會著重在專案中遇到的問題與解法
- 過去曾為設計師，曾合作過許多動畫或是平面案，對於視覺方面的溝通成本或許可以低一些
- 老實說，上面技術不代表都精熟，每個專案或團隊所需使用程度不同，歡迎透過對答交流或信件聊聊，確認是否為彼此所需要的方向

## 聯絡方式

oliver8410252594@gmail.com

如有興趣的公司或團隊，或是有覺得適合的職缺，都可以先來信聊聊，信件請附上公司名稱以及職缺資訊，若有想幫我內推的也歡迎聯繫，總之任何訊息我都會盡量在三天內回覆！非常感謝！
