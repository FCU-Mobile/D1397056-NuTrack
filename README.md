# NuTrack - 營養追蹤 iOS App

這是一款使用 SwiftUI 和 SwiftData 技術打造的 iOS 營養追蹤應用程式。使用者可以透過它輕鬆記錄每日的飲食，並追蹤三大營養素（碳水化合物、蛋白質、脂肪）的攝取量，以達成個人的健康目標。

## 主要功能

- **使用者系統**：支援使用者登入，並保存個人資料與營養目標。
- **每日儀表板**：以視覺化圖表清晰展示當日的營養攝取進度。
- **快速記錄**：方便地輸入每餐的克數，App 會自動計算總熱量。

## 技術棧

- **介面 (UI)**: SwiftUI
- **資料持久化**: SwiftData
- **程式語言**: Swift 5
- **目標平台**: iOS 17+

## 如何建置與執行

本專案使用標準的 Xcode 環境進行開發。

### 環境需求

- macOS Sonoma 或更新版本
- Xcode 16 或更新版本

### 執行步驟

1.  複製或下載此專案至您的本機電腦。
    ```bash
    git clone <repository-url>
    ```
2.  使用 Xcode 開啟 `NuTrackDemo03.xcodeproj` 檔案。
3.  在 Xcode 的頂部工具列中，選擇一個您想使用的 iOS 模擬器（例如：iPhone 15 Pro）。
4.  點擊「▶︎」按鈕或按下 `Cmd + R` 快速鍵來建置並執行此應用程式。

## 專案結構

專案的程式碼遵循功能導向的原則進行組織，主要目錄結構如下：

- `NuTrackDemo03/`
  - `Models/`: 存放 App 的核心資料模型，使用 SwiftData (`UserProfile`, `MealEntry`) 進行定義。
  - `Views/`: 包含所有的 SwiftUI 視圖元件，例如 `LoginView`, `HomeView` 等。
  - `Services/`: 放置提供特定服務或商業邏輯的類別，例如計算服務。
  - `Extensions/`: 存放擴充既有類型的檔案，例如自定義顏色 `Color+NutritionTheme.swift`。
  - `Assets.xcassets`: 管理 App 的圖示、顏色等靜態資源。

