# Breeze-ASR-26 台語語音辨識測試 v.1

## [Colab-link](https://colab.research.google.com/github/aKi-1201/breeze-asr-26/blob/main/Breeze_ASR_26_%E5%8F%B0%E8%AA%9E%E8%AA%9E%E9%9F%B3%E8%BE%A8%E8%AD%98%E6%B8%AC%E8%A9%A6_v_1.ipynb)

### ● 簡介
Breeze-ASR-26 是 MediaTek Research 針對台語 (Taigi) 的自動語音辨識模型（基於 Whisper 微調），模型與說明可參考:
* https://huggingface.co/MediaTek-Research/Breeze-ASR-26

結合 Breeze-ASR-26 和 yt-dlp 的工具，就可以將 Youtube 上的影片或播放清單擷取聲音、儲存語音檔後，進行語音辨識，並生成字幕檔。

目前在後面程式設定區塊中，語音來源路徑的「url」欄位中，可以填入 Youtube 的影片或影片清單網址；如果是在電腦本機中的影片或聲音檔，則可以上載在左側資料夾中後，在「url」欄位中填入完整的檔名名稱。

接著將其它選項都設定好後，就可以在[程式區塊]中按「執行」的按鈕，開始進行語音辨識了。

Breeze-ASR-26 專為台語設計，輸出為中文漢字。若想用自動偵測或其他語言代碼，亦可自行調整設定。

程式第一次執行時，因為要安裝及下載自動語音辨識所需要的資料，可能要稍等一下下。

update: 2026.04.28

 [credit - @gsyan](https://gsyan888.blogspot.com/2023/02/openai-whisper-ipynb.html)
