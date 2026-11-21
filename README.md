# 创意作品评审指标与最终奖项解释

用于核对虚构赛事评审轮次、评审覆盖和奖项记录，不作为真实赛事结果。

`fixtures/records.json` 保存合成演练记录，字段说明见 `docs/数据格式.md`。

需要 Python 3.9 或更新版本，无第三方依赖。运行资料基线检查：

```sh
python3 -m unittest discover -s tests -v
```
项目目前只提供资料读取和结构检查。
