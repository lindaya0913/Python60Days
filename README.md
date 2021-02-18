# Python60Days
## D01 NumPy 基本操作
1. 建立 NumPy array(陣列)
2. NumPy 陣列的索引和切片(Slicing)
3. NumPy 陣列的常用屬性
## D02 NumPy 陣列進階操作
1. NumPy 陣列重塑
2. 軸 (axis) 與維度 (dimension)
3. NumPy 陣列的合併與分割
4. 迭代
5. 搜尋與排序
## D03 NumPy 陣列運算及數學 Universal Functions (ufunc)
1. 四則運算
2. sum()
3. 次方 np.power()
4. 平方根 np.sqrt()
5. 歐拉數 (Euler's number) 及指數函式 np.exp()
6. 對數函式
7. 取近似值
8. 取絕對值：np.abs(), np.absolute(), np.fabs()
## D04 NumPy 陣列邏輯函式 (Logic Functions)
1. 陣列內容
2. 陣列型別偵測
3. 比較
4. 邏輯操作
5. np.all()、np.any()
## D05 NumPy 統計函式 Universal Functions (ufunc)
1. 順序統計量 (Order Statistics)
2. 平均數與變異數
3. 相關性
4. Histogram
5. digitize()
## D06 NumPy I/O
1. numpy.save()、numpy.savez()、numpy.load()
2. savetxt() 與 loadtxt()
3. genfromtxt()
## D07 NumPy 的矩陣函式與線性代數應用
1. 矩陣乘積
2. 矩陣操作
3. 特殊矩陣
4. 矩陣分解 (Matrix Decomposition)
## D08 NumPy 結構化陣列 (Structured Arrays)
1. 資料型別 (dtype)
2. 結構化陣列 (Structured Arrays)
3. RecordArray：numpy.recarray()
## D09 使用 Pandas 讀寫各種常用的檔案格式
1. 讀寫 csv
2. 讀寫 excel
3. 讀寫 json
4. 讀寫 SQL 資料庫
## D10 Pandas 資料的索引、操作、選擇、過濾、合併與排序
1. 索引
2. 操作資料
3. 資料過濾、選擇
4. 合併資料
## D11 Pandas 類別資料與缺失值處理
1. 認識類別資料，有順序型 LabelEncoder()與一般型 get_dummies()
2. 缺值處理方法共有三種:定值補值、前(後)補值
## D12 Pandas 常見圖表程式設計
1. 介紹常見的圖表種類與對應使用情境
2. 介紹如何在 Pandas 中繪製圖表
## D13 Pandas 統計函式使用教學
1. 應用統計函式
2. 自定義的行或列函式應用
## D14 用 Pandas 撰寫樞紐分析表
1. 在資料中的索引轉欄位、欄位轉索引
2. 欄位名稱轉為欄位值
3. 重新組織資料
## D15 Pandas Split-Apply-Combine Strategy
1. Groupby 可以同時針對多個欄位做 Group，並在 Group 中做運算
2. Split：將大的數據集拆成可獨立計算的小數據集
3. Apply：獨立計算各個小數據集
4. Combine：將小數據集運算結果合併
## D16 Pandas 時間序列
1. 時間序列資料處理
2. 日期時間處理
## D17 pandas 效能調校
1. 3種加速方法針對 Pandas ，在 Python 中還有很多方式可以提升效能
2. 欄位的型態降級有助於減少記憶體佔用空間
## D18 Python 資料視覺化工具與常見統計圖表介紹
1. 使用常見的子圖與軸圖來做畫面配置
2. 等高線圖
## D19 使用 Matplotlib 繪製各種常用圖表
1. 各種常見圖表適用情境範例展示
2. 經典圖表(直方、分箱、…)
3. 多重子圖表(subplot)
4. 其他圖型：密度圖、等高線圖
## D20 使用 Seaborn 進行資料視覺化
1. Seaborn：統計數據可視化
2. 結合 Matplotlib & Seaborn
3. 可視化線性關係和數據集的分佈
4. 使用語義映射繪製數據子集
## D21 運用實際資料集進行資料視覺化練習
1. 導入資料集
2. 針對特徵，視覺化的處理流程與效果
## D22 結合 Pandas 與 Matploglib 進行進階資料視覺化練習
1. 使用 Matplotlib, Seaborn, Pandas 處理龐大的數據集
- 條形圖(Bar plot)：條形圖也可稱為柱狀圖，通常用在數值的顯示或者比較。
- 直方圖(Hist plot)：用於頻率分佈，y 軸表示頻率分佈（數值或者比率），hist 函數柱體個數預設 bins=10，且預設圖中會有網格線。
- 散點圖能夠顯示 2 個維度上每組數據的值。可以顯示觀察數據分布情形，描述數據的相關性
- 核密度圖顯示數值變量的分佈，它非常類似於直方圖。
- 熱力圖是一個以顏色變化來顯示數據的矩陣。簡單來說，就是用依據數字的不同，使用不同的顏色來呈現數據。
## D23 BOKEH - 輕鬆以網頁呈現視覺化圖表
1. Bokeh 以成為交互式數據可視化的庫而自豪。
2. 不同於 Matplotlib 和 Seaborn 等 Python 可視化領域的流行同行，Bokeh 使用 HTML 和 JavaScript 渲染其圖形。這使其非常適合構建基於Web的儀表板和應用程序。但是，它是用於探索和理解數據或為項目或報告創建漂亮的自定義圖表的功能同樣強大的工具。
3. 提供了一些預先建置好的圖表供我們使用，其中幾個範例： bokeh.charts.Bar — 製作長條圖 bokeh.charts.BoxPlot — 製作盒鬚圖 bokeh.charts.HeatMap — 製作熱圖 bokeh.charts.Donut — 製作甜甜圈圖。
4. 為可視化添加交互姓 --- CustomJS/Render
## D24 Basemap 進行地理資訊繪圖
1. Basemap 工具，它是 mpl_toolkits 包中的一個專門用於構建地理信息數據可視化的擴展庫。Basemap 工具在地理信息讀寫、坐標映射、空間坐標轉化與投影等方面做的要比 geopandas 更加成熟，它可以使用常規的地圖素材數據源（shp）作為底圖進行疊加繪圖，效果與精度控制比較方便。
2. 投影 + 經緯度，底圖包括 GSSH(現在為 GSHHG)海岸線數據集，以及來自 GMT 的河流、州和國家邊界數據集。這些數據集可用於以多種不同解析度在地圖上繪製海岸線、河流和政治邊界圖像可以用作地圖背景，而不是繪製海岸線和政治邊界。
3. Basemap 類的 resolution 參數設置解析度級別：
- 'c'(原始)，'l'(低)，'i'(中)，'h'(高)，'f'(完整)或 None(如果沒有使用邊界)。 這個選項很重要，在全域地圖上設置高解析度邊界可能非常慢。
- 我們可以從放大到特定區域，這裡的參數是：llcrnrlat – 左下角的緯度，llcrnrlon – 左下角的經度，urcrnrlat – 右上角的緯度，urcrnrlon – 右上角的經度。可通過 drawmeridians()和 drawparallels()繪製經線和緯線。
## D25 使用 PANDAS 與 BASEMAP 將數據整合於地理資訊圖表
1. 結合 PANDAS，利用 PANDAS 的數據繪製關係圖
2. 如何自行輸入經緯度繪製所在區域的地圖
3. 學習如何讀取氣象資訊檔：netCDF4
## D26 用統計描述資料的樣態
1. 拿到資料後，要先判斷：母體 vs 樣本
2. 挑選適當統計量，描述出資料的輪廓
3. 敘述統計值，可以快速知道資料的特徵，進行簡單的比較，但只是現象，不是真相。
## D27 用機率分布描述亂中有序的世界－離散型分配 (1)
1. 生活中常見的離散分配的意義與性質，包含離散均勻分配(Discrete Uniform Distribution)、伯努利分配(Bernoulli Distribution)、二項分配(Binomial Distribution)。
2. 運用 python 語法了解各分配的特性與應用 pmf、cdf、rvs 和 stats
## D28 用機率分布描述亂中有序的世界－離散型分配 (2)
1. 生活中常見的五種離散分配
- 離散均勻分配
- 伯努利分配:只有兩種可能結果（成功與失敗）的單次隨機試驗
- 二項分配:在一系列獨立同分布的伯努利試驗中，其 n 次結果總和
- 負二項分配(Negative Binomial Distribution):在一系列獨立同分布的伯努利試驗中，X 為成功次數到達指定次數（記為 𝑘 ）時，需要試驗的次數的機率分布
- 超幾何分配(Hypergeometric Distribution):由有限個物件中抽出n個物件，成功抽出指定種類的物件的個數 (不歸還(without replacement)），若 n=1，超幾何分布還原為伯努力分布（bermulli(p)）