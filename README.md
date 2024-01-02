

# 3.1系統功能
透過前面的功能分析可以將員工宿舍管理系統的功能分為管理員、員工和維修員三個部分，系統的主要功能包括首頁、個人中心、員工管理、維修員管理、宿舍資訊管理、床位資訊管理、宿舍衛生管理、員工入住管理、報修資訊管理、分配任務管理、維修回饋管理、繳費中心管理、繳費記錄管理等內容。任何使用者只要進入網站不需登入也可瀏覽到的信息，後台管理是針對已登入的使用者看到滿意的員工宿舍資訊而設計的。
1、一般用戶的功能及權限
所謂一般使用者就是指還沒有註冊的過客,他們可以瀏覽主頁上的資訊。但如果要進入後台進行資訊管理時，要登入註冊，只有註冊成功才有的權限。

2、管理員的功能及權限
使用者資訊的新增和管理，員工宿舍詳細資訊新增和管理和文件資訊新增和管理以及網站資訊管理，這些都是管理員的功能。
3.系統功能結構圖
系統功能結構圖是系統設計階段，系統功能結構圖只是這個階段一個基礎，整個系統的架構決定了系統的整體模式，是系統的依據。員工宿舍管理系統的整個設計架構如圖3-1所示。
![image](https://github.com/xz55632/-SSM/blob/main/%E7%B3%BB%E7%B5%B1%E5%8A%9F%E8%83%BD%E7%B5%90%E6%A7%8B%E5%9C%96.drawio)
# 3.2可行性研究
透過系統研究目標及內容的分析審查後，提出可行性方案，並進行論述。主要從技術可行性出發，再進一步分析經濟可行性及操作可行性等面向。
# 3.2.1 經濟可行性
開發系統所涉及的資料，一般是在圖書館查閱，或在網上進行查找收集。所需的一些應用軟體也都是在網路上可以免費下載的，因此，開發成本是幾乎為零。但是開發出來的系統，還是具有高效率，低成本，較高品質的。所以，從經濟可行性的角度，系統符合標準。


# 3.2.2 技術可行性
技術可行性是考慮在現有的技術條件下，能否順利完成開發任務。以及判斷現有的軟硬體配置是否能滿足開發的需求。而本系統採用的是java技術開發，並非十分困難，所以在技術上是絕對可行的。此外，電腦硬體配置是完全符合發展的需要。
# 3.2.3 運行可行性
目前電腦資訊化的知識已經十分普及了，現在的操作人員也都是對系統環境有很強的適應性，各類操作人員大都是有過培訓補充的，因此完全不影響組織結構，所以在運行上也是可行的。
# 3.2.4 時間可行性
從時間上看，在大四的最後一個學期，在實習工作與完成畢設兩件大事相交叉的時間裡，結合之前學習的相關知識，並開發系統，時間上是有點緊，但是也不是完全沒可能實現，透過這段時間的努力功能基本實現。
# 3.3系統業務流程分析
員工宿舍管理系統是三種身分的用戶，主要涉及管理員、維修員和員工。每個身分都是操作起來都是清楚方便的。對於一些員工宿舍資訊,這是任何人都可以查看的，但是如果用戶想進入後台進行操作,則必須是已經進行登入的用戶，或者想修改員工宿舍資訊的話，也是需要用戶為登入狀態。這些使用者的基本資訊都由管理員對其統一管理。
根據員工宿舍實際過程的分析，網站有以下幾個部分，其中用戶註冊，發布個人信息，修改個人信息；用戶註冊登錄，發布員工宿舍信息；管理員管理用戶信息；一般用戶只可以瀏覽不可以發布資訊.以上業務過程從使用者角度可分為三類使用本系統的使用者角色，包括管理者、員工和維修員。以下針對各類使用者說明對應的業務流程。

# 3.4系統用例圖
系統用例圖如下圖3-2所示：
![image](https://github.com/xz55632/-SSM/blob/main/%E7%B3%BB%E7%B5%B1%E6%A5%AD%E5%8B%99%E7%94%A8%E4%BE%8B%E5%9C%96.drawio)

# 4.系統設計
# 4.1資料庫設計
資訊管理系統的效率和實現的效果完全取決於資料庫結構設計的好壞。為了確保資料的完整性，提高資料庫儲存的效率，那麼統一合理地設計資料庫結構是必要的。資料庫設計一般包括以下幾個步驟：
（1）依使用者需求，確定資料庫資訊進行保存
對使用者的需求分析是資料庫設計的第一階段，使用者的需求研究，熟悉小區運作流程，系統需求，這些都是以概念模型為基礎的。
（2）設計資料的概念模型
概念模型與資料建模使用者的觀點一致，用於資訊世界的建模工具。透過E-R圖可以清楚地描述系統所涉及的實體之間的相互關係。
員工註冊實體圖如圖4-1所示：

![image](https://github.com/xz55632/-SSM/blob/main/%E5%93%A1%E5%B7%A5%E8%A8%BB%E5%86%8A%E5%AF%A6%E9%AB%94%E5%9C%96.drawio)

圖4-1員工註冊實體圖
宿舍衛生管理實體圖如圖4-2所示：

![image](https://github.com/xz55632/-SSM/blob/main/%E5%93%A1%E5%B7%A54.png)

圖4-2宿舍衛生管理實體圖

# 5.1登入註冊模組
員工宿舍管理系統，管理員、員工和維修員透過填寫使用者名稱、密碼等資訊選擇角色進行登入就可以使用了，如圖5-1所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF1.jpg)

圖5-1系統登入介面圖

員工註冊，在員工註冊頁面透過填寫員工帳號、員工姓名、密碼、確認密碼、 手機號碼、信箱等資訊完成員工註冊，如圖5-2所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF2.jpg)

圖5-2員工註冊介面圖

維修員註冊，透過填寫維修員帳號、維修員帳號、密碼、 確認密碼、聯絡方式、信箱等內容進行註冊等操作，如圖5-3所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF3.jpg)

圖5-3維修員註冊介面圖

# 5.2管理員功能模組
管理員登入系統後，可對首頁、個人中心、員工管理、維修員管理、宿舍資訊管理、床位資訊管理、宿舍衛生管理、員工入住管理、報修資訊管理、分配任務管理、維修回饋管理、繳費中心管理、繳費記錄管理等內容進行詳細的操作，如圖5-4所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF4.jpg)

