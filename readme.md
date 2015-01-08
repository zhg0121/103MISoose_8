# 系統分析與設計 #
# 班級3B 第八組 #
## 旅遊查詢系統
##  ##
## 小組成員： 
0124038 宋彥陞

0124042 辜致豪

0124096 林慶龍
##
## 專題題目： ##
壹、基本簡介
	<br>　　本旅遊系統將各旅行社的旅遊範圍限定為國內，藉由比較各個不同旅行社同一旅遊地點之差異及費用，並將相關旅館、行程等做出比較，以供顧客做出最合適的決定。而在需求規格中，提供使用者透過此一系統得知各旅社的優惠專案其價格差異、著名行程選擇，節省搜尋成本，提升效率。

一、功能規格
		<br>　　旅行社簡介
		<br>　　旅遊篩選與查詢
		<br>　　留言板
		<br>　　客戶資料管理
		<br>　　客戶意見留言
		
二、非功能規格
	<br>　　可用性：介面的流程度掌握
	<br>　　可靠性：系統的有效及修復（ｄｅｂｕｇ）
	<br>　　績效性：提供伺服器處理效率
	<br>　　安全性：透過市場上著名防護軟體，提供基本的安全防護措施


三、利害關係人與目標
<br>內部人員
<br>　　專案人員
<br>　　　　測試人員

<br>外部人員
<br>　　客戶(旅遊消費族群)

四、利害關係人目標表 (P.85)
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
．利用留言板提供意見與想法<br>

</td>
</tr>

<tr>
<td>規劃人員</td>
<td>
．提供最新的旅行社資訊<br>
．維持資料的正確性<br>
</td>
</tr>



</table>


五、確認事件與使用案例 (P.87)

<table border="1" >
<tr>
<th>事件名稱</th>
<th>使用案例名稱</th>
</tr>

<tr>
<td>
1.能夠尋找興趣旅行社<br>
2.能夠進行價格比對<br>
3.能夠查詢旅遊行程<br>
4.更加了解旅遊地點<br>
5.建立與修改客戶資料<br>
6.給予網站相關建議<br></td>

<td>
1.旅行社查詢作業<br>
2.價格比對查詢作業<br>
3.旅遊行程查詢作業<br>
4.景點介紹影片查詢作業<br>
5.客戶基本資料作業<br>
6.客戶意見留言系統<br></td>
</tr>
</table>

貳、個別使用案例<br>
一、個別使用案例說明 (P.117)<br>
<img src="https://farm4.staticflickr.com/3952/15514932798_884fa71d6a_o.png" width="490" height="581" alt="11">

<img src="https://farm6.staticflickr.com/5609/15676595076_7ecb8e1b9d_o.png" width="491" height="585" alt="12">

<img src="https://farm4.staticflickr.com/3939/15700312205_ca4cf6c775_o.png" width="491" height="561" alt="13">

<img src="https://farm8.staticflickr.com/7472/15676595226_66ed79325b_o.png" width="492" height="731" alt="14">

<img src="https://farm8.staticflickr.com/7483/15698422271_6ac5e0b170_o.png" width="492" height="702" alt="15">

<img src="https://farm8.staticflickr.com/7514/15515126607_ab9dd20017_o.png" width="490" height="527" alt="16">

二、個別使用案例的活動圖 (P.114)<br>
<img src="https://farm4.staticflickr.com/3936/15566006656_dc99017495_o.png" width="514" height="389" alt="1">

<img src="https://farm4.staticflickr.com/3934/15587025941_f31c0358ee_o.png" width="515" height="364" alt="2">

<img src="https://farm6.staticflickr.com/5604/14969540033_933fe00038_o.png" width="513" height="389" alt="3">

<img src="https://farm6.staticflickr.com/5603/15403683767_c9ca77a742_o.png" width="511" height="391" alt="4">

<img src="https://farm4.staticflickr.com/3945/15403683717_8e4d495e1f_o.png" width="512" height="412" alt="5">

<img src="https://farm4.staticflickr.com/3942/15404081360_290cf2eda2_o.png" width="513" height="388" alt="6">

三、使用案例圖 (P.120)<br>
<img src="https://scontent-a-sjc.xx.fbcdn.net/hphotos-xap1/v/t1.0-9/10689910_958995600781570_5584691236118006573_n.jpg?oh=1dc82edeb000545994b8c51d436ed29f&oe=54EE6EEC" width="876" height="714" alt="P120-3">


