VisualSampler v1.0.1 FREE
for SP-404MK2
============================================================

Sample Your City. Remix Your Reality.

【1. 什么是 VisualSampler】

VisualSampler 是一款面向 macOS 的视觉采样器，
可通过 Roland SP-404MKII 演奏静态图像。

像采样音乐一样，采样城市风景和日常照片。
通过 16 个 PAD 切换图像，享受实时视觉创作。

放入喜欢的照片，轻敲 PAD 即可。
让你的日常生活成为视觉采样素材。

【2. 运行环境】

・支持的操作系统：macOS（内置运行环境的最低要求为 11.0；尚未完成各 OS 版本的运行验证）
・支持的 Mac：搭载 Apple Silicon 的 Mac（M 系列）
・控制器：Roland SP-404MKII
・连接方式：USB MIDI
・基于 Processing 制作
・发布的应用内含 Java 运行时（通常无需另行安装）

※本发布版本仅适用于搭载 Apple Silicon 的 Mac。不支持 Intel Mac 和 Windows。

【3. 应用的放置与启动】

1. 解压发布 ZIP 文件。
2. 使用 USB 将 SP-404MKII 连接到 Mac，并开启设备电源。
3. 检查 SP-404MKII 的 MIDI 设置（参见下文）。
4. 启动 VisualSampler.app。
5. 按下 SP-404MKII 的 PAD 切换图像。

SP-404MKII 必需的 MIDI 设置：
  SHIFT + PAD 13（UTILITY）→ SYSTEM → MIDI
  ・MIDI Mode：A
  ・PAD Note Out：ON

※这两项设置是操作 VisualSampler 的必要条件。
  如果 MIDI Mode 设为 B，PAD 的 MIDI 音符／通道分配会与
  VisualSampler 预期的分配不同，导致无法正常操作。
  如果 PAD Note Out 设为 OFF，PAD 操作将不会发送 MIDI 信号。
※操作 VisualSampler 时，MIDI EXT Src（TOGGLE / GATE / THROUGH）
  无需设为某个特定选项。

建议将 Banks 与 VisualSampler.app 放在同一目录，便于管理。
如果启动时要求指定 Banks 的位置，请选择包含 BankA 和 BankB 的上级“Banks”文件夹。
所选位置会被保存，并用于后续启动。
如果保存的位置不再可用，会再次显示文件夹选择窗口。
取消选择或选错文件夹后，可在应用窗口中按 R 键重新选择。
Banks/BankA 和 Banks/BankB 中都应备齐编号 01～16 的图像。

正确的目录结构示例：

VisualSampler_v1.0.1_macOS_AppleSilicon/
├── VisualSampler.app
├── Banks/
│   ├── BankA/
│   │   ├── 01.jpg
│   │   ├── 02.jpg
│   │   └── ... 16.jpg
│   └── BankB/
│       ├── 01.jpg
│       ├── 02.jpg
│       └── ... 16.jpg
├── README_JP.txt
├── README_EN.txt
├── README_ES.txt
├── README_ZH_CN.txt
└── README_KO.txt

※文件夹名称为“Banks”“BankA”“BankB”。
  请勿改为“BANK_A”“BANK_B”等名称。
※请勿将 Banks 移入 .app 内部。
【首次启动：隐私与安全性】

本发行版未经 Developer ID 签名，也未经 Apple 公证。
因此，首次启动时，macOS 可能提示 Apple 无法验证其安全性。
只有在信任下载来源并确认文件未被篡改时，才应执行以下步骤。

1. 解压 ZIP，然后尝试打开一次 VisualSampler.app。
2. 如果提示 Apple 无法验证应用是否包含恶意软件，请关闭该警告。
3. 从 Apple 菜单打开“系统设置”。
4. 选择“隐私与安全性”，向下滚动到“安全性”部分。
5. 在 VisualSampler 被阻止的通知旁点击“仍要打开”（Open Anyway）。
6. 如需认证或确认，请核对内容；若决定继续启动，请选择“打开”。
7. 应用启动后，如有提示，请选择 Banks 文件夹。

通常，许可会被保存，之后可通过双击打开。
更新版本可能需要重新授权。
如果找不到“仍要打开”，请先尝试打开应用，然后立即查看该设置页面。
由公司或学校管理的 Mac 可能无法使用此选项。

若警告显示应用“已损坏”“将损坏你的 Mac”或“检测到恶意软件”，
请勿仅按上述步骤继续；应核实官方下载来源及下载文件。
若提示“未响应”，请先退出应用并重新检查，不要反复尝试启动。

Apple 官方说明：
https://support.apple.com/ja-jp/102445

【4. 关于 BANK】

VisualSampler v1.0.1 FREE 仅可使用 BANK A 和 BANK B。
每个 BANK 可分配 16 张图像，总计最多 32 张。

BANK A：16 张东京日常风景照片（默认收录）
BANK B：以 BANK A 照片为主题的 16 张双色漫画风格图像（默认收录）

即使将图像放入 BANK C 或后续 BANK，FREE 版也不会加载或显示。
未来的 VisualSampler PRO 版计划增加可用的 BANK 数量。
※PRO 版的规格与发布时间尚未确定，可能发生变更。

【5. 使用自己的图像】

1. 退出 VisualSampler。
2. 打开 Banks/BankA 或 Banks/BankB。
3. 备份现有图像，并替换为自己喜欢的图像。
4. 重新启动 VisualSampler，确认显示效果。

