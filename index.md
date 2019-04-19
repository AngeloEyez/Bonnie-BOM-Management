---
layout: default
title: Bonnie - BOM Management Tool
---
# Bonnie
Bonnie 是一個可以快速批量編輯維護線路中零件property的工具 。


# Features

1. 將 OEM/ODM BOM 轉為 Matrix BOM 格式. 


# FAQ
### - OEM/ODM BOM格式需求
Matriz會確認輸入BOM的格式，以確保可以取得正確資訊，輸入的 OEM/ODM BOM 必須滿足以下條件： 
1. 包含這些 sheets，大小寫必須符合
 - ALL
 - SMD
 - PTH
 - BOTTOM
 - MP
2. 每個頁面不論有沒有 component，都要包含表頭

### - [Error:] BOM Creat fail (null bomkey)
請確認專案名稱正確，或者關閉記憶體中所有 Excel 程序後再重試

### - Something wrong with EXCEL operation, please close all EXCEL process in momory and try again.
請用工作管理員關閉所有記憶體中的 Excel, 若還是一樣的錯誤，可以嘗試重啟後再執行 Matriz


# Support or Contact
有遇到問題嗎? 請先參考 [FAQ](#faq)

如果仍然有無法解決的問題，歡迎 [提出issue](https://github.com/AngeloEyez/Bonnie-BOM-Management/issues)，但不保證一定能解決 :)
