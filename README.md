<div align="center">
  <img src="assets/banner.svg" width="100%" alt="MrHao — Android Reverse Engineering · Embedded / CAN · UE & IL2CPP"/>
</div>

<div align="center">

![Android](https://img.shields.io/badge/Android-RE-3DDC84?style=flat-square&logo=android&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-P4%20%2F%20C5-E7352C?style=flat-square&logo=espressif&logoColor=white)
![CAN](https://img.shields.io/badge/CAN%20Bus-TWAI-0ea5e9?style=flat-square)
![UE](https://img.shields.io/badge/Unreal-IL2CPP-818cf8?style=flat-square)

</div>

## 关于我

- 🔬 **Android 逆向 / 注入**：IL2CPP、Unreal Engine Dumper、Zygote 注入、自定义 linker、JNI trace
- 🚗 **嵌入式 / 车载总线**：ESP32-P4 / C5 上的 Tesla CAN 工具，TWAI 多路、注入时序、TLSSC / R79 / Nag
- 🧰 **工具链**：IDA / Ghidra 静态分析，Smali 重打包，Python 自动化；坚持"静态优先、产物可复现"
- 🧪 只在自己的车、封闭场地和台架上验证；不碰公共道路

## 精选项目

| 项目 | 说明 | 栈 |
|---|---|---|
| **[P4can-No-Reboot](https://github.com/MrHao12333/P4can-No-Reboot)** | Tesla CAN 固件：缓存补丁后的 `0x331` 并在车机读配置前主动补发，免去车机每轮上电重启 | `C` `CAN` |
| **[P4can-universal-unlock](https://github.com/MrHao12333/P4can-universal-unlock)** | Model 3/Y 三路 CAN 工具固件（Nag / R79 / 召唤 / TLSSC） | `C` `ESP32-P4` |
| **[p4can-zh-ios](https://github.com/MrHao12333/p4can-zh-ios)** | P4-CAN 中英双语汉化补丁 + iOS 外壳 App | `JavaScript` |
| **[Il2CppDumper-GUI-CODM](https://github.com/MrHao12333/Il2CppDumper-GUI-CODM)** | 针对 CODM 优化的 Il2CppDumper 图形界面（Android / iOS） | `C#` |
| **[AndUEProber](https://github.com/MrHao12333/AndUEProber)** | 运行时自动探测 UE 反射结构体成员偏移，输出给 UEDumper 使用 | `C++` |
| **[Android-FuckDrmID](https://github.com/MrHao12333/Android-FuckDrmID)** | 注入 `drm-service.widevine` 修改 Widevine ID（设备黑名单场景） | `C++` |
| **[TInjector_Symbi](https://github.com/MrHao12333/TInjector_Symbi)** | 更稳定的 Zygote 劫持，在 App 启动前注入 so | `C++` |
| **[fake-linker](https://github.com/MrHao12333/fake-linker)** | 改造 Android linker，提供模块加载与函数 hook 能力 | `C++` |

## 技术栈

<div align="center">

![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

![IDA](https://img.shields.io/badge/IDA%20Pro-static-1f2937?style=flat-square)
![Ghidra](https://img.shields.io/badge/Ghidra-static-1f2937?style=flat-square)
![Smali](https://img.shields.io/badge/Smali-repack-1f2937?style=flat-square)
![Arduino](https://img.shields.io/badge/Arduino-ESP32-00979D?style=flat-square&logo=arduino&logoColor=white)

</div>

## GitHub 统计

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MrHao12333&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="GitHub Stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MrHao12333&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=MrHao12333&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</div>

## 最近在折腾

- **C5can**（private）：把 P4can 固件移植到 ESP32-C5，双路 TWAI + 原生 Wi-Fi + TLSSC 免重启
- Android 侧继续做 UE / IL2CPP 的偏移探测与稳定注入

<div align="center">
  <sub>「静态优先，产物可复现」— 所有研究仅用于自有设备与封闭场地</sub>
</div>
