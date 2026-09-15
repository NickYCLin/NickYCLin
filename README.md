# Nick Lin 林洋琛

你好，我是 Nick，目前在逢甲大學地理資訊系統研究中心工作。平常做 GIS、水情與防災相關系統，寫前後端、串感測資料，也處理資料庫、部署和既有系統的維護。

這裡放的是我做的開源工具和應用。最近主要在做 **LatticeTerm** 和 **MQTTape**，也和羽山秋人一起維護資料庫工具 **mySQLPunk**。

I'm a software developer in Taiwan, working on GIS and monitoring systems. I also build the open-source tools and apps below.

[開發工具](#tools) &nbsp; · &nbsp; [生活、學習與遊戲](#apps) &nbsp; · &nbsp; [平常用的技術](#toolbox) &nbsp; · &nbsp; [More about me in English](#english)

<a name="tools"></a>

## 開發工具

<table>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/lattice-term"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/terminal.svg" width="28" height="28" alt=""> LatticeTerm</a></h3>

**AI CLI 與遠端連線工作區**

把本機 AI CLI 和 SSH、SFTP、RDP、VNC 放在一起，可以一邊跑 coding agent，一邊操作遠端主機。也有加密保管庫、工作階段還原，以及接手遠端既有 CLI 工作階段。

<sub>A desktop workspace for AI coding agents and remote connections.</sub>

`Rust` `Tauri` `React`

[原始碼](https://github.com/NickYCLin/lattice-term) · [下載](https://github.com/NickYCLin/lattice-term/releases)

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/mqttape"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/messages.svg" width="28" height="28" alt=""> MQTTape</a></h3>

**MQTT 訊息檢查與流量重播**

看 Topic、訊息內容和封包流程，把流量存下來再重播。支援 JSON、CBOR、Protobuf、Sparkplug B，有桌面版和瀏覽器版本。

<sub>Inspect, record, and replay MQTT traffic on desktop or web.</sub>

`TypeScript` `React` `Electron`

[原始碼](https://github.com/NickYCLin/mqttape) · [試用 Web Lite](https://nickyclin.github.io/mqttape/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/shadowjohn/mySQLPunk"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/database.svg" width="28" height="28" alt=""> mySQLPunk</a></h3>

**免費的多資料庫管理工具**（與 [羽山秋人](https://github.com/shadowjohn) 合作）

一個介面連 MySQL / MariaDB、PostgreSQL、SQL Server、SQLite、Oracle、MongoDB、Redis 與 Snowflake。專案由羽山秋人發起，我從 2026 年 5 月起加入一起開發，經手的部分有 Table Designer、Avalonia 跨平台版（Linux / macOS）、TLS 與 SSH Tunnel 連線安全、AI SQL 助理，以及測試與發版流程。

<sub>A free database GUI and DBA workbench for Windows, with a Linux / macOS preview. Co-developed with its original author; my parts include the cross-platform build, connection security, the AI SQL assistant, and the test / release pipeline.</sub>

`C#` `WinForms` `Avalonia`

[原始碼](https://github.com/shadowjohn/mySQLPunk) · [下載](https://github.com/shadowjohn/mySQLPunk/releases/latest)

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/story-voice"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/voice.svg" width="28" height="28" alt=""> StoryVoice</a></h3>

**多角色有聲書製作**

把 EPUB、TXT 做成有聲書。先檢查角色、調整說話者與聲線，再用 TTS 產生音訊；中途失敗的工作可以接著處理。

<sub>Multi-character audiobooks with voice casting and human review.</sub>

`ASP.NET Core` `React` `PostgreSQL`

[原始碼](https://github.com/NickYCLin/story-voice) · [功能現況](https://github.com/NickYCLin/story-voice/blob/main/docs/PROJECT_STATUS.md)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/exe-blueprint"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/binary.svg" width="28" height="28" alt=""> EXE Blueprint</a></h3>

**EXE / DLL 靜態分析**

不用執行目標程式，就能查看 PE、.NET metadata、IL、相依關係與 WPF BAML。可輸出報告與重建骨架，有桌面介面和 CLI。

<sub>Inspect Windows binaries and export reports without running them.</sub>

`C#` `.NET` `Avalonia`

[原始碼](https://github.com/NickYCLin/exe-blueprint) · [下載](https://github.com/NickYCLin/exe-blueprint/releases)

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/vuln-weaver"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/shield.svg" width="28" height="28" alt=""> VulnWeaver 弱點編織者</a></h3>

**弱點掃描報告與複掃比對**

把 Nessus、Nmap 的掃描結果整理成繁體中文的 Word 報告，內建常見弱點的在地化說明與修補建議。傳入初掃與複掃結果，會自動列出已修復、仍存在與新增的項目。

<sub>Turn Nessus and Nmap scans into Traditional Chinese Word reports, with baseline vs. rescan diffs.</sub>

`Python` `python-docx`

[原始碼](https://github.com/NickYCLin/vuln-weaver)

</td>
</tr>
</table>

<a name="apps"></a>

## 生活、學習與遊戲

<table>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/vowbook"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/planner.svg" width="28" height="28" alt=""> VowBook 誓約簿</a></h3>

**一起整理婚宴大小事**

和伴侶或婚顧共同管理賓客、桌次、預算、任務與婚禮流程。

<sub>A shared wedding planner for couples and wedding planners.</sub>

`Next.js` `TypeScript` `PostgreSQL`

[原始碼與使用說明](https://github.com/NickYCLin/vowbook)

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/learnmore"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/music.svg" width="28" height="28" alt=""> LearnMore</a></h3>

**用日文歌曲練聽力與跟唱**

同步顯示歌詞、漢字注音、羅馬拼音與中文翻譯，也整合 Whisper 轉錄。

<sub>Practice Japanese with songs, synchronized lyrics, and transcription.</sub>

`ASP.NET Core` `Whisper`

[原始碼與使用說明](https://github.com/NickYCLin/learnmore)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/pocket-salvagers"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/gamepad.svg" width="28" height="28" alt=""> Pocket Salvagers 小小回收隊</a></h3>

**桌底迷你機器人的回收冒險**

用磁力拖回散落零件、搭起尺橋探索對岸，再趕在時間耗盡前回基地。單人 3D 遊戲原型，素材以 Blender 自製。

<sub>A small open-source 3D scavenging game prototype built with Godot.</sub>

`Godot` `GDScript` `Blender`

[原始碼與遊玩方式](https://github.com/NickYCLin/pocket-salvagers)

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/project-shenjin"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/temple.svg" width="28" height="28" alt=""> 神燼：三誓之戰</a></h3>

**原創神話動作 RPG 原型**

以「失落神殿」守衛戰為起點，包含可重建的 Blender 角色與場景、UE5 C++ 專案，以及用來測試手感的瀏覽器戰鬥原型。目前是早期原型。

<sub>An original mythology action RPG prototype: Blender assets, UE5 C++, and a browser combat sandbox.</sub>

`Unreal Engine 5` `C++` `Blender`

[原始碼與試玩](https://github.com/NickYCLin/project-shenjin)

</td>
</tr>
</table>

其他公開的小專案：[remittance-demo](https://github.com/NickYCLin/remittance-demo) 是用 .NET 8 和 Vue 3 示範企業整批匯款的取消、狀態檢查與防止重複操作。

<a name="toolbox"></a>

## 平常用的技術

- **後端與資料**：C# / .NET、Python、PostgreSQL、SQL Server、MySQL、Redis
- **網頁與桌面**：TypeScript、React、Next.js、Rust、Tauri、Electron、Avalonia、WinForms
- **空間資料與設備**：CesiumJS、Three.js、MQTT、攝影機串流（RTSP / FFmpeg）
- **遊戲與 3D**：Godot、Unreal Engine 5、Blender
- **測試與部署**：Docker、GitHub Actions、GitLab CI、Playwright

工作上的專案多半沒有公開，主要是水情與防災決策平台、3D 水情數位孿生、出流管制監測、攝影機影像平台、農場觀測，以及各種感測資料與通知的整合工具，所以這裡以能分享原始碼的作品為主。如果你有用到這些工具，歡迎到各專案開 issue，告訴我哪裡不好用、遇到什麼問題。

<a name="english"></a>

<details>
<summary><b>More about me in English</b></summary>

I'm Nick, a software developer at the GIS Research Center, Feng Chia University in Taiwan.

My work involves GIS, water monitoring, and disaster management systems. I work on map interfaces, sensor data, APIs, databases, and deployment, including maintaining older applications alongside newer services.

The projects above cover developer tools, database tooling, security reporting, audiobook production, wedding planning, language learning, and a couple of game prototypes. I mostly use C# / .NET and TypeScript / React, with Rust for desktop tooling. mySQLPunk is a collaboration with its original author; since May 2026 I have been contributing features such as the cross-platform Avalonia build, connection security, and the release pipeline.

Some work repositories are private. The public projects here are available to explore, try, and contribute to. Bug reports and feedback are welcome.

</details>
