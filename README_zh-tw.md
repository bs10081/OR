# 作業研究所使用到的 Gurobi Jupyter Notebook

[English(US)](README.md)

此儲存庫包含使用 Gurobi 解決線性規劃問題的 Jupyter Notebook 範例和教學材料。這些 Notebook 範例來自不同的課程章節，旨在幫助學習者更深入了解如何使用 Gurobi 解決各種優化問題，包括線性規劃 (LP) 和混合整數規劃 (MIP)。

## 內容簡介

此儲存庫目前包含以下章節內容（均有繁體中文（臺灣）版本）：

### 章節列表

1. **Chap3 - Wyndor Glass Co. 使用 Gurobi 解決線性規劃問題**

- Notebook: `Chap3/wyndor_glass_co_uses_gurobi_for_linear_programming_problems.ipynb`

- 內容：介紹如何應用 Gurobi 解決經典的 Wyndor Glass Company 線性規劃問題。

2. **Chap3 - 放射治療優化問題**

- Notebook: `Chap3/Radiation Therapy Treatment Optimization using Gurobi.ipynb`

- 內容：模擬放射治療中的優化問題，旨在最大限度減少對健康組織的影響，同時確保腫瘤部位獲得足夠的放射量。

## 使用方法

1. **Clone 此儲存庫**

```bash
git clone https://github.com/bs10081/OR.git
```

2. **安裝必要的 Python 套件**

- Gurobi 求解器：若尚未安裝 Gurobi，請依照 [官方網站](https://www.gurobi.com) 的指示進行安裝。

- 其他依賴套件可從 `requirements.txt` 檔案中列出的依賴項目進行安裝：

```bash
pip install -r requirements.txt
```

3. **執行 Notebook**

在命令列中導航至 Notebook 目錄，並啟動 Jupyter Notebook：

```bash
jupyter notebook
```

接著選擇相應的 Notebook 進行學習與操作。

## 未來更新

此儲存庫將定期新增更多章節和範例，以涵蓋更廣泛的優化問題應用範疇。每個新章節將有對應的 Jupyter Notebook 檔案，解釋其應用背景與實作步驟。

未來可能的更新內容包括：

- 更多線性規劃和混合整數規劃的實際應用範例

- 使用 Gurobi 解決大型優化問題

- 其他優化算法的比較與應用

## 貢獻指南

如果您想對此儲存庫做出貢獻，歡迎提交 pull request。請先 fork 此專案，並確保所有 Notebook 正常執行後再提交。

## 相關資源

- [Gurobi 官方文件](https://www.gurobi.com/documentation/)

- [Jupyter Notebook 官方文件](https://jupyter.org/documentation)

## 授權

此儲存庫的內容遵循 [MIT License](LICENSE)。
