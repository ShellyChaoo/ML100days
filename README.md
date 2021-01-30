# ML60days
Python 資料科學程式馬拉松
- [Numpy](#numpy)
  * [Day 01 NumPy Basic Use](#day-01-numpy-basic-use)
  * [Day 02 NumPy Advanced](#day-02-numpy-advanced)
  * [Day 03 Universal Functions (ufunc)](#day-03-universal-functions--ufunc-)
  * [Day 04 Logic functions](#day-04-logic-functions)
  * [Day 05 Statistic ufunc](#day-05-statistic-ufunc)
  * [Day 06 IO](#day-06-io)
  * [Day 07 Matrix functions and linear algebra](#day-07-matrix-functions-and-linear-algebra)
  * [Day 08 Structured Arrays](#day-08-structured-arrays)
- [Pandas](#pandas)
  * [Day 09 IO](#day-09-io)
  * [Day 10 Indexing and selecting data](#day-10-indexing-and-selecting-data)
  * [Day 11 Categorical data and missing value](#day-11-categorical-data-and-missing-value)
  * [Day 12 Pandas plot](#day-12-pandas-plot)
  * [Day 13 Pandas statistic](#day-13-pandas-statistic)


<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## Numpy
### Day 01 NumPy Basic Use
介紹如何安裝及載入 NumPy。<br>
依照陣列產生的需求，使用相對應的函式，建立 NumPy 陣列。<br>
了解陣列屬性，在操作陣列時用來查看陣列資訊。<br>
NumPy 相關單元如果沒有特別說明的話，陣列均指 NumPy 陣列 (而非其他，例如 Python 陣列)。<br>

### Day 02 NumPy Advanced
陣列進階操作<br>
介紹陣列重塑<br>
介紹軸 (axis) 與維度 (dimension)<br>
介紹陣列的合併與分割<br>
介紹陣列的迭代<br>
介紹陣列的搜尋與排序<br>

### Day 03 Universal Functions (ufunc)
陣列運算及數學<br>
NumPy 提供許多數學及統計的函式，這些函式的用法都很相似，針對陣列進行 element-wise 的操作，並回傳陣列做為輸出，稱為 Universal Functions (ufunc)。

### Day 04 Logic functions
陣列的邏輯函式分為五大類，今天的內容會依照這五大類介紹相關的函式及使用。
- 陣列內容 (Array contents)
- 陣列型別偵測 (Array type testing)
- 比較 (Comparison)
- 邏輯操作 (Logical operations)
- Truth 值測試 (Truth value testing)

### Day 05 Statistic ufunc
陣列的統計功能分為四大類，今天的內容會依照這四大類介紹相關的函式及使用。
- 順序統計量 (Order Statistics)
- 平均數與變異數
- 相關性
- 直方圖 (Histogram)

### Day 06 IO
NumPy 提供自己的高效能檔案格式，可透過 save()、load() 等函式進行儲存或讀取，儲存時也可使用 savez() 將檔案壓縮。<br>
從一般的文字檔讀取或儲存，可以使用 savetxt() 與 loadtxt()。<br>
genfromtxt() 是一個功能強大且彈性的函式，能從文字檔中讀取陣列資料。<br>

### Day 07 Matrix functions and linear algebra 
學習 NumPy 線性代數相關函式，分為下列主題進行介紹。
- 矩陣乘積
- 矩陣操作
- 特殊矩陣
- 矩陣分解

### Day 08 Structured Arrays
深入了解 NumPy 資料型別 dtype 及如何應用<br>
介紹如何及操作結構化陣列 (Structured Arrays)<br>

## Pandas
### Day 09 IO
讀寫csv<br>
讀寫excel<br>
讀寫json<br>
讀寫SQL資料庫<br>

### Day 10 Indexing and selecting data
建立索引可快速找到需要的資料集。<br>
操作資料非常靈活可以刪減欄位，刪減列資料。<br>
資料過濾與操作資料不同，過濾出來的資料將是新資料集，不會動到原本的資料。<br>
合併資料時合併欄位(key)可多個欄位，遇到相同欄位名稱時 merge 會自動產生字尾，join 則不會。<br>

### Day 11 Categorical data and missing value
認識類別資料，有順序型與一般型，使用的編碼方式分別為<br>
- 順序性 LabelEncoder()
- 一般性 get_dummies() (One-hot Encoding)

缺值處理方法共有三種<br>
- 定值補值
- 前(後)補值
- 內插法補值

### Day 12 Pandas plot
折線圖<br>
- 適用：會隨時間變動的值
- 函數 : .plot()

長條圖<br>
- 適用：不同種類資料，在不同時間點的變化
- 函數 : .plot.bar()

箱型圖<br>
- 適用：完整呈現數值分布的統計圖表
- 函數 : .boxplot()

散佈圖<br>
- 適用：呈現相關數值間的關係
- 函數 : .plot.scatter()

### Day 13 Pandas statistic
mean, median, quantile, std, var, corr, apply...<br>
lambda x 相當於數學式中的 f(x) 