
🔥 NyxSU —— 内核级无痕 Root，重新定义“越狱”

-官网 www.zakosu.asia

你的 Root，凭什么要被检测到？

市面上所有 Root 管理器都在做同一件事：装进内核，然后祈祷检测工具看不见。NyxSU 不祈祷——NyxSU 从第一天起就是为“不可见”而生的。

⚡ 一键越狱，六种武器

内置 DirtyFrag、Ghostlock、GhostKey、DirtyPipe、DirtyCow、NyxSU_Shizuku 六大提权通道。不挑内核、不挑设备：KPM 内核走内核补丁，老内核走 CVE 历史，全设备兜底 Shizuku 配对。点一下「越狱」按钮，管理器自动探测你的内核版本、匹配最佳通道、实时输出日志——全程你只需要按一次确认。

👻 GhostLock —— 84 份内核档案随包携带

NyxSU 内置了 GhostLock 完整内核指纹库：84 份针对不同设备、不同内核构建的真实 offset 配置，覆盖 Android 12 → 16、5.10 → 6.18 全线 GKI 内核。点下越狱的瞬间，NyxSU 读取你的 uname -r，毫秒级匹配对应档案，直接执行内核级提权。找不到匹配？它诚实告诉你，绝不假装成功。

🕶️ Ultra 模式 —— 零痕迹，从安装那一刻开始

安装页选择 NyxSU_Ultra · 极致无痕：跳过 preinit、跳过自定义 rc，从 boot 镜像打补丁那一刻起就把用户态指纹降到最低。零可见 SELinux 策略修改、零挂载痕迹、全局保持 Enforcing——检测工具看到的，是一台“没动过手脚”的手机。

🛡️ 反检测三件套，专门伺候检测工具和游戏

- 隐藏挂载：非 root 进程永远看不到模块挂载点
- sus-path 隐藏：/data/adb、/system/bin/su 等全部痕迹路径 kstat 级抹除
- uname 伪装：内核版本号对你说了谎——检测工具读到的，是一台原厂 GKI 机器

一处开关，全部生效。银行 APP、游戏反作弊、企业 MDM——让它们集体失明。

🎛️ 双 UI，双倍的体验

Miuix：MIUI 原生质感，毛玻璃模糊、动态壁纸背景、玻璃透明度可调，还有 NyxSU 专属渐变模式卡——Ultra 是深邃的青，Normal 是神秘的紫，一眼认出你的工作模式。
Material 3 Expressive：谷歌最新动态取色 + 表现力动效，Monet 全系统联动。
两套 UI 功能完全对等，随时一键切换——切换是丝滑的，因为我们把双主题共存的地雷也扫干净了。

🧩 KPM + SUSFS 原生集成

内核补丁模块（KPM）运行时加载、SUSFS 深度隐藏——不是 PPT 功能，是接通 ksud 真实接口的活功能。内核支持就亮绿灯，不支持就明说，从不糊弄。

🗄️ 一键备份，换机无忧

全部设置、授权记录、隐藏状态——一条 JSON 导出，换机恢复只要一次点击。

🔒 还有那些你没想到的

- 隐身模式一键全开：隐藏图标 + 隐身 + 卸载隐藏 + SELinux 隐藏，一次全关
- 暗码唤醒：图标藏了也能 *#*#6997#*#* 拨号唤回
- 超时自动回滚的越狱保护：30 秒没响应自动放弃，绝不变砖
- v1.1.0 全新品牌：极致无痕内核 Root——这就是 NyxSU 的名字

---

KernelSU 的壳，MapleSU 的野心，NyxSU 的灵魂。
装上它，你的 Root 从此只有你知道。

📥 开源仓库：github.com/cranemay9/TomiSU
⭐ 觉得好用，点个 Star；有问题，Issue 见。

---



🔥 NyxSU v1.1.0 | 内核级无痕 Root 管理器

⚡ 一键越狱：DirtyFrag / Ghostlock / GhostKey / DirtyPipe / DirtyCow / Shizuku，自动探测内核匹配通道
👻 内置 GhostLock 84 份内核档案，Android 12-16 全覆盖
🕶️ Ultra 无痕模式：0 SELinux 修改、0 挂载、全局 Enforcing
🛡️ 游戏反检测：sus-path 抹除 + uname 伪装，检测工具集体失明
🎛️ Miuix / Material 双 UI 完全对等，一键切换
🧩 KPM + SUSFS 真接口集成 | 🗄️ 一键备份 | 🔒 隐身全开

你的 Root，只有你知道。
📥 github.com/cranemay9/TomiSU
