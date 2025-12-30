# fmt_RE_MESH-Noesis-Plugin

> RE Engine 模型/贴图/动画 Noesis 导入导出插件（个人修改版）

⚠️ **学习自用，请勿售卖或商用，风险自负**

📖 [Wiki 文档](https://github.com/AniBullet/fmt_RE_MESH-Noesis-Plugin-BulletS/wiki) ｜ 🔧 [BsKeyTools 远端脚本](https://github.com/AniBullet/BsKeyTools)

---

## ✨ 特性

- 支持 **Monster Hunter Wilds** 正式版动画（`.motlist.992`）
- 完整的动画压缩算法解码支持

## 🎮 支持游戏

| 游戏 | 状态 |
|------|------|
| Resident Evil 2/3/4/7/8 Remake | ✅ |
| Devil May Cry 5 | ✅ |
| Monster Hunter Rise / Wilds | ✅ |
| Street Fighter 6 | ✅ |
| Dragon's Dogma 2 | ✅ |
| ExoPrimal | ✅ |
| Apollo Justice: Ace Attorney Trilogy | ✅ |

## 📦 安装

1. 下载 [Noesis](https://www.richwhitehouse.com/index.php?content=inc_projects.php&showproject=91)
2. 将脚本放入 `[Noesis]/plugins/python/` 目录：
   - `fmt_RE_Motion_Rel.py` - 动画导入脚本
   - `fmt_RE_Motion_Rel_AutoLoad.py` - 自动加载版本（可选）
3. 重启 Noesis

## 💡 使用技巧

- 支持 `.motlist` 动画文件的导入
- 双击 `..` 返回上级目录，或直接粘贴路径跳转
- 可同时加载多个模型并自动合并骨骼
- 使用 `-fbxmultitake` 参数可分离多动画轨道导出

## 🔗 相关链接

- [REEM 使用指南](https://residentevilmodding.boards.net/thread/15374/noesis-maxscript-custom-physics-guide)
- [插件详细说明](https://residentevilmodding.boards.net/thread/13501/exporting-custom-models-dmc5-noesis)

## 🙏 致谢

- [alphazolam](https://github.com/alphazolam/fmt_RE_MESH-Noesis-Plugin) - 原仓库作者
- [Gh0stblade](https://github.com/Gh0stblade) - 初版插件作者
- [RE-Engine-Lib](https://github.com/czastack/RE-Engine-Lib) - 动画压缩算法参考

## 📬 反馈

问题反馈请提交 [Issue](../../issues) 或加入 [Modding Haven](https://discord.gg/acCRqRyUB2)
