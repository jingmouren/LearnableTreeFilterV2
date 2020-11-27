|name|about|
|:-:|:-:|
|🐛 Bugs|报告cvpods中的bug|

---

如果能确定是cvpack中某个具体API的bug, 请使用该模板.

否则, 请使用[Unexpected behaviors](https://git-core.megvii-inc.com/zhubenjin/cvpods/issues/new) issue template.

## 复现bug的步骤

1. cvpods和cvpods_playground的commit id

   ||branch|commit id|
   |:-:|:-:|:-:|
   |cvpods|`cd path/to/cvpods; git rev-parse --abbrev-ref HEAD`|`cd path/to/cvpods; git rev-parse HEAD`|
   |cvpods_playground|`cd path/to/cvpods_playground; git rev-parse HEAD`|`cd path/to/cvpods_playground; git rev-parse HEAD`|
2. 复现的具体环境和步骤, 包括使用的config和模型, 修改了什么, 使用了什么命令(`git diff`)

3. 观察到的现象 (包括 **log** 和 **Traceback**):
```
<put logs here>
```

## 期望的结果

请告诉我们你期望的结果

## 环境

需要的话, 在此处提供运行环境

运行环境可使用如下命令获取
```
cd cvpods && python cvpods/utils/env/collect_env.py
```

如果是环境或安装问题, 请先尝试通过文档中的指示解决
https://luoshu.iap.wh-a.brainpp.cn/docs/cvpods/en/latest/
