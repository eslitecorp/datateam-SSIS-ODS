# datateam-SSIS-ODS
#SSIS-Project
===

##Pipeline
---
資料夾包含了STAGE專案為prestage to stage 和ODS專案為stage to ods 兩階段的封裝檔，因 STAGE_MY 不在此次範圍可以略過  
- ME  
- OMI  
- FS  
- ESAPP  
- HKAPP  
- POSNEC  
- DW  
- TEAM  
- APP  
- EC  
- SMS  
- ECS2 (資料是執行 python script 取檔下來)
- SAP  
- LMS  
- LMSNS 
---
##願望清單
1. 監控告警平台:資料未下檔、重複下檔、匯入資料規格有誤、轉換錯誤、Pkey重複
2. 重轉優化:各 pipeline 從 stage to ods 會有關聯性，資料在排程時間點未上傳
3. 資料血緣、資料字典
4. 現階段 log 檔會有三張表，能整合成一張直觀的 LOG 表
5. 整合發送 EMAIL 錯誤清單
6. 資料存回 GCS
7. 資料驗證
8. 權限 Google Cloud 的 IAM

