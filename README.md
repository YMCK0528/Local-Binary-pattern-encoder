# Local Binary pattern encoder

2016 IC-Design-Contest 

問題描述:
局部二值模式(Local Binary Patterns, LBP)可用於描述局部紋理特徵的計算。本題請完成一Local Binary Patterns (後文以 LBP 表示),輸入為一灰階影像(如圖 1.所示),此灰階影像存放於 Host端的灰階圖像記憶體模組(gray_mem)中,LBP 須發送訊號至 Host 端以索取灰階影像資料,再對灰階影像中每個 pixel 各自進行獨立運算,運算後的結果請寫入 Host 端的局部二值模式記憶體模組(lbp_mem)內,並在整張影像訊號處理完成後,將 finish 訊號拉為 High,接著系統會自動進行比對整張影像資料的正確性。有關 LBP 的定義與運算方式,描述於後。
