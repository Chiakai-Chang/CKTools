# Chiakai's 科偵軍火庫
* [![Hits](https://hits.sh/chiakai-chang.github.io/CKTools.svg?style=for-the-badge&label=%E7%80%8F%E8%A6%BD%E4%BA%BA%E6%AC%A1)](https://hits.sh/chiakai-chang.github.io/CKTools/)
* 更新至 2024-07-03
* [**【建議與問題回饋請點我】**](https://forms.gle/euDVcKwk7QsiHgsz8)
---

# <span style="background-color:yellow;"> ☆☆☆ 溫馨提醒您 ☆☆☆ </span>
* 本軍火庫內之各項 **Colab** 或 **Google Sheet** 之工具，相關程式碼或設定全部都係開源透明的，歡迎取用、修改或[回饋改進意見](https://forms.gle/euDVcKwk7QsiHgsz8)。
* <span style="color:red;">**請先記得將工具複製到您的帳號再運作唷!**</span>
  * ### Colab 複製方法:
    * 左上角「**檔案**」->「**在雲端硬碟中儲存副本**」
  * ### Google Sheet 複製方法:
    * 左上角「**檔案**」->「**建立副本**」

---

# <span style="background-color:yellow;"> ☆☆☆ 重磅推薦 ☆☆☆ </span>
* ## [AI Insight Seeker 智慧偵查筆記系統](https://chiakai.pse.is/AIInsightSeeker)
[![](https://chiakai-chang.github.io/tempHTML/img/Logo_AIInsightSEEKER_small.png)](https://chiakai.pse.is/AIInsightSeeker)
  * <p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://chiakai.pse.is/AIInsightSeeker">AI Insight Seeker 智慧偵查筆記系統</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.linkedin.com/in/chiakai-chang-htciu">Chang, Chia-kai</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""></a></p>
  * 隨著資訊爆炸、新興科技飛速演進，致使網路犯罪案件激增，員警負荷過載，傳統偵查模式面臨挑戰。本作品設計並實作一套以協作為基礎的偵查管理平台，旨在解決資訊過載及知識碎片化問題。該系統平臺藉由 Google Sheets 強大的共用協作功能，適用於跨區域、跨國偵查，實現偵查工作的即時分配、進度追蹤及資料結構化等管理。透過高度整合且自動化的管理工具，有效提升自身偵查小隊或跨團隊間的協同合作、偵查過程情資共享透明度、同步協作效率及資訊共享準確性。
    * ※ 相關學術論文撰寫中。
  * **核心特色**
    * **智慧型洞察與管理**：<br>
      透過整合的儀表板，AI Insight Seeker 為同一偵查團隊除提供整體案件進度、活動完成情況和任務逾期提醒的即時概覽；亦可由偵查團隊人員分配偵查工作，細部查看個別偵查人員工作負載量與個別偵處進度，支持偵查活動的全面管理。
    * **偵查作為一覽表**：<br>
      作為知識共享和問題解決的核心，這個工作表詳細記錄每一步偵查行動的規劃、進行狀態和結果，包括預計完成日期和逾期提醒，確保案件追蹤的準確性和時效性。這不僅促進了知識共享，還提高了偵查工作的效率和成效。
    * **障礙排除記錄**：<br>
      專門設計來記錄偵查過程中遇到的障礙和延遲原因，這一功能強調了在面對挑戰時的透明度和問題解決策略，促進了團隊間的溝通和協作。
    * **一站式管理與深度整合工具**：<br>
      將常用的網路偵查工具如 WHOIS、PingFromEverywhere 等整合於單一平台，方便快速使用和記錄偵查結果，提升偵查效率。
  * 同仁可搭配 [**Chiakai's CyberSleuths: Digital Detective Challenge**](https://chiakai.pse.is/CyberSleuths) 這個專為訓練網路科技犯罪偵查而設計之事件擬真遊戲，透過各種隨機生成之網路犯罪事件，逐一學習如何進行相關調查與管理相關偵查作為。

---

# <span style="background-color:yellow;"> ☆☆☆ 科技偵查指令秘笈 ☆☆☆ </span>
* ## [現場勘查參考(操作系統Log與指令)](https://hackmd.io/@chiakai/OSnCMD)
* ## 網頁勘查_DevTools Console 可用指令
  * ### [必須先做] 請先「手動」輸入以下指令，才會被允許在 DevTools 的 Console 內貼上程式碼:
    ```javascript
    allow pasting
    ```
    * 或者見到 Console 出現以下警示的時候，也請「**手動**」輸入上記指令
      ![](https://chiakai-chang.github.io/tempHTML/img/allowpasting.png)
  * ### 列舉出網頁中「所有圖片連結 」(即\<img\>)
    ```javascript
    document.querySelectorAll('img').forEach(target_tag => {console.log(target_tag.src);});
    ```
  * ### 列舉出網頁中「所有影片連結」(即\<video\>)
    ```javascript
    document.querySelectorAll('video').forEach(target_tag => {console.log(target_tag.src);});
    ```
  * ### 列舉出網頁中「所有連結」(即\<a\>) 
    ```javascript
    document.querySelectorAll('a').forEach(target_tag => {console.log(target_tag.href);});
    ```
* ## ☆ 快速點「簿冊傳閱」(勤教) 密技 ☆
  * 步驟:
    * 1. 開啟到「值班臺應勤簿冊電子化系統」-「簿冊傳閱」的網頁
    * 2. 按「F12」開啟DevTools，選「Console」頁籤
    * 3. 在「>」後面輸入以下指令，然後按 「Enter」鍵，瞬間就可以幫你全部點完
  * 指令:
    ```javascript
    document.querySelectorAll('#btnDetail').forEach(button => button.click());
    ```
* ## ☆ 下載「PDF」簡報檔密技 ☆
  * 步驟:
    * 1. 使用 Chrome 到教育訓練網站，選擇你的課程，直到打開簡報檔的網頁
    * 2. 點右上角的「⋮」 -> 選「更多工具」 -> 選「開發人員工具」(即 DevTools)
    * 3. 「開發人員工具」(即 DevTools) 跳到「Network」頁籤，點上方「∅」符號清空目前封包
    * 4. 回到網頁，按 F5 重新整理
    * 5. 「Network」頁籤會攔到「getPDF.php?id=...」的封包，請看該封包的「Request URL」，其中的「id=...」跟「&ticket=...」中的...就是我們需要的資料
    * 6. 請將以下指令中的 id=... 跟 ticket=... 中的 ... 替換成你取到的資料
        * 指令:
           ```javascript
           var link = document.createElement('a'); link.href = "getPDF.php?id=...&ticket=..."; link.download = 'document.pdf'; document.body.appendChild(link); link.click(); document.body.removeChild(link);
           ```
    * 7. 將上述指令修改後，貼到 Console 執行，稍等一下就會跳出視窗問你 PDF 要下載到哪了 
  * 例圖:
    * ![](https://chiakai-chang.github.io/tempHTML/img/downloadPDFpng.png)
---

# <span style="background-color:yellow;"> ☆☆☆ 精心研發各種線上 AI 智慧偵查小幫手 ☆☆☆ </span>
* ## 全新! [CrossCaseSolver 跨境偵查小助手](https://chiakai.pse.is/CrossCaseSolver_POE)
  * [![](https://chiakai-chang.github.io/tempHTML/img/CBIA.png)](https://chiakai.pse.is/CrossCaseSolver_POE)
  * 因網路犯罪愈發頻繁，使用境外IP如 VPN、Web Hosting 等躲避查緝的情形也愈發常見。為貫徹刑案偵查並尋求突破可能，特別開發此工具協助同仁在跨國調閱資料時，幫忙提醒應注意事項、提供調閱之建議，並以該國適當的用詞用語協助撰寫資料調閱之 Email，藉以降低同仁跨境追查之協調困難，提升同仁突破困境之意願。
  * 特色:
    * 1、協助偵辦跨國案件的 Email 撰寫。
    * 2、會幫忙提醒要注意時區等等。
    * 3、不知道可以調什麼，也可以幫你想。
    * 4、一次產多國語言都可以。
    * 5、還會幫你使用跨國適當的用詞用語。
  * 趕快來試用看看吧!!
  * 當前有兩個版本：
    * ### (新!) [Open AI 平臺](https://chiakai.pse.is/CrossCaseSolver)
      * 語言模型：GPT-4 turbo (數一數二強大)
      * 次數限制：40筆/3小時
      * 收費：需有 ChatGPT Plus 資格(20美元/月)
    * ### (免費!) [POE 平臺](https://chiakai.pse.is/CrossCaseSolver_POE)
      * 基於 Claude-instant-100k 語言模型
      * 次數限制：40筆/天
      * 免費
  * 範例:
    <table>
      <tr>
        <td><img src="https://chiakai-chang.github.io/tempHTML/img/CBIA_Start.png" width="250" height="250"></td>
        <td><img src="https://chiakai-chang.github.io/tempHTML/img/CBIA_Chinese.png" width="250" height="250"></td>
      </tr>
      <tr>
        <td><img src="https://chiakai-chang.github.io/tempHTML/img/CBIA_Japanese.png" width="250" height="250"></td>
        <td><img src="https://chiakai-chang.github.io/tempHTML/img/CBIA_English.png" width="250" height="250"></td>
      </tr>
      <tr>
        <td><img src="https://chiakai-chang.github.io/tempHTML/img/CBIA_China.png" width="250" height="250"></td>
        <td></td>
      </tr>
    </table>

* ## 全新改版! [Code Investigater AI 隨身程式碼鑑識小幫手](https://chiakai.pse.is/CodeInvestigatorAI)
  * [![](https://chiakai-chang.github.io/tempHTML/img/Cute_CODE_INVESTIGATOR_AI.png)](https://chiakai.pse.is/CodeInvestigatorAI)
  * 為解決執行數位鑑識現場勘查時，遇到「開發人員」相關現場充斥複雜難懂之各種程式碼的問題，該問題令現場查緝人員難以快速瞭解掌握涉案情形或釐清現場人員所言是否真實，特別開發此工具，提供快速分析程式碼並產出報告的功能，協助現場快速掌握涉案狀況。
  * 特色:
    * 1、可以直接將程式文檔上傳(如 .html、.py、.bat、.sh、.ps1等)，不用複製貼上。
    * 2、經歷數個月 N 輪的 Promt Engineering (提示工程)實測，目前可實現分析程式並給出以下報告內容: 
      * (1) 辨識是哪一種程式語言
      * (2) 分析程式功能概要
      * (3) 分析程式執行分析、函數名稱與程式碼出處(區分自動、手動的函數與類別區塊)
      * (4) 分析程式作者撰寫與變數命名之風格/特徵
      * (5) 分析並嘗試找出程式內留之相關聯絡資訊
      * (6) 分析並嘗試找出程式內之登入資訊(如帳號,密碼,Token等數位憑證)
      * (7) 分析並嘗試找出程式內之網路資訊(如IP、Port、路徑):
      * (8) 分析程式有無加密動作
      * (9) 分析程式是否有惡意程式碼
      * (10) 分析程式之網路交互作用(如從何處取得資料或將資料傳輸至何處)
      * (11) 分析程式是否存在資料混淆
      * (12) 分析程式是否有可疑/違法活動並總結出摘要
      * (13) 提供偵查建議
  * 趕快來試用看看吧!!
  * 當前有兩個版本：
    * ### (新!) [Open AI 平臺](https://chiakai.pse.is/CodeInvestigatorAI)
      * 語言模型：GPT-4 turbo (數一數二強大)
      * 次數限制：40筆/3小時
      * 收費：需有 ChatGPT Plus 資格(20美元/月)
    * ### (免費! 但結果較不穩定) [POE 平臺](https://chiakai.pse.is/CodeInvestigatorPOE)
      * 基於 Claude-instant-100k 語言模型
      * 次數限制：40筆/天
      * 免費

---

# <span style="background-color:yellow;"> ☆☆☆ 精心研發各種小幫手程式 (點擊程式名稱即可下載) ☆☆☆ </span>
* ## [IPwhois好好查](https://chiakai-chang.github.io/CKTools/Tools/IPwhoisTool.zip)
  * 當前版本： 20240403_2 [點我下載](https://chiakai-chang.github.io/CKTools/Tools/IPwhoisTool.zip)
  * 一般案件偵查時，針對 IP 使用紀錄通常有幾十到上百的 IP 要逐筆手動查詢 Whois，再轉貼到 Excel 中，往往查完到整理好可以申請投單調閱就已耗時2小時以上；甚至在從事 log 分析時，還可能面臨有多達百萬、甚至上千萬行的資料與 IP，以人力是不可能完成的困境(以舊版的 IP Whois 好好查仍需耗費約連續60~80小時才能查完)。因此特別設計、改進此程式，讓大家自由貼上任意文本資料，程式將自動從每一行資料中，將 IP 抽取出來彙整，並以「即時更新離線資料庫」搭配精心設計的「二分搜尋演算法 (Binary search algorithm)」來加速，自動進行 IP Whois 查詢(若係臺灣 IP 還會再進一步自動查詢 TWNIC 資料)，最後將結果整理成「Excel 一覽表」+「臺灣 IP 基資投單格式 TXT 檔」，其中惱人的 IPv6 也會自動幫大家轉換成符合投單系統可以吃的格式。力求從各種面向，以最貼心的方式，大量節約同仁查詢所需耗費的寶貴時間與精力。
  * 解壓縮密碼：`htciu`
  * [![](https://chiakai-chang.github.io/CKTools/img/ipwhois_poc.png)](https://chiakai-chang.github.io/CKTools/Tools/IPwhoisTool.zip)

---

# <span style="background-color:yellow;"> ☆☆☆ 精心研發各種小幫手程式 (Colab 即取即用，點擊程式名稱即可開啟) ☆☆☆ </span>
* ## [洞察 IP 下載 BT 紀錄 AI 小幫手](https://chiakai.pse.is/AIBTinsight)
   * 緣起:
     * 執行網路案件偵查時，IP 的追查有時候是境外的大家就自動忽略了，但其實 [I Know What You Download](https://iknowwhatyoudownload.com) 網站有提供 IP 對應下載過的 BT 紀錄，還是可以幫忙了解一下該 IP 使用者的一些習性，包括上網時間(是否比較屬於哪個時區的人)、下載的檔案是比較偏哪個語系、是不是都是很專業的工具軟體、是哪方面的專業，還是只是影音娛樂等等。
     * 因為該網站沒有提供下載成 Excel 或 CSV 格式，且複製到 Excel 都無法正確對應。
     * 而且下載後，還有需要分析該 IP 使用者作息時間與下載內容剖繪。
     * 故設計這個小幫手幫忙，除自動下載以外，並利用 AI 幫忙分析(由 Chat-GPT 幫忙的唷，感謝 g4f 套件的開發團隊，但是他們是逆向人家的 API，好像也不太適合推崇，大家默默的...使用就好)，讓大家輕鬆偵查。
   * \[**重要提醒**\] 請務必將本小幫手按以下步驟複製到您的雲端硬碟，再開始執行唷
     * 1. 請按左上角「檔案」
     * 2. 請選「在雲端硬碟中儲存副本」
     * 3. 恭喜，你已經將本小幫手複製到您的雲端硬碟囉

* ## [網路檔案下載取證小幫手](https://chiakai.pse.is/DigitalForensicsFileDownloader)
  * 此小幫手旨在協助您從指定網址下載檔案。主要步驟包括：
    1. 下載並保存檔案。
    2. 同時保存該檔案的「原始封包」。
    3. 對下載的檔案和原始封包計算「雜湊值(HASH)」。
    4. 將上述所有資料壓縮成zip檔，便於封存並下載證據。
  * 使用此小幫手的優點：
    1. 透過 Colab 的虛擬主機進行下載，有效隱藏下載者的 IP 地址和裝置資訊，保護您的隱私。
    2. 結合下載檔案、保存原始封包和雜湊值計算於一體的高效率操作。
    3. 小幫手的程式碼完全開源，無需安裝任何額外套件，使用透明安全。

* ## [臉書好友整理神器](https://colab.research.google.com/drive/1JCgq0qmmsAtfuICuyk_CciQVjgSfKZ33?usp=sharing)
   * 請參考教學: [使用指引](https://drive.google.com/file/d/1KI8intBMvUYx2rTMgFi2utGGM6oxEH0i/view)
   * 整理大量以往難以人工彙整之臉書留言或按攢者資訊，並用以從事「交集分析」抓出關鍵犯嫌。

* ## [臉書留言整理神器](https://colab.research.google.com/drive/1t4xkYcXG0apHxFmjXqOPpR_cHpKwtfxV?usp=sharing)
   * 最近網路相關案件越來越多，臉書上假消息、恐嚇、不當發文等等也是越發頻繁，若是假帳號或相關資料很少的帳號發文，或者由他人轉 PO 的文章，常常都有需要從該貼文的留言內容，嘗試看看有無其他線索的需求。
   * 手動瀏覽再複製貼上，實在是很費力，所以特別撰寫這個小程式，只要會取得「留言部份」的網頁原始碼，貼給本程式，就會自動幫忙整理出以下資訊：
      * 1、留言者
      * 2、留言者臉書連結
      * 3、留言內容

* ## [IPv6 格式轉換小幫手](https://colab.research.google.com/drive/1we5ASiwmo9hfpVU9fNz0b115R-c0VPL5?usp=sharing)
   * 鑒於 IPv6 位址表示法太長，因此有所謂的以下「省略規則」：
      * 規則1：
         * 為每組數字的第一個0可以省略，若整組皆為0，則以0表示。譬如，「0DB8」可以省略為「DB8」，「0000」則為「0」。
      * 規則2：
         * 為連續出現的0000可以省略成「::」。譬如：「:0000:0000:0000:0000:」可以省略成「:0000:0000:0000::」、「:0:0:0:0:」、「:0::0:」或「::」。
   * 投單調取 IPv6 時，須輸入完整128bits，不可省略「0」，英文部分須為大寫。
      * 範例：2001:B400:E2AD:236A:713E:0BF4:804C:1573
   * 所以特別撰寫這個小程式，幫忙將 IPv6 都轉成符合投單調取的格式

* ## [批量 IP HTTP HEAD 確認小幫手](https://colab.research.google.com/drive/1N559gaAMvCnsKWwK3Y3DPUGDI26JGfNc?usp=sharing)
  * 若您有一批 IP 想了解該 IP 是什麼網站
  * 除了透過 Reverse IP Lookup 查詢 Domain 以外，。
  * 也可以針對該 IP 之 80 (http) 或 443 (https) port 發送 HTTP HEAD 請求。
    * 若該 IP 是 WEB server，就會回應 HTTP Headers，即該網站的 Meta Data，包括：
      * 伺服器類型，如: CloudFlare, Google 等。
      * Location，如： 該網頁的域名。
  * 曾經偵辦案件時取得過某不知身分犯嫌的 IP 連線紀錄，想了解他連線到的 IP 是什麼網站，看有沒有有助於瞭解查明該犯嫌身分的資料，所以撰寫了這個程式。
    * 想到可能對大家也會有幫助，特別釋出給大家使用。

* ## [大量同格式JSON彙整小幫手](https://colab.research.google.com/drive/1w1ApO_p3zh38ocU6jW5di3LXfeQWA3t6?usp=sharing)
  * 現在的網頁大多都基於 MVC 等架構，除了呈現的網頁以外，背後還會用 ajax 等方式用去存取 API 來獲得要更新顯示的資料(大多為 JSON 格式)。
  * 因為前述 JSON 給的資料往往比網頁上肉眼能看到得「更豐富」，且格式也更容易整理，所以有個小幫手可以幫忙將這些 Json 接收下來，一起轉換成更容易操作的 excel 格式，豈不美哉？
  * 本小幫手目前有兩種使用方法，適應不同情境：
    * 用法1: 整理已下載之大量 JSON 檔
    * 用法2: 每次複製貼上1筆，即時換整 JSON 資料再匯出

* ## [視覺化情資網路關聯小幫手](https://colab.research.google.com/drive/1hVI20D5MchN6OuSI8OSC6MVYTDSJclg6?usp=sharing)
  * 現在已有的視覺化分析軟體包括：i2 analyst's notebook、KeyLines 等等，真的非常好用。
  * 但是有以下困擾:
    1. i2 價格實在...門檻太高了。
    2. KeyLines 則需要在公務系統內使用，要比較注意資安稽核等等疑慮。
  * 加上有時候只是單純想要「顯示」情資之間的關聯，用來幫助判斷、分析資料。
  * 所以撰寫了個小程式，讓大家可以隨時隨地「免費的」視覺化自己資料之間的關聯。

* ## [AWS IP 確認小幫手](https://colab.research.google.com/drive/1T7vX0L2gs9VCNzwzSpvsI84rGTFRXl3R?usp=sharing)
   *  若大家有遇到 ip 是 amazon (亞馬遜) 的，可以使用這個小幫手來確認 IP 是 AWS 的什麼雲端服務。
      * 亦可參考 RyanLabs 提供之線上查詢工具：AWS IP Range Checker/Lookup Tool
         * 該工具僅能查詢 IPv4 的資料
   * 本程式係從官方：AWS IP address ranges 下載最新之 IP 資訊 (Json 檔，含 IPv4 與 IPv6) 進行比對，為最即時、最準確之資料

* ## [IP 與 CIDR (網段) 轉換小幫手](https://colab.research.google.com/drive/1DaA5otkgKxl5jZMMYxu8AJaTclpWdHPE?usp=sharing)
  * 因偵辦案件需要設 IP 黑名單阻擋涉案網段，若一個一個 IP 輸入費時費工，有時候 IP Whois 結果又只有提供起始、結束的 IP，還要自己換算成 CIDR 表示法。
  * 故乾脆自己寫一個程式來做轉換，比漫天找網路資源快多了。
  * 只要輸入起始、結束的 IP，就會自動將這之前所有不同的網段，都改以 CIDR 表示法的方式全部列舉出來。

* ## [地址轉經緯度小幫手](https://colab.research.google.com/drive/1BWleXRAN1vM82-k9lz-O78fPMqBZf581?usp=sharing)
  * 借用內政部國土測繪中心「國土測繪圖資服務雲」之電子地圖，查詢任意地址之完整行政區(至村里鄰)及經緯度。 

* ## [User-Agent 解析小幫手](https://colab.research.google.com/drive/1IP1t7yFuIYLnTttwcn_V5fy3XkJASk2d?usp=sharing)
  * 在做 log 分析時，常常都會遇到 User-Agent 這個資料，該資料通常包含了其應用程式類型(瀏覽器)、作業系統、軟體供應商……等等，有時還會包含軟體修訂版本等資訊。
  * 因該字串不容易閱讀，所以特別以小程式幫忙解析重點。

* ## [封包 headers 文字轉 dict 小幫手](https://colab.research.google.com/drive/15auzjfvWt6HICDyKtTDEFfKpoT-TlG7s?usp=sharing)
   * 使用 DevTools 複製找到並複製封包有關 Requests Headers 的文字內容。
   * 貼到程式後，即可整理成方便使用的 dict 格式，並自動將 cookie 分離。

* ## [時間戳轉換小幫手](https://colab.research.google.com/drive/1uzcBbl5EHOn8J5S_UHWQ2_rpfs_Gjttp?usp=sharing)
  * 在做資料清洗、資料探勘時，偶爾會發現有以數字表示的時間(即: 時間戳)。
  * 因為數字的時間戳雖然很方便比較「日期、時間差異」、方便做「時區加減計算」，但是不容易直觀的了解究竟是什麼時間，所以為了方便就寫了個小小小幫手。
  * 本小幫手目前有兩種使用方法，適應不同情境：
    * 用法1: 「時間戳」轉換成「西元日期」
    * 用法2: 「任意日期格式」轉換成「時間戳」

* ## [文字加解密技術](https://colab.research.google.com/drive/1lq6E8jFDKuXveji5zJmzl7m7hT3o3503?usp=sharing)
   * 提供文字有關「凱薩加密」、「二進制轉換」等2種之加解密，尤其是「二進制轉換」時常受資安相關社群隱藏發言所愛用。
   * 包含：
      * 凱撒加密
      * 二進制轉換 (資安社群常用)

---

# <span style="background-color:yellow;"> ☆☆☆ 資料分析處理工具區 ☆☆☆ </span>
* ## Google Sheet: [RE正規表達式套用範本](https://docs.google.com/spreadsheets/d/1qwhzTBiAizzCirTtNPr507Ub5mL4vfr85oOp86BVY5w/edit?usp=sharing)
   * 請參考教學: [使用指引](https://drive.google.com/file/d/1sC3xvlGxVF_IHNsWb78kqXjeRQyLfHHQ/view?usp=sharing)
   * 你可以透過這個範本，並參考相關的「正規表達式」，即能幫您從一行一行的文字資料中(例如: 165案情描述、log檔等等)，批次快速地自動化擷取出例如: 身分證號、手機號碼、市內電話、Email、URL、通訊軟體 ID (Username)等您所需要的關鍵資訊出來。
   * 優點:
     * 使用 Google Sheet 免費，且手機、電腦、平板都能使用。
     * 只要設定好表達式，並貼上一批您要分析的資料，就會一行一行很快速地幫您擷取出來
   * 缺點:
     * 受限於 Google Sheet 的 REGEXEXTRACT 函數，一次只能從您給的分析資料中擷取出第一個符合表達式的關鍵資訊，例如您的給資料中有出現 3 個 IP，就只能擷取出第一個  IP。

---

# <span style="background-color:yellow;"> ☆☆☆ 開源實用工具分享 ☆☆☆ </span>
* ## [WhisperDesktop](https://github.com/Const-me/Whisper) 錄音轉文字軟體
   * 請參考: [使用教學](https://notesstartup.com/youtube-ai-subtitle-tutorial/)
   * 已經為大家打包好實測最好用的模型+程式介面
     * [點我下載(WhisperDesktop.zip)](https://drive.google.com/file/d/1h9Bg9BpWooZMna8ZEieBhokfJJ6b6vXq/view?usp=sharing)
     * 解壓縮密碼: htciu
   * WhisperDesktop 是一款免費、開源的語音轉文字軟體，適用於 Windows 系統。它使用 OpenAI 的 Whisper 語音辨識模型來轉錄音訊和影片。WhisperDesktop 的優點是速度快、準確率高，而且可以支援多種語言，廣東話國語及英語。
   * 小評：
     * 用來快速產生錄音譯文、會議譯文應該是是蠻有幫助的唷！
     * 若錄音檔不在軟體本身預設支援的副檔名內(例如: .agg)而找不到檔案的話，可以先嘗試直接將副檔名改成 .wav 試試看，不行再轉檔就好。
     * 有學長提到在需要通譯陪同的筆錄，未來也許也可以藉由此開源模型去做初步的翻譯，藉以確認通譯所翻譯的譯文是否有正確傳達被詢問者的意思。這部分因為比較需要即時的翻譯，就不適用 WhisperDesktop 這個軟體，只能藉用 OpenAI 開發的 Whisper 語音辨識模型再另外開發，或尋找另外的介面軟體。
   * WhisperDesktop 優點
     * 速度快：WhisperDesktop 可以快速地轉錄音訊和影片。
     * 準確率高：WhisperDesktop 的準確率較高，可以滿足一般需求。
     * 支援多語言：WhisperDesktop 支援多種語言，可以滿足不同使用者的需求。
   * WhisperDesktop 及 OpenAI 的關係
     * WhisperDesktop 是基於 OpenAI 開發的 Whisper 語音辨識模型。OpenAI 是一家非營利性研究機構，致力於開發安全的人工智慧。Whisper 是 OpenAI 開發的一種大型語言模型，可用於語音轉文字、語言翻譯等。


---

# <span style="background-color:yellow;"> ☆☆☆ 人生與職場的心靈雞湯 ☆☆☆ </span>
* ## [智慧心境．蛻變領航．Wisdom Mindset Evolution Navigator](https://chiakai.pse.is/WMEN)
   * [![](https://chiakai-chang.github.io/tempHTML/Icons/WMEN.png)](https://chiakai.pse.is/WMEN)
   * ※ 這是一個基於 ChatGPT4o的GPT 
   * 🌟 提升心靈智慧，解答人生疑惑！ 🌟
       * 親愛的朋友們，我是 Chiakai，誠摯邀請您體驗我獨立設計的智慧心境導師：「智慧心境．蛻變領航．Wisdom Mindset Evolution Navigator」。
無論您遇到什麼困惑，或是需要人生建議，都將為您提供深入的洞察和個性化的指導，助您找到方向。
       * ✨ 功能亮點 ✨
           * 🔍 解答各種人生疑問
           * 🧠 提供專業的心靈指導
           * 🌟 給予實用的人生建議
       * 立即點擊以下連結，開始您的智慧之旅：
           * 👉 [https://chiakai.pse.is/WMEN](https://chiakai.pse.is/WMEN)
       * **提醒您**：
           * 由於此智慧心境導師需連線查資料，若出現連線許可請點選「**允許**」，以確保能為您提供最佳服務。
       * #智慧解惑 #心靈指導 #人生建議 #提升智慧
       
---

# <span style="background-color:yellow;"> ☆☆☆ 再次溫馨提醒您 ☆☆☆ </span>
* 本軍火庫內之各項 **Colab** 或 **Google Sheet** 之工具，相關程式碼或設定全部都係開源透明的，歡迎取用、修改或[回饋改進意見](https://forms.gle/euDVcKwk7QsiHgsz8)。
* <span style="color:red;">**請先記得將工具複製到您的帳號再運作唷!**</span>
  * ### Colab 複製方法:
    * 左上角「**檔案**」->「**在雲端硬碟中儲存副本**」
  * ### Google Sheet 複製方法:
    * 左上角「**檔案**」->「**建立副本**」
