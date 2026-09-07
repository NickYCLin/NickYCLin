# Nick Lin 林洋琛

你好，我是 Nick，目前在逢甲大學地理資訊系統研究中心工作。

工作上主要做 GIS、水情與防災相關系統，從地圖介面、感測資料串接，到後端 API、資料庫和部署都會碰。除了開發新功能，也花不少時間維護既有系統、追資料問題，讓不同年代的程式能繼續一起運作。

這裡放的是我做的開源專案，有開發工具，也有有聲書、語言學習和婚宴規劃。最近主要在做 LatticeTerm 和 MQTTape。

[English](#english)

## 最近在做的專案

### [LatticeTerm](https://github.com/NickYCLin/lattice-term)

把本機 AI CLI 和 SSH、SFTP、RDP、VNC 放在同一個桌面工作區，可以一邊跑 coding agent，一邊操作遠端主機。用 Rust、Tauri 和 React 開發，支援 Windows、macOS、Linux，也有加密保管庫、遠端分享與工作階段還原。

[下載版本](https://github.com/NickYCLin/lattice-term/releases)

### [MQTTape](https://github.com/NickYCLin/mqttape)

用來檢查 MQTT 訊息、看 Topic 和封包流程，也能把流量存下來重播。除了 JSON，也支援 CBOR、Protobuf、Sparkplug B 等格式。桌面版用 Electron 和 React，另有可以直接開啟的 [Web Lite](https://nickyclin.github.io/mqttape/)。

### [StoryVoice](https://github.com/NickYCLin/story-voice)

把 EPUB、TXT 做成多角色有聲書。可以檢查角色、調整誰在說話、安排聲線，再交給 TTS 產生音訊；中途失敗的工作可以接著處理。後端是 ASP.NET Core，前端用 React，搭配 PostgreSQL。

### [EXE Blueprint](https://github.com/NickYCLin/exe-blueprint)

不用執行 EXE 或 DLL，就能查看 PE、.NET metadata、IL、相依關係與 WPF BAML，輸出報告和程式重建骨架。用 C#、.NET 和 Avalonia 開發，有桌面介面與 CLI。

## 其他作品

- [VowBook 誓約簿](https://github.com/NickYCLin/vowbook)：和伴侶或婚顧一起管理賓客、桌次、預算與婚禮流程，使用 Next.js、PostgreSQL。
- [LearnMore](https://github.com/NickYCLin/learnmore)：用日文歌曲練聽力與跟唱，整合同步歌詞、漢字注音、羅馬拼音、中文翻譯與 Whisper 轉錄。

## 平常用的技術

後端以 **C# / .NET** 為主，前端多半用 **TypeScript、React**，桌面工具也用 **Rust、Tauri、Electron**。資料庫主要是 PostgreSQL、SQL Server，空間資料與設備串接會用到 CesiumJS 和 MQTT。

另外會用 Docker 部署服務，測試與發版流程搭配 GitHub Actions、GitLab CI 和 Playwright。

有些工作專案沒有公開，所以這裡以能分享原始碼的作品為主。如果你有用到這些工具，歡迎到各專案開 issue，告訴我哪裡不好用、遇到什麼問題。

---

## English

I'm Nick, a software developer at the GIS Research Center, Feng Chia University in Taiwan.

My work involves GIS, water monitoring, and disaster management systems. I work on map interfaces, sensor data, APIs, databases, and deployment, including maintaining older applications alongside newer services.

I also build and maintain the open-source projects listed above:

- **[LatticeTerm](https://github.com/NickYCLin/lattice-term)** brings local AI coding agents and remote connections into a desktop workspace.
- **[MQTTape](https://github.com/NickYCLin/mqttape)** inspects, records, and replays MQTT traffic, with desktop and browser versions.
- **[StoryVoice](https://github.com/NickYCLin/story-voice)** turns EPUB and TXT files into multi-character audiobooks, with voice casting, human review, and resumable TTS jobs.
- **[EXE Blueprint](https://github.com/NickYCLin/exe-blueprint)** inspects Windows binaries without running them and exports reports and reconstruction scaffolds.
- **[VowBook](https://github.com/NickYCLin/vowbook)** is a collaborative wedding planner.
- **[LearnMore](https://github.com/NickYCLin/learnmore)** is a Japanese song learning app with synchronized lyrics and transcription.

I mostly use C# / .NET and TypeScript / React, with Rust for desktop tooling. If you try one of these projects, bug reports and feedback are welcome.

