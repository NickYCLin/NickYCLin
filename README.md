# Nick Lin 林洋琛

你好，我是 Nick，目前在逢甲大學地理資訊系統研究中心工作。平常做 GIS、水情與防災相關系統，寫前後端、串感測資料，也處理資料庫、部署和既有系統的維護。

這裡放的是我做的開源工具和應用。最近主要在做 **LatticeTerm** 和 **MQTTape**。

I'm a software developer in Taiwan, working on GIS and monitoring systems. I also build the open-source tools and apps below.

[作品 Projects](#projects) &nbsp; · &nbsp; [平常用的技術](#toolbox) &nbsp; · &nbsp; [More about me in English](#english)

<a name="projects"></a>

## 做過的工具與應用

<table>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/lattice-term"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/terminal.svg" width="28" height="28" alt=""> LatticeTerm</a></h3>

**AI CLI 與遠端連線工作區**

把本機 AI CLI 和 SSH、SFTP、RDP、VNC 放在一起，可以一邊跑 coding agent，一邊操作遠端主機。也有加密保管庫與工作階段還原。

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

<h3><a href="https://github.com/NickYCLin/story-voice"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/voice.svg" width="28" height="28" alt=""> StoryVoice</a></h3>

**多角色有聲書製作**

把 EPUB、TXT 做成有聲書。先檢查角色、調整說話者與聲線，再用 TTS 產生音訊；中途失敗的工作可以接著處理。

<sub>Multi-character audiobooks with voice casting and human review.</sub>

`ASP.NET Core` `React` `PostgreSQL`

[原始碼](https://github.com/NickYCLin/story-voice) · [功能現況](https://github.com/NickYCLin/story-voice/blob/main/docs/PROJECT_STATUS.md)

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/NickYCLin/exe-blueprint"><img src="https://raw.githubusercontent.com/NickYCLin/NickYCLin/main/assets/binary.svg" width="28" height="28" alt=""> EXE Blueprint</a></h3>

**EXE / DLL 靜態分析**

不用執行目標程式，就能查看 PE、.NET metadata、IL、相依關係與 WPF BAML。可輸出報告與重建骨架，有桌面介面和 CLI。

<sub>Inspect Windows binaries and export reports without running them.</sub>

`C#` `.NET` `Avalonia`

[原始碼](https://github.com/NickYCLin/exe-blueprint) · [下載](https://github.com/NickYCLin/exe-blueprint/releases)

</td>
</tr>
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
</table>

<a name="toolbox"></a>

## 平常用的技術

- **後端與資料**：C# / .NET、Python、PostgreSQL、SQL Server、Redis
- **網頁與桌面**：TypeScript、React、Next.js、Rust、Tauri、Electron
- **空間資料與設備**：CesiumJS、MQTT
- **測試與部署**：Docker、GitHub Actions、GitLab CI、Playwright

有些工作專案沒有公開，所以這裡以能分享原始碼的作品為主。如果你有用到這些工具，歡迎到各專案開 issue，告訴我哪裡不好用、遇到什麼問題。

<a name="english"></a>

<details>
<summary><b>More about me in English</b></summary>

I'm Nick, a software developer at the GIS Research Center, Feng Chia University in Taiwan.

My work involves GIS, water monitoring, and disaster management systems. I work on map interfaces, sensor data, APIs, databases, and deployment, including maintaining older applications alongside newer services.

The projects above cover developer tools, audiobook production, wedding planning, and language learning. I mostly use C# / .NET and TypeScript / React, with Rust for desktop tooling.

Some work repositories are private. The public projects here are available to explore, try, and contribute to. Bug reports and feedback are welcome.

</details>

