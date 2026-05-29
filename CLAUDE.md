# 2026药师技能大赛题库

在线刷题HTML工具。主文件：`index.html`，自包含801道题目。

## 部署
- 平台：GitHub Pages
- 仓库：`l1065521312-creator/yaoshi-tiku`
- 公开链接：https://l1065521312-creator.github.io/yaoshi-tiku/
- SSH推送：`git@github.com:l1065521312-creator/yaoshi-tiku.git`
- SSH私钥：`C:\Users\y\.ssh\yaoshi_deploy`

## 更新推送命令
```
cd "C:\Users\y\Desktop\题库" && GIT_SSH_COMMAND="ssh -i /c/Users/y/.ssh/yaoshi_deploy -o StrictHostKeyChecking=no" git push origin main
```

## 功能
- 随机50题 / 随机100题 / 按顺序答全部
- 判断题：正确/错误按钮
- 单选题：A-G单选
- 多选题：A-G多选+确认按钮
- 填空题：文本输入+确认按钮
- 答错显示正确答案，手机电脑全适配
