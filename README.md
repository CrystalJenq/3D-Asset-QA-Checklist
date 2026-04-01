# 3D Asset QA Checklist

Digital Twin 數位資產品質檢查表 — 互動式 React 元件

## 功能

- **三大檢查分類**：模型 (Mesh)、貼圖 (Texture)、材質球 (Material)，共 40+ 個項目
- **通過 / 不通過**：雙按鈕切換，再點一次可取消
- **良率計算**：即時顯示總良率與各分類良率，含等級評定（優良 / 待改善 / 不合格）
- **關鍵項目標記**：黃色「關鍵」標籤標示重點檢查項
- **篩選功能**：全部 / 未檢查 / 關鍵項目 / 不通過
- **貼圖尺寸子選項**：可勾選 512 / 1024 / 2048 / 4096
- **備註功能**：每個項目可加註檢查備註
- **匯出報告**：生成文字報告並複製到剪貼簿

## 檢查規範涵蓋

### 模型 (Mesh)
- 拓撲結構、流行幾何、面數密度、法線一致性
- UV 分佈規則、LOD 系統、命名規則、清理作業

### 貼圖 (Texture)
- 貼圖規劃、PBR 表現、貼圖整合 ORM

### 材質球 (Material)
- 材質球數量/命名管控、Alpha 透明材質、Overdraw 管控

## Tech Stack

- React (JSX)
- Tailwind CSS variables
- Google Fonts: DM Sans, Noto Sans TC, JetBrains Mono
