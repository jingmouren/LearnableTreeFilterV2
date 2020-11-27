|name|about|title|
|:-:|:-:|:-:|
|Unexpected behaviors|Run into unexpected behaviors when using cvpods|Please read & provide the following|

---

If you do not know the root cause of the problem, and wish someone to help you, please
post according to this template:

## Instructions To Reproduce the Issue:

1. what code you wrote or what changes you made (`git diff`)
```
<put diff or code here>
```
2. what exact command you run:
3. what you observed (including __full logs__):
```
<put logs here>
```
4. please simplify the steps as much as possible so they do not require additional resources to
	 run, such as a private dataset.
   See https://stackoverflow.com/help/minimal-reproducible-example for how to ask good questions.

## Expected behavior:

If there are no obvious error in "what you observed" provided above,
please tell us the expected behavior.

If you expect the model to converge / work better, note that we do not give suggestions
on how to train a new model.
Only in one of the two conditions we will help with it:
(1) You're unable to reproduce the results in cvpods model zoo.
(2) It indicates a cvpods bug.

## Environment:

Provide your environment information using the following command:
```
git clone git@git-core.megvii-inc.com:zhubenjin/cvpods.git && cd cvpods && python cvpods/utils/env/collect_env.py
```

If your issue looks like an installation issue / environment issue,
please first try to solve it with the instructions in
https://luoshu.iap.wh-a.brainpp.cn/docs/cvpods/en/latest/
