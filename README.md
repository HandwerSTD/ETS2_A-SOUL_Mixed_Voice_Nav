# A-SOUL 五人混搭导航语音包混搭 Alpha 版本

创意工坊地址：[https://steamcommunity.com/...](https://steamcommunity.com/sharedfiles/filedetails/?id=2740270337)

本仓库存放工程文件（不含语音源文件，因为涉及到版权问题），同时 issues 区开放给大家提问题和建议

如果你想使用我自己截取的语音源文件，请使用 Fmod\_Bank\_Tools 自行提取，并在基于此公开发表内容中明显处注明原作者和 A-SOUL 及项目地址，且禁止一切形式的商用

# 问题

[x] 语音未覆盖完全

[x] 语音整体声音偏小

[x] roundabout 系列语音音量需要进一步调整

[] roundabout 系列语音需要更好的源文件

[] 部分语音仍旧词不达意

# 语音使用说明

ABCDE 为成员代号，表格空缺处为否或同上

需要调整为“是”的代表我也忍受不了，为“尽量”的代表我个人能接受

`compound ... and then` 系列语音例：“靠左（`compound`），然后使用左边的出口（`and then`）”

| 文件前缀             | （参考）语音命令                     | 语音使用 | 是否需要调整 | 调整备注        | 是否需要随机化 | 是否需要提取人声及原因 |
| -------------------- | ------------------------------------ | -------- | ------------ | --------------- | -------------- | ---------------------- |
| turn_left            | "左转。"                             | A        |              |                 |                |                        |
| turn_right           | "右转。"                             | A        |              |                 |                |                        |
| keep_left            | "靠左行驶。"                         | A        |              |                 |                |                        |
| keep_right           | "靠右行驶。"                         | A        |              |                 |                |                        |
| exit_left            | "向左前方行驶。"                     | E        | 是           | 拼接            |                |                        |
| exit_right           | "向右前方行驶。"                     | E        | 是           | 拼接            |                |                        |
| go_straight          | "直行。"                             | A        | 尽量         |                 |                |                        |
| roundabout_1         | "在环形交叉路口，从第一个出口驶出。" | 统一为A  | 是           | 拼接            |                |                        |
| roundabout_2         | "在环形交叉路口，从第二个出口驶出。" |          | 是           | 拼接            |                |                        |
| roundabout_3         | "在环形交叉路口，从第三个出口驶出。" |          | 是           | 拼接            |                |                        |
| roundabout_4         | "在环形交叉路口，从第四个出口驶出。" |          | 是           | 拼接            |                |                        |
| roundabout_5         | "在环形交叉路口，从第五个出口驶出。" |          | 是           | 拼接            |                |                        |
| roundabout_6         | "在环形交叉路口，从第六个出口驶出。" |          | 是           | 拼接            |                |                        |
| exit_now             | "驶出环岛。"                         | E        | 尽量         | 声线            |                |                        |
| prepare_turn_left    | "即将左转。"                         | AA       | 是           | 拼接            |                |                        |
| prepare_turn_right   | "即将右转。"                         | AA       | 是           | 拼接            |                |                        |
| prepare_exit_left    | "即将向左前方行驶。"                 | AE       | 是           | 拼接            |                |                        |
| prepare_exit_right   | "即将向右前方行驶。"                 | AE       | 是           | 拼接            |                |                        |
| compound_turn_left   | "左转..."                            | A        |              |                 |                |                        |
| compound_turn_right  | "右转..."                            | A        |              |                 |                |                        |
| compound_keep_left   | "靠左行驶..."                        | E        |              |                 |                |                        |
| compound_keep_right  | "靠右行驶..."                        | A        |              |                 |                |                        |
| compound_exit_left   | "左转..."                            | E        |              |                 |                |                        |
| compound_exit_right  | "右转..."                            | E        |              |                 |                |                        |
| compound_go_straight | "直行..."                            | A        |              |                 |                |                        |
| and_then_turn_left   | "...然后左转。"                      | A        |              | 词不达意 + 拼接 |                |                        |
| and_then_turn_right  | "...然后右转。"                      | A        |              | 剩下 6 个皆是   |                |                        |
| and_then_keep_left   | "...然后靠左行驶。"                  | A        |              |                 |                |                        |
| and_then_keep_right  | "...然后靠右行驶。"                  | A        |              |                 |                |                        |
| and_then_exit_left   | "...然后向左前方行驶。"              | E        |              |                 |                |                        |
| and_then_exit_right  | "...然后向右前方行驶。"              | E        |              |                 |                |                        |
| and_then_go_straight | "...然后继续直行。"                  | A        |              |                 |                |                        |
| start                | 例如，"好吧，我们开始吧！"           | ABCDE    |              |                 | 是             | 音乐                   |
| finsh                | 例如，"我们在这里结束吧！"           | B        | 尽量         | 词不达意        |                |                        |
| recomputing          | 例如，"重新计算中..."                | D        | 尽量         | 词不达意        |                | 音乐                   |
| u_turn               | "掉头。"                             | DA       | 尽量         | 词不达意        |                |                        |
| speed_warning        | "注意，您已超速。"                   | A        | 尽量         |                 |                |                        |

# 感谢

感谢 A-SOUL Database 提供优秀的工具，极大简化了搜寻语音的过程

感谢 [知乎专栏](https://zhuanlan.zhihu.com/p/462410193) 提供了制作教程

# 版权

本仓库使用 Mozilla Public License 2.0