支持的图像格式：
  .jpg   （优先级 1）
  .jpeg  （优先级 2）
  .png   （优先级 3）

扩展名不区分大小写。

文件命名规则：
・以对应 PAD 01～16 的“01”～“16”开头。
・可以仅使用编号，或使用“编号_任意名称”。
・示例：01.jpg / 01_tokyo.jpg / 16_night.png
・编号后没有紧接下划线的名称（如“01tokyo.jpg”）不会被识别。

同一 PAD 编号存在多个候选文件时的优先顺序：
  1. 扩展名：.jpg → .jpeg → .png
  2. 扩展名相同时，优先选择不含扩展名的文件名较短者
  3. 长度相同时，按文件名的字母顺序选择（不区分大小写）

示例：如果存在 01.jpg / 01_city.jpg / 01_tokyo.png，
      则加载 01.jpg。

为避免混淆，建议每个 PAD 编号只保留一个图像文件。

【6. 建议的图像比例与文件大小】

应用的基准窗口尺寸为 768 × 1024 px（宽：高 = 3：4）。
如需按屏幕比例制作素材，请以竖向 3：4 为参考。

建议尺寸：约 768 × 1024 px 或 1536 × 2048 px。
※这些尺寸仅为制作参考，并非必要条件。
※根据图像显示方式，裁剪、留白或变形的视觉效果可能不同。
  请确认实际显示效果。

图像文件越大或分辨率越高，启动时加载 BANK 图像所需的时间
可能越长。如果从启动画面进入主画面需要较长时间，
请将图像缩小或压缩至合适的大小。

【7. 使用 Mac 键盘调整窗口大小】

Shift + 1 ：384 × 512 px（50%）
Shift + 2 ：576 × 768 px（75%）
Shift + 3 ：768 × 1024 px（100%）

※这些操作用于切换应用的窗口大小，
  不会改变图像文件本身的尺寸。
※操作效果可能因键盘布局或输入设置而异。

【8. 视觉效果】

内置效果：
・GLITCH    ：数字噪点与画面故障效果
・CRT       ：显像管电视风格效果
・PIXELATE  ：粗颗粒像素效果
・RGB SPLIT ：RGB 色彩错位效果

SP-404MKII 操作：
・CTRL 1：选择效果
・CTRL 2 / CTRL 3：调整所选效果
・按两次 EXT SOURCE：重置效果

※效果的外观与可调整的内容因当前所选效果而异。

【9. 故障排查】

如果图像未显示：
・在启动时的选择窗口中选择上级 Banks，而不是单独的 BankA 或 BankB。
・如需重新选择，请在说明画面中按 R 键。
・确认保存位置中的 Banks 仍然存在并且可读取。
・确认“Banks/BankA”“Banks/BankB”的名称正确。
・确认图像符合 01～16 的命名规则，并使用支持的格式。
・确认没有将图像放入 BANK C 或后续 BANK。
・确认替换图像后已重新启动应用。

如果启动耗时较长：
・降低图像分辨率或减小文件大小后重试。

如果无法通过 SP-404MKII 操作：
・检查 USB 连接和设备电源。
・在 SYSTEM → MIDI 中确认“MIDI Mode：A”。
・在同一画面中确认“PAD Note Out：ON”。
・重新启动应用后再次确认。

【10. 使用注意事项与商标】

VisualSampler 是个人独立制作的软件。
在某些环境下可能无法正常运行。
对于使用本软件所产生的损失，制作者在法律允许的范围内不承担责任。

替换图像时，请遵守著作权、肖像权等相关权利要求。
进行直播或发布视频时，也请注意所用素材的权利。

VisualSampler 是与 Roland Corporation 无关联的独立作品，
并非由该公司开发、认可或赞助。
Roland 和 SP-404MKII 是 Roland Corporation 的商标或注册商标。

【11. Credits / 制作者信息】

VisualSampler v1.0.1 FREE
Created by：achamania
Concept / Design / Development：achamania

© 2026 achamania. All rights reserved.

YouTube：achamania
https://www.youtube.com/@achamania

X（Twitter）：@achamania
https://x.com/achamania

有关演示与创作活动，请查看上述社交媒体。

【12. Message from achamania】

让我看看你的作品吧！

如果你使用 VisualSampler 制作并发布了视频，
请一定在我的 YouTube 频道评论区告诉我！

现场表演、音乐视频、使用城市风景创作的视觉作品……
无论哪种用法，都非常欢迎。

我非常期待看到大家用 VisualSampler 创作出怎样的作品！

Show me what you've sampled!

YouTube：https://www.youtube.com/@achamania

Sample Your City. Remix Your Reality.

【v1.0.1 更新与验证情况】
・修复下载后因 macOS 隔离运行（App Translocation）而找不到外部 Banks 的问题。
・支持选择 Banks、保存位置和重新选择。
・更新应用图标。
・已内置 Java，通常无需另外安装 Processing 或 Java。

2026 年 10 月 15 日，在用于开发的 Apple Silicon Mac 上，已验证从 GitHub 重新下载、
macOS 启动授权、Banks 加载与重新选择恢复，以及实体设备的 MIDI、BANK、FX、CTRL 操作。
还通过自动化测试验证了全部 32 张图像及 PAD 处理。
尚未验证其他 Mac、长时间运行以及所有参数组合。
现有启动画面显示 Ver. 1.00，但本发行包为 v1.0.1。
