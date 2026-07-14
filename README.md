# English Core 3000

英语核心词汇学习库，共 **3000** 词，按通用英语词频排序。

## 词表来源

| 部分 | 来源 | 数量 |
|------|------|------|
| 主表 | [NGSL 1.2](https://www.newgeneralservicelist.com/new-general-service-list) 中心词 | 2801 |
| 补充 | NGSL 补充词（星期 / 部分月份 / 数词与序数等） | 51 |
| 补足 | [NAWL](https://www.newgeneralservicelist.com/) 中不在 NGSL 的词 | 148 |

引用（CC BY-SA 4.0）：

> Browne, C., Culligan, B., & Phillips, J. The New General Service List (NGSL) / New Academic Word List (NAWL). https://www.newgeneralservicelist.com

## 约定

- **Rank**：词频序（NGSL → 补充词 → NAWL 补足）
- **CEFR**（频段近似标签，非官方鉴定）：
  - NGSL：1–600 ≈ A1；601–1500 ≈ A2；1501–2400 ≈ B1；2401–2801 ≈ B2
  - 补充词（星期/数词等）：标为 A1
  - NAWL 补足：标为 B2
- 音标：英式 IPA（`IPA_UK`）
- CSV / Excel / Anki：每批 100 词，共 30 个 Part
- Markdown：每批 50 词，共 60 个 Part

## CSV 字段

```text
Rank,Word,CEFR,PartOfSpeech,IPA_UK,Chinese,Collocation,Example_EN,Example_CN,Synonym,Antonym,MemoryTip
```

## 目录

| 路径 | 说明 |
|------|------|
| `csv/Part01.csv` … `Part30.csv` | 分卷词表（每卷 100 词） |
| `excel/English-Core-3000.csv` | 全书合并 CSV |
| `markdown/Part01.md` … `Part60.md` | Markdown 分卷（每卷 50 词） |
| `anki/English-Core-3000.txt` | Anki 导入（Tab 分隔） |

## 分布

| Part | Rank | 说明 |
|------|------|------|
| Part01–06 | 1–600 | 最高频（偏 A1） |
| Part07–15 | 601–1500 | 偏 A2 |
| Part16–24 | 1501–2400 | 偏 B1 |
| Part25–28 | 2401–2801 | NGSL 后段（偏 B2） |
| Part29–30 | 2802–3000 | 补充词 + NAWL 补足 |