四、使用案例的名詞與概念類別列舉表 (P.129 表5.4)<br>
1.旅行社查詢作業概念 類別列舉表<br>
<table border="1">
	<tr>
		<td>名詞</td>
		<td>原因</td>
		<td>結果(是否為概念類別)</td>
	</tr>
	
	<tr>
		<td>客戶<br>
		(Client)</td>
		<td>本系統需要從中記錄使用者所偏好的旅行社為何。</td>
		<td>是。</td>
	</tr>
	<tr>
		<td>入口網站<br>
		(Portal)</td>
		<td>提供使用者一個可以瀏覽著名旅行社最新消息之頁面。</td>
		<td>是。</td>
	</tr>

	<tr>
		<td>旅遊社資訊<br>
		(travelInfo)</td>
		<td>為搜尋頁面屬性。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>搜尋列<br>
		(searchBar)</td>
		<td>為搜尋頁面屬性。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>規劃人員<br>
		(Planner)</td>
		<td>本系統需要規劃人員。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>旅行社資訊</td>
		<td>同旅行社資訊。</td>
		<td>否。</td>
	</tr>
</table>

2.價格比對查詢作業 類別列舉表<br>
<table border="1">
	<tr>
		<td>名詞</td>
		<td>原因</td>
		<td>結果(是否為概念類別)</td>
	</tr>

	<tr>
		<td>客戶<br>
		(ClientData)</td>
		<td>本系統需要從中記錄使用者所偏好的旅行社為何。</td>
		<td>是。</td>
	</tr>

	<tr>
		<td>他家旅行社之價格</td>
		<td>同搜尋結果。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>搜尋頁面<br>
		(SearchPrice)</td>
		<td>提供使用者可進行資料初步的行程篩選，以求所需的相關資訊。</td>
		<td>是。</td>
	</tr>

	<tr>
		<td>旅行地點<br>
		(travelPlace)</td>
		<td>為搜尋頁面屬性。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>旅遊天數<br>
		(travelDay)</td>
		<td>為搜尋頁面屬性。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>查詢結果<br>
		(result)</td>
		<td>為搜尋頁面屬性。</td>
		<td>否。</td>
	</tr>
</table>

3.旅遊行程查詢作業 類別列舉表<br>
<table border="1">
	<tr>
		<td>名詞</td>
		<td>原因</td>
		<td>結果(是否為概念類別)</td>
	</tr>

	<tr>
		<td>客戶<br>
		(ClientData)</td>
		<td>本系統需要從中記錄使用者所偏好的旅行社為何。</td>
		<td>是。</td>
	</tr>

	<tr>
		<td>他家旅行社之行程</td>
		<td>同旅行地點、旅遊天數。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>搜尋頁面<br>
		(SearchTrip)</td>
		<td>提供使用者可進行資料初步的行程篩選，以求所需的相關資訊。</td>
		<td>是。</td>
	</tr>

	<tr>
		<td>旅行地點<br>
		(travelLocation)</td>
		<td>為搜尋頁面屬性。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>旅遊天數<br>
		(travelDays)</td>
		<td>為搜尋頁面屬性。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>查詢結果<br>
		(result)</td>
		<td>為搜尋頁面屬性。</td>
		<td>否。</td>
	</tr>
</table>

4.景點介紹影片查詢作業 類別列舉表<br>
<table border="1">
	<tr>
		<td>名詞</td>
		<td>原因</td>
		<td>結果(是否為概念類別)</td>
	</tr>

	<tr>
		<td>客戶<br>
		(ClientData)</td>
		<td>本系統需要從中記錄使用者所偏好的旅行社為何。</td>
		<td>是。</td>
	</tr>
	
	<tr>
		<td>旅遊地點介紹畫面<br>
		(TravelIntroducePage)</td>
		<td>本系統需要介紹客人預想旅遊地點資訊，以利客戶更加了解相關資訊。</td>
		<td>是。</td>
	</tr>
	
	<tr>
		<td>介紹地點<br>
		(introduce)</td>
		<td>為旅遊地點介紹屬性。</td>
		<td>否。</td>
	</tr>
	
	<tr>
		<td>影片網頁<br>
		(filmPage)</td>
		<td>為旅遊地點介紹屬性。</td>
		<td>否。</td>
	</tr>

	<tr>
		<td>youtube搜尋方式<br>
		(youtubeBar)</td>
		<td>為旅遊地點介紹屬性。</td>
		<td>否。</td>
	</tr>
</table>

