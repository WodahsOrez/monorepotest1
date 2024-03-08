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



