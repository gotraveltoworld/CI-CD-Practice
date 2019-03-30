# Welcome to 廣宣學堂 [BroadMission.org](https://www.facebook.com/broadmission) #
## 【DevOps學程[ CI/CD 實作工作坊](https://broadmission.kktix.cc/events/5218a5a3)】學習資訊共筆系統 ##

### March 30 2019 ###

### A. 教材
- 課前作業: 歡迎先練習與思考，請見[文件](http://bit.ly/2Fzl1NY)最末頁
- [投影片](https://drive.google.com/file/d/1qijSz1sYMi8RLB20Db9q7QBYEi0yPaDu/view?usp=sharing)(已上架)
- [code](https://drive.google.com/file/d/1QT4gYYraTXiPI8dw3j4in96-azB9QPYO/view?usp=sharing)下載

### B. 共筆 (歡迎一同筆記, Markdown)

### C. 事先安裝事項 (亦可參考[文件](http://bit.ly/2Fzl1NY))

- 註冊 gitlab.com / github.com 帳號
    - 請於 gitlab / github 帳號中各建立一個 project，可設為 private
    - 註冊 gitlab [參考網頁](https://blog.csdn.net/fucaijin/article/details/80860112)
    - 註冊 github [參考網頁](https://progressbar.tw/posts/3)

- 本次以虛擬機操作為主，請課前先下載並安裝完畢

    1. 下載安裝 [virtualbox](https://www.virtualbox.org/wiki/Downloads)
        - 安裝步驟[參考網頁](https://zh.wikihow.com/%E5%AE%89%E8%A3%85VirtualBox)

    2. **事先下載 VM 的.ova 檔**  [下載點1](https://chengweichen.com/workshop/CI_CD_Workshop_0330.ova) / [下載點 2](http://bit.ly/2JGey8e)
    3. 設定VM環境 (啟動映像檔前，請先完成設定)
          - 點選匯入的 VM 後選擇"設定值"
          - 選擇後確定以下的設定
          ```
               - 系統>主機板>基本記憶體 --> 1024~2048 (1024至少；2048為佳)
               - 系統>處理器>處理器 --> 1~2 (2為佳)
               - 系統>加速>硬體虛擬化 --> 勾選 "啟用 VT-x/AMD-V"
               - 網路>介面卡1>點開 "進階">連接埠轉送 --> 檢查是否有一項為
                    主機IP=127.0.0.1/ 主機連結埠=2222/ 客體連接埠=22
          ```
          - 點擊 "確定" 離開設定

    4. 啟動 VM (請確認防火牆 2222埠為開放)

    5. 使用 Putty 或 Cmder 或其他 ssh client 登入
        - 請注意登入 127.0.0.1 的埠 **2222**，帳密為 vagrant / vagrant
            - 下載 [Putty](http://www.putty.org/)
            - 下載[Cmder](http://cmder.net)(選擇 Download full)
    6. 確認功能

          - 確認 docker 有否正確運作

            `` 指令: service docker status``
               - 結果應為 active(running)

          - 確認對外網路是否暢通 (請先確認筆電連網)
            `` 指令: sudo apt-get update``
              - 結果在末段應有 "Reading package lists... Done"

    7. 完畢

### D. 回饋與後續服務
- 回饋單[點此填寫](https://goo.gl/forms/RoxUeINjpqboFZm42)
全程參加課程者，可獲得本課程電子證書。

- 加入廣宣學堂 學習 Line 群組
  ![Imgur](https://i.imgur.com/jIAYPby.jpg =x200)




### E. 活動預告: [近期課程列表](https://broadmission.kktix.cc/)

- 【[Azure AI 基礎實作工作坊](https://broadmission.kktix.cc/events/azureai)】

     Azure 雲端擁有超過 100 種服務，各樣工具與基礎設施，能幫助使用者極快速地建置所需專案，並且強大之資料及 AI 服務，能很容易地開發智慧型應用程式。本次課程邀請到 Azure 重量級老師，由淺入深、手把手示範，包含 物體影像辨認、臉部辨認、語音識別、文字分析、情緒分析，並且如何使用 Azure 的機器學習平台，創建工作空間、資料上傳與處理、進行實驗、訓練與評估模型、部署與透過 RESTful API 使用服務等等。

    吸收高手精華、累積專業、學習新技能，很好的練功機會

- 【[K8S學程 : K8S 微服務企業實戰](https://broadmission.kktix.cc/events/k8sserivce)】

    本課程以 Kubernetes 來實作微服務營運管理之實戰教學，大慶講師用第一線企業實戰經驗、分析實作上各種痛點與解決方式，並以真實案例進行經驗分享，加上講解 Kubernetes 各種重點功能與手把手操作。豐富實作與經驗分享的課程，值得您來聽聽。

- 【[給初學者的Python入門課 - 廣宣 x Udemy線上課程](https://www.udemy.com/python-course-beginnners)】

    本線上課，一步步從入門開始並針對核心技術做講解，試著學習 Python 的專案開發，不但讓您競爭力大幅提升、也取得了程式設計的基礎工具能力。

    10名特別限額，請參考。 優惠碼: COURSEOFFER 額滿為止
# Welcome to 廣宣學堂 [BroadMission.org](https://www.facebook.com/broadmission) #
## 【DevOps學程[ CI/CD 實作工作坊](https://broadmission.kktix.cc/events/5218a5a3)】學習資訊共筆系統 ##

### March 30 2019 ###

### A. 教材
- 課前作業: 歡迎先練習與思考，請見[文件](http://bit.ly/2Fzl1NY)最末頁
- [投影片](https://drive.google.com/file/d/1qijSz1sYMi8RLB20Db9q7QBYEi0yPaDu/view?usp=sharing)(已上架)
- [code](https://drive.google.com/file/d/1QT4gYYraTXiPI8dw3j4in96-azB9QPYO/view?usp=sharing)下載

### B. 共筆 (歡迎一同筆記, Markdown)

### C. 事先安裝事項 (亦可參考[文件](http://bit.ly/2Fzl1NY))

- 註冊 gitlab.com / github.com 帳號
    - 請於 gitlab / github 帳號中各建立一個 project，可設為 private
    - 註冊 gitlab [參考網頁](https://blog.csdn.net/fucaijin/article/details/80860112)
    - 註冊 github [參考網頁](https://progressbar.tw/posts/3)

- 本次以虛擬機操作為主，請課前先下載並安裝完畢

    1. 下載安裝 [virtualbox](https://www.virtualbox.org/wiki/Downloads)
        - 安裝步驟[參考網頁](https://zh.wikihow.com/%E5%AE%89%E8%A3%85VirtualBox)

    2. **事先下載 VM 的.ova 檔**  [下載點1](https://chengweichen.com/workshop/CI_CD_Workshop_0330.ova) / [下載點 2](http://bit.ly/2JGey8e)
    3. 設定VM環境 (啟動映像檔前，請先完成設定)
          - 點選匯入的 VM 後選擇"設定值"
          - 選擇後確定以下的設定
          ```
               - 系統>主機板>基本記憶體 --> 1024~2048 (1024至少；2048為佳)
               - 系統>處理器>處理器 --> 1~2 (2為佳)
               - 系統>加速>硬體虛擬化 --> 勾選 "啟用 VT-x/AMD-V"
               - 網路>介面卡1>點開 "進階">連接埠轉送 --> 檢查是否有一項為
                    主機IP=127.0.0.1/ 主機連結埠=2222/ 客體連接埠=22
          ```
          - 點擊 "確定" 離開設定

    4. 啟動 VM (請確認防火牆 2222埠為開放)

    5. 使用 Putty 或 Cmder 或其他 ssh client 登入
        - 請注意登入 127.0.0.1 的埠 **2222**，帳密為 vagrant / vagrant
            - 下載 [Putty](http://www.putty.org/)
            - 下載[Cmder](http://cmder.net)(選擇 Download full)
    6. 確認功能

          - 確認 docker 有否正確運作

            `` 指令: service docker status``
               - 結果應為 active(running)

          - 確認對外網路是否暢通 (請先確認筆電連網)
            `` 指令: sudo apt-get update``
              - 結果在末段應有 "Reading package lists... Done"

    7. 完畢

### D. 回饋與後續服務
- 回饋單[點此填寫](https://goo.gl/forms/RoxUeINjpqboFZm42)
全程參加課程者，可獲得本課程電子證書。

- 加入廣宣學堂 學習 Line 群組
  ![Imgur](https://i.imgur.com/jIAYPby.jpg =x200)




### E. 活動預告: [近期課程列表](https://broadmission.kktix.cc/)

- 【[Azure AI 基礎實作工作坊](https://broadmission.kktix.cc/events/azureai)】

     Azure 雲端擁有超過 100 種服務，各樣工具與基礎設施，能幫助使用者極快速地建置所需專案，並且強大之資料及 AI 服務，能很容易地開發智慧型應用程式。本次課程邀請到 Azure 重量級老師，由淺入深、手把手示範，包含 物體影像辨認、臉部辨認、語音識別、文字分析、情緒分析，並且如何使用 Azure 的機器學習平台，創建工作空間、資料上傳與處理、進行實驗、訓練與評估模型、部署與透過 RESTful API 使用服務等等。

    吸收高手精華、累積專業、學習新技能，很好的練功機會

- 【[K8S學程 : K8S 微服務企業實戰](https://broadmission.kktix.cc/events/k8sserivce)】

    本課程以 Kubernetes 來實作微服務營運管理之實戰教學，大慶講師用第一線企業實戰經驗、分析實作上各種痛點與解決方式，並以真實案例進行經驗分享，加上講解 Kubernetes 各種重點功能與手把手操作。豐富實作與經驗分享的課程，值得您來聽聽。

- 【[給初學者的Python入門課 - 廣宣 x Udemy線上課程](https://www.udemy.com/python-course-beginnners)】

    本線上課，一步步從入門開始並針對核心技術做講解，試著學習 Python 的專案開發，不但讓您競爭力大幅提升、也取得了程式設計的基礎工具能力。

    10名特別限額，請參考。 優惠碼: COURSEOFFER 額滿為止
