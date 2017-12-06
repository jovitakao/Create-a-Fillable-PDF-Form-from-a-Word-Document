# Create-a-Fillable-PDF-Form-from-a-Word-Document
How to Create a Fillable PDF Form in Word

# 原由
客戶有個需求，將Word轉換成PDF，並只允許填寫幾個表單欄位。
## 業務說明
服務單位將fillable PDF表單email給申請單位，申請單位填寫好再“列印”成內容定死的PDF後，email回傳給服務單位接續處理。  
* 為何不在線上辦理？因為不想做成系統。  
* 為何不用Word填單就好？因為不想讓申請單位變動表單絲毫內容。只想讓申請單位可以填寫只需填寫的欄位。

# 製作fillable PDF主要流程
1. 先用Word把申請表單製作完畢  
   Word製作的越好後面轉換越方便。
2. 存成PDF。
3. 再用 [Adobe Acrobat pro DC](https://acrobat.adobe.com/tw/zh-Hant/free-trial-download.html) 轉換成 fillable PDF。商用的話請記得買license。  
   用【Prepare Form】功能，設定ArcoForm 互動欄位。  
   用【Edit PDF】功能，編輯與微調PDF。
4. 完工

# 應用測試
1. 用 [Adobe Acrobat Reader DC](https://get.adobe.com/tw/reader/)開啟fillable PDF。
2. 填寫好欄位。
3. 使用 Virtual PDF Printer 再“列印”成內容定死的PDF。

# 相關資源
* [Create a Fillable PDF Form from a Word Document](https://hip.ucdavis.edu/technical-support/create-fillable-pdf-form-word-document)
* [How to Create a Fillable PDF Form in Word](https://www.youtube.com/watch?v=RzmsSmyGLRQ)

# 原理
其實fillable PDF那些可以填寫的欄位，在規格上的名稱是「ArcoForm」。  
一些新的PDF API模組可以處理，比如：[PDFsharp](http://www.pdfsharp.net/)，但只能填寫不能新增。

(EOF)
