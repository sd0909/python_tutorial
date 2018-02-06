# Lesson 0
## 0.1安裝python(window版本)

1.在瀏覽器輸入:[https://www.python.org/downloads/](https://www.python.org/downloads/)
點選Download python 3.6.4

![](https://i.imgur.com/Gaya7Es.png)


2.下載後雙擊<python3.6.1.exe> 按下執行
![](https://i.imgur.com/10OL8hr.png)

3.記得將Add python 3.6 to path 勾選!!!
勾選完之後，按下install now
![](https://i.imgur.com/6L5Dkjg.png)

4.安裝完成後
打開命令提示字元>輸入`python --version`
如果出現如以下及代表安裝成功(忽略:: anaconda 4.4.0(64-bit))
![](https://i.imgur.com/ilvquCf.png)



---
## 0.2編輯軟體介紹
1. visual studio code 微軟公司開發，有很多插件可以安裝使用
https://code.visualstudio.com/

![](https://i.imgur.com/sJZlhO0.png)

2. sublime text 簡潔，也可以裝套件
https://www.sublimetext.com/3
![](https://i.imgur.com/HxaOSdz.png)
3. atom 由github公司支持，開源，也有很多套件跟主題可以使用
https://atom.io/
![](https://i.imgur.com/e7JxBA1.png)

選哪個都可以，喜歡就好~



---
## 0.3 一些小指令
在命令提示字元(win)中 Mac:終端機terminal
創建目錄`mkdir 資料夾名稱`
刪除目錄 `rmdir 資料夾名稱`
刪除檔案 `del 檔案名稱.副檔名` Mac:`rm 檔案名稱.副檔名`
進入目錄 `cd 資料夾名稱`
回到上一層 `cd ..`
顯示目錄中的檔案以及子目錄清單 `dir` Mac: `ls` 顯示所有檔案`ls -a`
顯示現在時間 `time`
清空畫面 `cls` Mac:`clear`    

ex:
![](https://i.imgur.com/YG07MbU.png)


---

## 0.4執行python程式的方法
`python 檔案名稱.py`
ex:
Step1: 打好程式碼 (用visual studio code為例，用啥都可以)
![](https://i.imgur.com/pZvejil.png)

Step2: 儲存檔案，存檔類型記得選Python (要記得自己存放的位置喔)
![](https://i.imgur.com/Xp1sccY.png)

Step3: 我存在桌面上，而我打開cmd時我的位置在Jay，所以先輸入`cd Desktop`
進入到Desktop後，輸入`python hello.py` hello是我檔案的命名py是副檔名
![](https://i.imgur.com/BetgRRF.png)
Step4: 輸入完畢後，按下enter 就可以看到結果~
![](https://i.imgur.com/SOi3XTS.png)


---
## 0.5 pip 以及 jupyter notebook

pip是一個套件管理工具，python擁有許多套件可以使用，因此一個管理工具就很重要，而pip就可以為我們做到這件事。

#### pip指令
查看安裝了哪些套件`pip list`
![](https://i.imgur.com/HRNfMhp.png)
安裝套件 `pip install 套件名稱 ` 以jupyter notebook 為例
![](https://i.imgur.com/3k5dhE3.png)
安裝好後可以輸入pip list 看看是否有安裝成功
![](https://i.imgur.com/Y3Jlv0D.png)有的話就代表成功~


更新套件 `pip install --upgrade 套件名稱`
![](https://i.imgur.com/g3a835g.png)

解除安裝套件 `pip uninstall 套件名稱`



---

## Lab0
1.安裝好python
回傳python --version的截圖

2.執行一次python的程式
回傳一個你執行的結果的截圖

3.安裝好 jupyter notebook
回傳pip list的結果的截圖

回傳至slack python channel