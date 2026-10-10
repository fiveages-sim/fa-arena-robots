# FiveAges Arena 机器人注册

给 Arena 用的 `model_params.yaml`。USD 资产在 [fiveages-sim/robot_usds](https://github.com/fiveages-sim/robot_usds)。

只有 USD 还不能 `robot:=某名字` 生成。每个名字都要有：

```text
arena_robots/robots/<名字>/model_params.yaml
```

## 当前已注册

| `robot:=` | USD |
| --- | --- |
| `FiveAges_W2` | `deps/robot_usds/humanoid/FiveAges_W2`（[fa-w2-usds](https://github.com/fiveages-sim/fa-w2-usds)） |

要加组织里的其他机器人：复制 `FiveAges_W2/model_params.yaml`，改 `usd_redirect`、足迹、底盘坐标系、激光话题和相机 prim。
