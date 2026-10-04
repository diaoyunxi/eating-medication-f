# 贡献指南

感谢你对 UniHiker M10 智能服药提醒终端的关注！

## 开发环境

- 硬件：UniHiker M10 开发板
- Python 3.10+
- 依赖：unihiker, pinpong, pyttsx3, dfrobot_huskylensv2

```bash
pip install -r requirements.txt
```

## 代码风格

- Python 代码遵循 PEP 8，使用 [ruff](https://github.com/astral-sh/ruff) 检查
- 运行 `ruff check .` 验证代码风格

## 提交 PR 流程

1. Fork 本仓库
2. 创建功能分支：`git checkout -b feature/your-feature`
3. 提交变更：`git commit -m "feat: add your feature"`
4. 推送分支并创建 Pull Request

## 提交信息规范

- `feat:` 新功能
- `fix:` 修复 Bug
- `docs:` 文档变更
- `chore:` 构建/工具变更