圖5-4管理員功能介面圖

員工管理，在員工管理頁面中可以對索引、員工帳號、員工姓名、手機號碼、頭像、性別、信箱、審核回覆、審核狀態、審核等內容進行詳情、修改或刪除等操作，如圖5-5所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF5.jpg)

圖5-5員工管理介面圖

維修員管理，在維修員管理頁面中可以對索引、維修員帳號、維修員姓名、聯絡方式、頭像、性別、信箱、審核回覆、審核狀態、審核等內容進行詳情、修改或刪除等操作，如圖5-6所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF6.jpg)

圖5-6維修員管理介面圖



宿舍資訊管理，在宿舍資訊管理頁面可以對索引、宿舍名稱、位置、床位數、狀態等內容進行發布、宿舍衛生修改或刪除等操作，如圖5-7所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF7.jpg)

圖5-7宿舍資訊管理介面圖

床位資訊管理，在床位資訊管理頁面可以對索引、宿舍名稱、位置、床位數等內容進行詳情、員工入住、修改或刪除等操作，如圖5-8所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF8.jpg)

圖5-8床位資訊管理介面圖

宿舍衛生管理，在宿舍衛生管理頁面可以對索引、宿舍名稱、位置、是否消毒、消毒影片、時間等內容進行詳情、修改或刪除等操作，如圖5-9所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF9.jpg)

圖5-9宿舍衛生管理介面圖

員工入住管理，在員工入住管理頁面可以對索引、宿舍名稱、 地點、床位數、員工帳號、員工姓名等內容進行詳情、修改或刪除等操作，如圖5-10所示。

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF10.jpg)

圖5-10員工入住管理介面圖

報修資訊管理，在報修資訊管理頁面可以對索引、宿舍名稱、位置、報修名稱、員工帳號、員工姓名、上報日期、審核回覆、審核狀態、審核等內容進行詳情、指派任務、修改或刪除等操作，如圖5-11所示

![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF11.jpg)

圖5-11報修資訊管理介面圖

分配任務管理，在分配任務管理頁面可以對索引、宿舍名稱、位置、報修名稱、員工帳號、員工姓名、上報日期、維修員帳號、維修員姓名、分配時間等內容進行詳情、修改或刪除等操作，如圖5-12所示。
![image](https://github.com/xz55632/market/blob/main/%E5%AE%BF12.jpg)

圖5-12分配任務管理介面圖




參考文件:https://blog.csdn.net/bishe401/article/details/127224532
