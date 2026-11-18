# 诗词活动参与统计的跨期安全发布

本项目保存参与统计发布分析所需的合成去重人群、分组政策、申请和历史公开数字，均使用 UTF-8 CSV。空字段表示记录未提供。

## 数据

- `data/population.csv`：统计期去重参与者及交叠标签。
- `data/policies.csv`：审核范围、人数阈值及公开边界。
- `data/requests.csv`：收件方、统计期及分组申请。
- `data/released.csv`：已发布的历史数字。

## 环境与验证

需要 Python 3.11 或更新版本；项目仅使用 Python 标准库。可用 `python3 -m unittest discover -s tests -v` 检查 CSV 结构与本地资料完整性。
