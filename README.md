# 三根电阻TC264开源库

**重要提醒**

- 请在开始编译或烧录前关闭所有杀毒软件，以免干扰编译工具或烧录程序。
- 编译前请先解压英飞凌芯片库：位于 `Seekfree_TC264_DualCam_Opensource_Library/libraries/infineon_libraries.zip`。

## 快速开始

1. 解压仓库到本地工作目录并解压英飞凌芯片库。
2. 使用支持的 IDE/编译器打开 Debug 下的工程（示例：TASKING），或按项目说明使用 makefile 构建。
3. 按需调整推荐 IO 分配与工程配置（见 code/ 下的说明文件）。
4. 将固件烧写到目标板并进行调试。

## 目录说明（简要）

- `code/`：工程与源码说明文件。
- `Debug/`：编译工程文件、makefile 与调试配置。
- `libraries/`：第三方及项目依赖库（包含 infineon_libraries、zf_common、zf_components 等）。
- `user/`：用户应用入口与中断配置（如 cpu0_main.c、isr.c 等）。

## 其他

- 更多细节请参阅仓库内对应的说明文档与注释文件。
- 许可证请见仓库根目录的 LICENSE 文件。

如果你希望我进一步根据项目具体内容补充使用示例或英文版 README，我可以继续完善。