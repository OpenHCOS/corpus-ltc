# 前言

參加MCPM活動時剛好有學員提及音樂治療，長照語料收集也可考慮收集音樂創作，目前先進行相關音樂AI工具應用收集與整理。

# magenta.js

magenta.js可用來做AI深度學習音樂後處理，下面為測試別人已經做好的範例模型，後續可開發練習相關模型並拓展到長照領域。

- magenta-js/music https://github.com/tensorflow/magenta-js/tree/master/music
- Making music with magenta.js  https://hello-magenta.glitch.me/

## Piano Scribe 

https://piano-scribe.glitch.me/

Piano Scribe可以用網頁直接推論出人聲哼唱後鋼琴播放聲，並可轉存為MIDI檔案。midis/piano-scrbe-wedding-march.mid 為結婚進行曲哼唱燈燈燈結果，做了兩個版本可以比較，另一個是口哨版本piano-scrbe-wedding-march-whistle，可以看出模型要推論好還是要看訓練模型的環境。

結婚進行曲 (孟德爾頌) - 維基百科 https://zh.wikipedia.org/wiki/%E7%B5%90%E5%A9%9A%E9%80%B2%E8%A1%8C%E6%9B%B2_(%E5%AD%9F%E5%BE%B7%E7%88%BE%E9%A0%8C)

# Colab notebook (ipynb)

- Make music with Magenta https://colab.research.google.com/notebooks/magenta/hello_magenta/hello_magenta.ipynb
- Colab Notebooks https://magenta.tensorflow.org/demos/colab/

## Hello Magenta

放置在ipynbs裡面，目前版本出現不少DeprecationWarning: The binary mode of fromstring is deprecated待修正。

下載ipynb放置在github來觀看不會保存圖表與撥放MIDI音樂的功能，只能在colab裡面看到與聽到，也就是如果要取得製作內容須另外下載，無法跟ipynb放在同一個檔案裏面。