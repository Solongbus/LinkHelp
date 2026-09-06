# LinkHelp

![Link Help!](img/post.png)

Link Help!（LinkLinkedHelper）可以在多个Excel文件里建立索引关联,免去你打开多张Excel一一比对的烦恼, 方便你快速改表


![Link Help!](img/sample1.png)

> ⚡ **配置自由度高** — 支持最多跨3张表获取数据，灵活应对复杂场景

---



![Link Help!](img/sample2_gif.gif)

> 🎯 **强化Excel原有操作** — 操作更直观，数据切换更高效

---

## 安装

1. **关闭 Excel**（避免文件占用）
2. 双击 [`安装.bat`]
   - 自动检测 Excel 位数（32/64），复制对应 `packed.xll` 到 `%APPDATA%\LinkLinkedHelper`
   - 自动写入 Excel 启动注册表（`HKCU\...\Excel\Options\OPEN*`），无需管理员权限
3. **重启 Excel**，加载项自动生效

> 💡 带参数运行 `安装.bat -RestartExcel` 可安装后自动启动 Excel

---

## 卸载

1. **关闭 Excel**
2. 双击 [`卸载.bat`]
   - 删除注册表启动项与加载痕迹
   - 删除安装目录 `%APPDATA%\LinkLinkedHelper`
3. 重启 Excel 即可完全移除

> ⚠️ 若曾通过「文件 → 选项 → 加载项 → 转到」手动加载过，需在该对话框中取消勾选一次。

