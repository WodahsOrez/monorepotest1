pnpm + lerna

npm i -g pnpm lerna

创建pnpm-workspace.yaml

```
packages:
  # 所有 packages/ 下一级目录的包（只有一层）
  - 'packages/*'
```

lerna init

修改lerna.json,添加"npmClient": "pnpm"


lerna version 修改版本

lerna publish 包含lerna version的修改版本然后发布到npm

两者都有很多lifecycle scripts，可以做一些脚本流程操作，如编译之类的


