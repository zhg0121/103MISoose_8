# 班級3B 第八組 #
##  ##
## 小組成員： 
0124038 宋彥陞

0124042 辜致豪

0124096 林慶龍
##
## 專題題目： ##
基本簡介
	<br>　　設計相關系統，針對旅行社，比較同一旅行地點，不同旅行社之差異及費用，以供顧客做出最合適的決定。

定義需求與需求規格
	<br>　　提供使用者透過此一系統得知各旅社的優惠專案其價格、配套措施等差異，節省搜尋成本，提升效率。

功能規格
		<br>　　旅行社簡介
		<br>　　景點查詢
		<br>　　旅遊專案
		<br>　　客戶資料管理 <br>
		
非功能規格
	<br>可用性：介面的流程度掌握
	<br>可靠性：系統的有效及修復（ｄｅｂｕｇ）
	<br>績效性：提供伺服器處理效率
	<br>安全性：透過市場上著名防護軟體，提供基本的安全防護措施


利害關係人與目標
內部人員
	專案人員
	程式開發者
		測試人員
	Boss
外部人員
	客戶(旅遊消費族群)

利害關係人目標表 (P.85)
<table border="1" >
<tr>
<th>利害關係人 (參與者)</th>
<th>目標</th>
</tr>
<tr>
<td>客戶</td>

<td>
．能夠查詢各旅行社之相關資訊<br>
．能配合預算，找出合適的旅行社<br>
．獲取旅行社旅遊資訊<br>
．能夠正確查詢旅遊地點影片介紹<br>
</td>
</tr>

<tr>
<td>規劃人員</td>
<td>
．提供最新的旅行社資訊<br>
．維持資料的正確性<br>
</td>
</tr>

<tr>
<td>程式開發員</td>
<td>
．提供完善的查詢機制<br>
．提供簡潔舒適的介面<br>
</td></tr>
</table>


確認事件與使用案例 (P.87)

<table border="1" >
<tr>
<th>事件名稱</th>
<th>使用案例名稱</th>
</tr>

<tr>
<td>1.建立與修改客戶資料<br>
2.能夠尋找興趣旅行社<br>
3.能夠進行價格比對<br>
4.能夠查詢旅遊行程<br>
5.更加了解旅遊地點<br></td>

<td>1.客戶基本資料作業<br>
2.旅行社查詢作業<br>
3.價格比對查詢作業<br>
4.旅遊行程查詢作業<br>
5.景點介紹影片查詢作業<br></td>
</tr>
</table>

個別使用案例的活動圖 (P.114)<br>
<img src="https://farm4.staticflickr.com/3932/15272137627_670bfe1bdc_o.png" width="777" height="500" alt="1">

<img src="https://farm4.staticflickr.com/3928/15272137577_9a17a8ab27_o.png" width="769" height="500" alt="2">

<img src="https://farm3.staticflickr.com/2945/15272003680_40ba7e63b0_o.png" width="773" height="500" alt="3">

<img src="https://farm4.staticflickr.com/3928/15272003670_2b23612448_o.png" width="774" height="572" alt="4">

個別使用案例說明 (P.117)<br>
<img src="https://farm6.staticflickr.com/5601/15514571202_9a6d5bb39b_o.png" width="567" height="571" alt="2-1">
<img src="https://farm6.staticflickr.com/5599/15514971405_e939dafbc5_o.png" width="501" height="568" alt="2-2">
<img src="https://farm4.staticflickr.com/3945/15514571062_44146b7d79_o.png" width="499" height="570" alt="2-3">
<img src="https://farm3.staticflickr.com/2949/15328385577_a5ce6363c8_o.png" width="401" height="551" alt="2-4">

使用案例圖 (P.120)<br>
<img src="https://farm3.staticflickr.com/2950/15511812581_b9e6e81617_o.png" width="870" height="509" alt="P120-2">


<table border="1" >
<tr>
<th>使用案例名稱</th>
<th>旅行社查詢作業</th>
</tr>

<tr>
<td>使用案例描述</td>

<td>客戶可於網頁瀏覽部分旅行社資訊或自行查詢，依照自身喜好找出其有興趣的旅行社網站，以獲取相關的資料。</td>
</tr>

<tr>
<td>主要參與者</td>
<td>客戶、規劃人員</td>
</tr>

<tr>
<td>利害關係人與目標</td>
<td>客戶：能夠查詢各旅行社之相關資訊<br>
規劃人員：提供最新的旅行社資訊<br>
</td>
</tr>

<tr>
<td>前置條件</td>
<td>無。</td>
</tr>

<tr>
<td>後置條件</td>
<td>進行相關旅行社資訊的查詢</td>
</tr>

<tr>
<td>主要成功情節</td>
<td>
<table border="1">
	<tr>
		<td>參與者</td>
		<td>系統</td>
	</tr>
	<tr>
		<td>1.客戶於入口網站中，瀏覽本系統已列出之相關旅行社資訊。<br>
		2.客戶可於搜尋列進行其他旅行社之搜尋。<br>
		3.規劃人員進行旅行社資訊的更新並統計客戶所喜好的旅行社。<br>
		</td>

		<td>1.1	瀏覽頁面顯示旅行社相關資訊畫面。<br>
		2.1	使用google搜尋引擎另開分頁以進行其他旅行社的搜尋。<br>
		3.1	規劃人員於系統之後端資料庫進行資訊的更新。<br>
		</td>
	</tr>
</table>
</td>
</tr>

<tr>
<td>例外情節</td>

<td>*a. 如果有欄位無法(未)輸入，或資料無法儲存，系統需給予警告並指向錯誤頁面。</td>
</tr>

<tr>
<td>其他需求</td>
<td>無。</td>
</tr>
</table>
