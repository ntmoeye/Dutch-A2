# 🇳🇱 Nederlands A2 單字本

個人荷蘭語 A2 單字學習工具，由 Claude AI 協助建立。

## 功能
- 📚 單字本（搜尋、篩選詞性/分類/狀態）
- ✏️ 測驗（選擇題 + 填空題，四種題型）
- ⭐ 收藏（跨批次保留）
- ✍️ 手動新增單字
- 完整文法資料（動詞變化表、名詞冠詞/複數、形容詞比較級）

## 單字批次
| 檔案 | 內容 | 數量 |
|------|------|------|
| `words/a2-batch-01.js` | 基本動詞、情態、移動、溝通、飲食、名詞、形容詞、副詞 | ~400 |

## 新增單字批次
在 `words/` 資料夾新增 `a2-batch-02.js`，格式同 batch-01，
然後在 `index.html` 的 `<head>` 加入：
```html
<script src="words/a2-batch-02.js"></script>
```

## 部署
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

連結 GitHub repo → Vercel 自動部署，網址：`https://專案名.vercel.app`
