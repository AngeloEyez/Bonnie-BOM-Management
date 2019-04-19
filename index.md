---
layout: default
title: Bonnie - BOM Management Tool
---
# Bonnie
Bonnie 是一個可以快速批量編輯維護線路中零件property的工具 。


# Features

1. 將 Capture Orcad輸出之 .BOM 檔案中 BOM/Side 欄位的 config 炸開。
2. 快速導入 Allegro 中零件的正背面屬性到線路中。 


# FAQ
### 1. 支援的 Option 欄位
Bonnie 支援以下欄位有 Option，以逗號分隔： 
1. BOM ： 例如 I,I,NI,MP,PROTO
2. Side ： Bonnie會自動更新Side欄位，若有 option，會以 T,T,T,B,B 表示
Bonnie 會確認支援的欄位都含有相同數量的 option。


# Support or Contact
有遇到問題嗎? 請先參考 [FAQ](#faq)

如果仍然有無法解決的問題，歡迎 [提出issue](https://github.com/AngeloEyez/Bonnie-BOM-Management/issues)，但不保證一定能解決 :)