5.客戶基本資料作業類別列舉表
<table border="1">
	<tr>
		<td>名詞</td>
		<td>原因</td>
		<td>結果(是否為概念類別)</td>
	</tr>

	<tr>
		<td>客戶<br>
		(Client)</td>
		<td>本系統需要從中記錄使用者所偏好的旅行社為何。</td>
		<td>是。</td>
	</tr>
	
	<tr>
		<td>入口網站<br>
		(Portal)</td>
		<td>提供使用者一個可以瀏覽著名旅行社最新消息之頁面。</td>
		<td>是。</td>
	</tr>
	
	<tr>
		<td>客戶基本資料<br>
		(ClientData)</td>
		<td>為已登入之客戶，客戶也可從中進行基本資料修改並瀏覽歷程記錄</td>
		<td>是。</td>
	</tr>
	
	<tr>
		<td>瀏覽紀錄<br>
		(searchRec)</td>
		<td>為客戶屬性</td>
		<td>否。</td>
	</tr>
	
	<tr>
		<td>帳號<br>
		(account)</td>
		<td>為客戶屬性</td>
		<td>否。</td>
	</tr>
	
	<tr>
		<td>密碼<br>
		(password)</td>
		<td>為客戶屬性</td>
		<td>否。</td>
	</tr>
	
	<tr>
		<td>姓名<br>
		(name)</td>
		<td>為客戶屬性</td>
		<td>否。</td>
	</tr>
	
	<tr>
		<td>性別<br>
		(sex)</td>
		<td>為客戶屬性</td>
		<td>否。</td>
	</tr>
	
	<tr>
		<td>信箱<br>
		(mail)</td>
		<td>為客戶屬性</td>
		<td>否。</td>
	</tr>
</table>

6.客戶意見留言系統類別列舉表
<table border="1">
	<tr>
		<td>名詞</td>
		<td>原因</td>
		<td>結果(是否為概念類別)</td>
	</tr>

	<tr>
		<td>客戶<br>
		(ClientData)</td>
		<td>本系統需要從中記錄已登入使用者所偏好的旅行社為何，並提供使用者一個可以提供網站意見的平台</td>
		<td>是。</td>
	</tr>
	
	<tr>
		<td>留言板<br>
		(MsgBroad)</td>
		<td>本系統提供一個平台供客戶留言其想法</td>
		<td>是。</td>
	</tr>
	
	<tr>
		<td>意見<br>
		(Comments)</td>
		<td>為留言板屬性</td>
		<td>否。</td>
	</tr>
	
	<tr>
		<td>客戶意見</td>
		<td>同意見</td>
		<td>否。</td>
	</tr>
	
	<tr>
		<td>規劃人員<br>
		(Planner)</td>
		<td>管理客戶意見之資料庫，並根據其建議進行網站之改善</td>
		<td>是。</td>
	</tr>

</table>

五、使用案例的初步類別圖 (p137 圖5.13)<br>
註:屬性需加入visibility + data type 以及屬於哪種類別boundary entity controller<br>

1.旅行社查詢作業概念 初步類別圖<br>
<img src="https://farm8.staticflickr.com/7518/15929357881_3724ecf362_o.png" width="1100" height="238" alt="1.旅行社查詢作業概念_初步類別圖">

2.價格比對查詢作業 初步類別圖<br>
<img src="https://farm6.staticflickr.com/5612/15649582869_9d9caf2743_o.png" width="1566" height="279" alt="2.價格比對查詢作業_初步類別圖">

3.旅遊行程查詢作業 初步類別圖<br>
<img src="https://farm8.staticflickr.com/7465/15835388495_4e180cf9c3_o.png" width="1458" height="279" alt="3.旅遊行程查詢作業_初步類別圖">

4.景點介紹影片查詢作業 初步類別圖<br>
<img src="https://farm9.staticflickr.com/8678/15215966383_63be73e89e_o.png" width="1849" height="276" alt="4.景點介紹影片查詢作業_初步類別圖">

5.客戶基本資料作業 初步類別圖<br>
<img src="https://farm9.staticflickr.com/8626/15905514846_a2b7fa4528_o.png" width="1523" height="553" alt="5.客戶基本資料作業_初步類別圖_2版">

6.客戶意見留言系統 初步類別圖<br>
<img src="https://farm8.staticflickr.com/7464/15649961568_a89dd7d267_o.png" width="1132" height="275" alt="6.客戶意見留言系統 初步類別圖">

六、系統的初步類別圖 (p151 圖5.30)<br>
註:屬性需加入visibility + data type以及屬於哪種類別boundary entity controller<br>
<img src="https://farm9.staticflickr.com/8580/15745566837_8a020bb9d7_o.png" width="2337" height="1311" alt="系統初步類別圖_專業版">

