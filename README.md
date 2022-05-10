# Stock-Recommendation-Systems
一個關於股票的推薦系統  
旨在協助user發掘自己喜歡的股票, 並且將與之相似的股票推薦給user.

## Structure
  - Crawler, get data
  - 數學模型分析基本面
  - 針對各股對象做出數據特徵
  - Recommendation
  - GUI (LINE B)

## Recommendation Systems
- Content - Based Filtering (結合使用者評價與商品屬性, 推薦user偏好商品)優勢：
  - 用戶之間獨立性(User Independence), 較不易受用戶對item作弊影響.
  - 高可解釋性, 可根據item屬性立刻解釋為何推薦此一item.
  - New item可以立即推薦(np cold start), item不會有新/舊差異.

## Data
- 基本面
  - Goodinfo!台灣股市資訊網 https://goodinfo.tw/tw/index.asp
  - 公開資訊觀測站 https://mops.twse.com.tw/mops/web/index  
  - lab01_基本面數學模型. (因著網站data錯誤, 故自行撰寫數學模型程式, 做出基本面相關分析)
