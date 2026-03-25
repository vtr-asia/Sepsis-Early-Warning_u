# Sepsis-Early-Warning_u
這是一套基於 FHIR 標準的敗血症早期警示網頁應用，透過 SMART on FHIR 串接衛福部 THAS 平台，即時監測病患體溫、呼吸速率、收縮壓與乳酸值，自動計算 qSOFA 分數（≥2 分即高風險），以紅色警示、脈動動畫與 CDS Hooks 建議（立即血液培養＋廣效抗生素）提示臨床人員，支援模擬 5 分鐘週期監測與 FHIR Bundle 上傳（Patient＋Encounter＋Observation），目前為單病患前端原型，適合展示、教學或作為醫院敗血症快速反應系統的開發起點。
