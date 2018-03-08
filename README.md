## 維基百科詞向量model

* 語料來源：<a herf="https://zh.wikipedia.org/wiki/Wikipedia:%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%8B%E8%BD%BD">維基百科：資料庫</a>
* 使用相關庫：
  * word2vec套件：<a href="https://github.com/RaRe-Technologies/gensim">gensim</a>
  * 斷詞套件：<a href="https://github.com/fxsjy/jieba">結巴中文分詞</a>, <a href="https://github.com/ldkrsi/jieba-zh_TW">結巴_TW</a>



### 簡體翻繁體

---

使用<a href="https://github.com/BYVoid/OpenCC">OpenCC</a>將簡體文字轉成繁體文字：

```
opencc -i wiki_text.txt -o zh_wiki_text.txt -c s2tw.json
wiki_text.txt -> zh_wiki_text.txt
```



### 訓練好的model下載

---

20171201版本（使用jieba）：<a href="https://drive.google.com/file/d/1BJmXftGSnPqYCNf539HQKSQ2KKno7bbI/view?usp=sharing">Google Drive</a>



