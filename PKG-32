# PKG-300002-BRANCH

## Description
> MID 站台設定 API

## API Document

> 站台列表

| 項目                      | 內容                       | 說明                                  |
|---------------------------|----------------------------|---------------------------------------|
| <b>路徑</b>               | branch/config/get-branch-list         |                                       |
| <b>方法</b>               | GET                          |                                       |
| <b>權限</b>               | 檢視                         |                                       |
| <b>參數</b>               | 參照 branch/setting/get-list |                                       |
|<b>>備註</b>               | 非全域帳號不可操作           |                                       |

> 檢視

| 項目                      | 內容                       | 說明                                  |
|---------------------------|----------------------------|---------------------------------------|
| <b>路徑</b>               | branch/config/show         |                                      |
| <b>方法</b>               | GET                        |                                       |
| <b>權限</b>               | 檢視                       |                                       |
| <b>參數</b>               |                            |                                       |
|                           | p32_bch_guid               | 站台GUID(全域帳號須帶入)              |
|<b>>備註</b>               | 非全域帳號僅限站長可操作   |                                       |


> 編輯程序

| 項目                      | 內容                       | 說明                                  |
|---------------------------|----------------------------|---------------------------------------|
| <b>路徑</b>               | branch/config/do-set      |                                       |
| <b>方法</b>               | POST                       |                                       |
| <b>權限</b>               | 編輯                       |                                       |
| <b>參數</b>               |                            |                                       |
|                           | p32_bch_guid               | 站台GUID(全域帳號須帶入)              |
|                           | handicap[{球種GUID(scy_guid)}]=盤口GUID(bho_guid)| 站台ABC盤      |
|                           | sport_play[]=玩法 GUID(spy_guid)| 站台玩法                         |
|                           | sport_game[]=場次 GUID(sge_guid)| 站台場次                         |
|                           | p78_pfc_guid|金流GUID      | 設定站台金流 |
|                           | p79_tmc_guid|簡訊GUID      | 設定站台簡訊 |
|                           | enable_balls[]=球種GUID (scy_guid)| 站台啟用球種                   |
|                           | service_url| 客服系統網址                   |
|                           | video_api_key | 影城api key                   |
|                           | video_api_url | 影城api 網址                   |
|                           | forum_api_key | 論壇api key                   |
|                           | forum_api_url | 論壇api 網址                   |
|                           | forum_platform | 論壇api識別代號                   |

> 檢視站台啟用球類

| 項目                      | 內容                       | 說明                                  |
|---------------------------|----------------------------|---------------------------------------|
| <b>路徑</b>               | branch/config/showSportCategorySetting      |                                       |
| <b>方法</b>               | POST                       |                                       |
| <b>權限</b>               | 編輯                       |                                       |
| <b>參數</b>               |                            |                                       |
|                           | sbl_guid               | 球種類型GUID              |
|                           | bch_guid   |    站台GUID |


> 設定站台啟用/關閉球類

| 項目                      | 內容                       | 說明                                  |
|---------------------------|----------------------------|---------------------------------------|
| <b>路徑</b>               | branch/config/doSetDisableSportCategory      |                                       |
| <b>方法</b>               | POST                       |                                       |
| <b>權限</b>               | 編輯                       |                                       |
| <b>參數</b>               |                            |                                       |
|                           | disable [0=>['scy_guid'=>{球種GUID(scy_guid)},'sge_guid'=>'{賽事GUID(sge_guid)}','spy_guid'=>{玩法GUID(spy_guid)}]]  |     |
|                           | bch_guid   |    站台GUID |

> 檢視站台盤口設定

| 項目                      | 內容                       | 說明                                  |
|---------------------------|----------------------------|---------------------------------------|
| <b>路徑</b>               | branch/config/showBchHandicapSetting      |                                       |
| <b>方法</b>               | POST                       |                                       |
| <b>權限</b>               | 編輯                       |                                       |
| <b>參數</b>               |                            |                                       |
|                           | sbl_guid               | 球種類型GUID              |
|                           | bch_guid   |    站台GUID |

> 編輯站台盤口設定

| 項目                      | 內容                       | 說明                                  |
|---------------------------|----------------------------|---------------------------------------|
| <b>路徑</b>               | branch/config/doSetBchHandicapConfig      |                                       |
| <b>方法</b>               | POST                       |                                       |
| <b>權限</b>               | 編輯                       |                                       |
| <b>參數</b>               |                            |                                       |
|                           | sbl_guid(string)             |     球種類型GUID|
|                           | handicap[{球種GUID(scy_guid)}]=盤口GUID(bho_guid)             |   	站台ABC盤   |  
|                           | bch_guid   |    站台GUID |



#站台盤口或球種設定
| 代碼   | 說明 | 備註 |
| ------ | -------------------------------- | ------ |
| 0 | OK | - |
| 320201 | 傳遞參數錯誤 | - |