參、個別使用案例文件<br>
一、使用案例主要成功情節之英文名稱事件對應 (表6.5 p169）<br>
<img src="https://farm8.staticflickr.com/7567/15081249943_4ed0c8b01c_o.png" width="655" height="533" alt="61">

<img src="https://farm4.staticflickr.com/3941/15080642264_b85488ed4b_o.png" width="651" height="589" alt="62">

<img src="https://farm4.staticflickr.com/3947/15515778610_b052ec12bd_o.png" width="653" height="563" alt="63">

<img src="https://farm8.staticflickr.com/7560/15700583735_39400eb95f_o.png" width="651" height="647" alt="64">

<img src="https://farm6.staticflickr.com/5613/15676870006_f4ccfd57e9_o.png" width="651" height="537" alt="65">

<img src="https://farm4.staticflickr.com/3949/15515201038_9bded24bda_o.png" width="651" height="487" alt="66">

二、每個名稱事件之合約 (表6.6 p169)<br>
1.旅行社查詢作業<br>
<img src="https://farm8.staticflickr.com/7479/15514723069_42a24057d1_o.png" width="655" height="381" alt="611">

<img src="https://farm8.staticflickr.com/7577/15515398467_718cfbba3d_o.png" width="657" height="411" alt="612">

2.價格比對查詢作業<br>
<img src="https://farm4.staticflickr.com/3938/15702187272_6f5a8841f6_o.png" width="659" height="461" alt="621">

<img src="https://farm6.staticflickr.com/5603/15702187242_2f4cb2d88e_o.png" width="655" height="461" alt="622">

3.旅遊行程查詢作業<br>
<img src="https://farm6.staticflickr.com/5607/15698692321_de5ebdf691_o.png" width="661" height="463" alt="631">

<img src="https://farm6.staticflickr.com/5604/15515778360_3fae9d353c_o.png" width="653" height="491" alt="632">

4.景點介紹影片查詢作業<br>
<img src="https://farm6.staticflickr.com/5608/15698692211_d4d7252e97_o.png" width="653" height="461" alt="641">

<img src="https://farm6.staticflickr.com/5610/15080641844_fb68fdb18e_o.png" width="653" height="239" alt="642">

<img src="https://farm8.staticflickr.com/7503/15515201358_061278fb25_o.png" width="653" height="515" alt="643">

<img src="https://farm8.staticflickr.com/7564/15700584055_5ebb749dde_o.png" width="653" height="237" alt="644">

5.景點介紹影片查詢作業<br>
<img src="https://farm8.staticflickr.com/7581/15515201268_9c7ecb7d35_o.png" width="655" height="541" alt="651">

<img src="https://farm8.staticflickr.com/7562/15700584005_50cbf2077e_o.png" width="653" height="265" alt="652">

<img src="https://farm6.staticflickr.com/5614/15702187682_2347f0849a_o.png" width="657" height="491" alt="653">

6.景點介紹影片查詢作業<br>
<img src="https://farm4.staticflickr.com/3947/15515778780_c681a6ba0b_o.png" width="655" height="657" alt="661">

三、使用案例之系統循序圖 (圖6.13 p170)<br>
1.旅行社查詢作業<br>
<img src="https://farm4.staticflickr.com/3956/15566279416_a068607c47_o.png" width="696" height="558" alt="671">

2.價格比對查詢作業<br>
<img src="https://farm6.staticflickr.com/5609/14969228214_c31edf8fce_o.png" width="696" height="716" alt="672">

3.旅遊行程查詢作業<br>
<img src="https://farm4.staticflickr.com/3956/15589961645_1173a5638c_o.png" width="696" height="716" alt="673">

4.景點介紹影片查詢作業<br>
<img src="https://farm6.staticflickr.com/5607/14969228124_7f5c0fcdb4_o.png" width="617" height="627" alt="674">

5.客戶基本資料作業<br>
<img src="https://farm4.staticflickr.com/3936/15403963577_d2137e2d0e_o.png" width="617" height="627" alt="675">

6.客戶意見留言作業<br>
<img src="https://farm6.staticflickr.com/5601/14969817753_02aecbe663_o.png" width="617" height="627" alt="676">

系統循序圖
<img src="https://farm8.staticflickr.com/7511/15929357901_2c21be10a3_o.png" width="1412" height="629" alt="Untitled">

強韌圖
<img src="https://farm8.staticflickr.com/7523/16043661488_37a7b8043e_o.png" width="1286" height="629" alt="循序圖_統整">
ER Model
<img src="https://farm8.staticflickr.com/7478/16038971036_cbafec0e21_o.jpg" width="1228" height="808" alt="10860722_867643296590343_985004350_o">
