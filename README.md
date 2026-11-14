# 无边缘传送

- [无边缘传送.zip](02_build/%E6%88%90%E5%93%81MOD/%E6%97%A0%E8%BE%B9%E7%BC%98%E4%BC%A0%E9%80%81/%E6%97%A0%E8%BE%B9%E7%BC%98%E4%BC%A0%E9%80%81.zip)

[完整源码与功能说明](01_plugins/no_area_move/)。包内提供安装说明；安装包按原样保存。

构建：克隆到纯 ASCII 路径，准备 Rust nightly、rust-src、cargo-mhgu-forge 1.5.0、ARM GNU Toolchain 和 Python 3。进入本目录后运行：

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File .\06_tools\build.ps1 -Project no_area_move
python .\06_tools\patches\pack_no_area_move.py
```

2026-11-14 上传已有安装包与当前源码快照；ZIP 完整性及包内 NRO 重定位检查通过，本次未重新编译或进行游戏测试。Eden / Switch 需要另装兼容的 Forge 前置；源码快照不保证与历史二进制逐字节复现。
