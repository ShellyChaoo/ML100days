# ML60days
Python 資料科學程式馬拉松
- [Numpy](#numpy)
  * [Day 1 NumPy Basic Use](#day-1-numpy-basic-use)
  * [Day 2 NumPy Advanced](#day-2-numpy-advanced)
  * [Day 3 Universal Functions (ufunc)](#day-3-universal-functions--ufunc-)
  * [Day 4 Logic functions](#day-4-logic-functions)
  * [Day 5 Statistic ufunc](#day-5-statistic-ufunc)
  * [Day 6 IO](#day-6-io)
  * [Day 7 Matrix functions and linear algebra](#day-7-matrix-functions-and-linear-algebra)
  * [Day 8 Structured Arrays](#day-8-structured-arrays)
- [Pandas](#pandas)
  * [Day 9 IO](#day-9-io)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## Numpy
### Day 1 NumPy Basic Use
介紹如何安裝及載入 NumPy。
依照陣列產生的需求，使用相對應的函式，建立 NumPy 陣列。
了解陣列屬性，在操作陣列時用來查看陣列資訊。
NumPy 相關單元如果沒有特別說明的話，陣列均指 NumPy 陣列 (而非其他，例如 Python 陣列)。

### Day 2 NumPy Advanced
陣列進階操作
介紹陣列重塑
介紹軸 (axis) 與維度 (dimension)
介紹陣列的合併與分割
介紹陣列的迭代
介紹陣列的搜尋與排序

### Day 3 Universal Functions (ufunc)
陣列運算及數學
NumPy 提供許多數學及統計的函式，這些函式的用法都很相似，針對陣列進行 element-wise 的操作，並回傳陣列做為輸出，稱為 Universal Functions (ufunc)。

### Day 4 Logic functions
陣列的邏輯函式分為五大類，今天的內容會依照這五大類介紹相關的函式及使用。
- 陣列內容 (Array contents)
- 陣列型別偵測 (Array type testing)
- 比較 (Comparison)
- 邏輯操作 (Logical operations)
- Truth 值測試 (Truth value testing)

### Day 5 Statistic ufunc
陣列的統計功能分為四大類，今天的內容會依照這四大類介紹相關的函式及使用。
- 順序統計量 (Order Statistics)
- 平均數與變異數
- 相關性
- 直方圖 (Histogram)

### Day 6 IO
NumPy 提供自己的高效能檔案格式，可透過 save()、load() 等函式進行儲存或讀取，儲存時也可使用 savez() 將檔案壓縮。
從一般的文字檔讀取或儲存，可以使用 savetxt() 與 loadtxt()。
genfromtxt() 是一個功能強大且彈性的函式，能從文字檔中讀取陣列資料。

### Day 7 Matrix functions and linear algebra 
學習 NumPy 線性代數相關函式，分為下列主題進行介紹。
- 矩陣乘積
- 矩陣操作
- 特殊矩陣
- 矩陣分解

### Day 8 Structured Arrays
深入了解 NumPy 資料型別 dtype 及如何應用
介紹如何及操作結構化陣列 (Structured Arrays)

## Pandas
### Day 9 IO
讀寫csv
讀寫excel
讀寫json
讀寫SQL資料庫
