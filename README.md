Docker spring maraidb RESTAPI
spring簡易RESTAPI程式碼範例-docker

## 教學參考來源:

## 專案資料夾與檔案格式說明
| 型態 | 名稱 | 說明 |
| --- | --- | --- |
| 資料夾 | app | 專案主要程式碼 |
| 資料夾 | iiidevops | devops系統使用 |
| 檔案 | Dockerfile.local | 本地端部屬使用 |
| 檔案 | docker-compose.yaml | 本地端快速部屬使用 |
| 檔案 | postman_collection_local.json | 本地端快速部屬使用 |
| 檔案 | openapi_local.yaml | 本地端快速部屬使用 |
| 檔案 | newman-report.xml | (自動產生)Postman collection本地端測試報告 |
| 檔案 | owasp-report.md | (自動產生)owasp ZAP-本地端掃描測試報告 |

## (local)本地環境隔離快速專案部屬(隨機PORT) + Postman-collection(newman)自動測試
需安裝Docker, 若在Linux環境需額外手動安裝docker-compose, 部屬結果與UI相同
``` 
docker-compose up -d --build 
```
部屬包含flask網頁 + Postman-collection(newman)自動測試, 自動測試報告結果會自動產生在`app/newman-report.xml`, 驗證後即可上傳程式碼
### 查看部屬結果 `docker-compose ps`

## 


JDK15
