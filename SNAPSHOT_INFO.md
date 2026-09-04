# Car_real_copy 独立源码快照

保存日期：2026-09-04。

- 来源：机器人 `/home/test/Car_real_copy` 当前工作树，而非 `car_real_copy_zhenghang`。
- 原本地 Git 基线：`52348412d7dfa7ade879fbea67a76c0c1367d19c`。本快照包含基线之后当前工作树中的既有修改，独立仓库从本次快照开始记录历史。
- 保留现有 README、源码、启动脚本、配置及地图；没有修改机器人源代码或运行状态。
- `SNAPSHOT_SHA256SUMS` 记录399个源文件校验值，已与机器人对应文件逐一核对。
- 不包含原 `.git` 历史、`build/`、`install/`、日志、运行状态、录像、密钥或备份压缩包。不能当作可直接刷机的系统镜像。
- 恢复时在独立目录克隆，先执行 `sha256sum -c SNAPSHOT_SHA256SUMS`，再按原 README 准备 ROS Humble 依赖并构建。不要在机器人运行时直接覆盖项目。
- 对应千问项目：https://github.com/AdjacentGarden/qwen_robot ，同步快照标签为 `snapshot-20260904-qwen-carrealcopy`。

原代码保持原有格式；部分文件有 CRLF 或末尾空格，本次不进行格式化。
