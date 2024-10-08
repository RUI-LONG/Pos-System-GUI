# Raspberry Pi POS System

## Overview
這是一個為 Raspberry Pi 開發的銷售點系統 (POS)，使用 Python 的 `tkinter` 庫進行構建。該系統旨在提供簡單的用戶界面來管理商品、處理付款並生成收據。系統中包含自定義的按鈕、標籤和框架，支持無縫結賬流程。

https://github.com/user-attachments/assets/d3df38ee-a41d-411c-9835-c0eeeca8f488


## Features
- **類別選擇**：使用單選按鈕來選擇不同的商品類別。
- **商品列表**：顯示所選類別中的可用商品。
- **收據管理**：將商品添加到收據中，可調整數量並計算總額。
- **計算器**：簡單的計算器可執行基本的算術操作，包括增加和減少商品。
- **結帳系統**：處理付款並計算找零。
- **清除收據**：清除當前收據的選項。
- **退出**：簡單的退出按鈕用於關閉應用程式。

## Components
1. **自定義按鈕**： 
    - 用於添加、清除和移除商品的各種按鈕。
    - 控制系統的退出和清除收據按鈕。
2. **自定義標籤**： 
    - 用於顯示數量、總金額、現金輸入和找零的標籤。
3. **自定義變量**： 
    - 動態更新的變量，用於處理數量、總金額和找零。
4. **自定義樹狀檢視**： 
    - 以結構化的方式顯示收據，包括商品編號、名稱、數量和小計的列。
5. **計算器**： 
    - 基於網格的簡單計算器，用於基本的POS操作。
6. **收銀系統**： 
    - 處理付款並提供即時找零計算。
7. **商品管理**： 
    - 按類別組織商品，允許選擇商品及其自訂選項。
8. **收據管理**： 
    - 顯示和管理收據，包括清除和移除商品的功能。
