# FiveAges Arena robots

Arena `model_params.yaml` registrations for robots in [fiveages-sim/robot_usds](https://github.com/fiveages-sim/robot_usds).

A USD in `robot_usds` is not enough to spawn a robot in Arena. Each name used as `robot:=...` needs a folder here:

```text
arena_robots/robots/<Name>/model_params.yaml
```

## Registered now

| `robot:=` | USD |
| --- | --- |
| `FiveAges_W2` | `deps/robot_usds/humanoid/FiveAges_W2` ([fa-w2-usds](https://github.com/fiveages-sim/fa-w2-usds)) |

To add another org robot, copy `FiveAges_W2/model_params.yaml`, point `usd_redirect` at that robot's USD, and fill footprint, base frame, lidar topic, and camera prim.
