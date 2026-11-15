# Awesome-Mobile-Enterprise-Productivity

# Awesome Mobile Enterprise Productivity

> A curated list of top Mobile Enterprise Productivity platforms — both SaaS/Hosted commercial suites and open-source alternatives for documents, tasks, and team collaboration on mobile devices.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Microsoft 365 Mobile](#microsoft-365-mobile)
  - [Google Workspace Mobile](#google-workspace-mobile)
  - [Notion Mobile](#notion-mobile)
  - [Slack Mobile](#slack-mobile)
  - [ClickUp Mobile](#clickup-mobile)
- [Open-Source Software](#-open-source-software)
  - [AFFiNE](#affine)
  - [OnlyOffice DocSpace](#onlyoffice-docspace)
  - [Collabora Office](#collabora-office)
  - [Vikunja](#vikunja)
  - [Jotter](#jotter)
  - [Tasks.org](#tasksorg)
  - [Joplin](#joplin)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Mobile Enterprise Productivity platforms. These are not open-source but are included as reference points for feature comparison.

### Microsoft 365 Mobile
**Type:** Office apps and collaboration on mobile
Microsoft 365 Mobile provides Word, Excel, PowerPoint, Outlook, and Teams on iOS and Android, with real-time co-authoring, cloud sync via OneDrive, and enterprise security controls. It is the default choice for organizations standardized on Microsoft.

### Google Workspace Mobile
**Type:** Google productivity suite on mobile
Google Workspace Mobile provides Gmail, Drive, Docs, Sheets, Meet, and Chat on mobile devices, with real-time collaboration and offline access. It is the natural choice for Google-first organizations, with zero setup and broad device support.

### Notion Mobile
**Type:** Flexible workspace with mobile editing
Notion Mobile brings its block-based workspace to iOS and Android, with pages, databases, and wikis accessible on the go. It supports offline editing and sync, with the same flexibility as the desktop version.

### Slack Mobile
**Type:** Team messaging on mobile
Slack Mobile provides channels, threads, direct messages, and Huddles on phones, with push notifications and file sharing. It is the most widely adopted team messaging platform, with native apps for iOS and Android.

### ClickUp Mobile
**Type:** All-in-one productivity on mobile
ClickUp Mobile provides tasks, docs, goals, and chat on mobile devices, with offline mode and notifications. It is positioned for teams wanting a comprehensive productivity suite in a single app.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Mobile Enterprise Productivity tools. The open-source ecosystem spans **local-first workspaces with native apps**, **full office suites for mobile**, **task managers with mobile clients**, and **note-taking apps with sync**.

### AFFiNE
**Stack:** TypeScript / Rust (OctoBase) | **License:** MIT (Community Edition)
AFFiNE is an open-source, local-first workspace that combines documents, whiteboards, and tasks in one app, with native mobile clients for iOS and iPadOS [citation:3]. Key characteristics include block-based documents with Markdown support, an infinite canvas for visual thinking, task tracking, and AI features. It has approximately 70K GitHub stars and 7 million downloads, with a focus on data ownership and self-hosting options [citation:3]. **Trade-off:** AI features are gated to paid plans, and the mobile app is iOS-focused with Android support still maturing.
**Best for:** Teams wanting a Notion + Miro hybrid workspace with local-first data control and a native iOS app, accepting the Community Edition's feature limits.

### OnlyOffice DocSpace
**Stack:** JavaScript / Node.js (server) / Native apps | **License:** AGPL-3.0 (Community)
OnlyOffice provides a full office suite (Documents, Spreadsheets, Presentations, PDF) with **native mobile apps for Android and iOS**, compatible with Microsoft Office formats (DOCX, XLSX, PPTX) [citation:4][citation:13]. It requires no mandatory signup for local use, and the mobile apps are free with no ads or feature restrictions [citation:4]. Cloud sync is available through DocSpace or third-party services like Nextcloud [citation:4]. **Trade-off:** The mobile apps are focused on document editing rather than team collaboration features like chat or task management.
**Best for:** Organizations wanting a free, open-source office suite with strong Microsoft format compatibility on mobile, accepting the document-focused scope.

### Collabora Office
**Stack:** C++ / LibreOffice core | **License:** MPL-2.0 (Community)
Collabora Office is the mobile version of the LibreOffice suite, available for Android and iOS, supporting Word, Excel, and PowerPoint formats along with PDF viewing and annotation [citation:9]. It is ad-free and requires no in-app purchases, developed by Collabora, a major LibreOffice contributor [citation:9]. **Trade-off:** The mobile app is focused on document editing rather than broader productivity workflows.
**Best for:** Users wanting a LibreOffice-compatible mobile office suite without ads or subscriptions, accepting a document-centric feature set.

### Vikunja
**Stack:** Go / SQLite or PostgreSQL | **License:** AGPLv3
Vikunja is an open-source to-do and project management platform with an **unofficial native iOS app** (Noel Mayr) that connects to a self-hosted Vikunja server [citation:10][citation:14]. Key features include task management with lists, projects, due dates, reminders, recurring tasks, priorities, team collaboration, offline support with automatic sync, and biometric app lock [citation:10]. The app collects no personal data and requires a Vikunja server instance [citation:10]. **Trade-off:** The iOS app is unofficial, and Android support relies on the web interface or third-party clients.
**Best for:** Teams already using Vikunja for task management wanting a native iOS client with offline support, accepting the unofficial app status.

### Jotter
**Stack:** Python / Markdown / SQLite | **License:** Open Source (PyPI)
Jotter is a local-first, Markdown-based task manager with a **native Android app** (APK) that operates 100% offline using local Markdown files with IndexedDB caching [citation:8]. It supports Kanban, list, Eisenhower Matrix, and time views, with Git-backed sync for cross-device synchronization via Syncthing or Git [citation:8]. The Android app requires no server or internet connection and can point to a synced Markdown folder for cross-device sync [citation:8]. **Trade-off:** Android-only mobile app, and the Markdown-based approach requires some technical comfort.
**Best for:** Privacy-conscious individuals wanting a Markdown-based task manager with a fully offline Android app and Git-based sync, accepting a technical setup.

### Tasks.org
**Stack:** Android-native (Kotlin/Java) | **License:** Open Source (GPL)
Tasks.org is a privacy-focused, ad-free open-source to-do list and reminder app for Android, listed in F-Droid's task category [citation:12]. It supports optional sync with Google Tasks, CalDAV, and EteSync, making it compatible with self-hosted calendar servers [citation:12]. It is one of the most established open-source Android task managers, with a mature feature set and active community.
**Best for:** Android users wanting a mature, privacy-respecting task manager with CalDAV sync to self-hosted servers, accepting Android-only availability.

### Joplin
**Stack:** JavaScript / React Native / SQLite | **License:** AGPL-3.0
Joplin is a widely adopted open-source note-taking and to-do app with **native mobile apps for iOS and Android**, supporting Markdown, end-to-end encryption, and sync via Nextcloud, Dropbox, OneDrive, or WebDAV [citation:12]. It is the most recommended open-source Evernote alternative, with a plugin ecosystem and cross-platform support. **Trade-off:** The mobile app is feature-rich but can feel heavy, and sync configuration requires some setup.
**Best for:** Teams wanting a proven, encrypted note-taking and task app with self-hosted sync options, accepting the sync configuration overhead.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Native Mobile | Offline Support | Self-Hosted | Best For |
|----------|---------|-------|---------------|-----------------|-------------|----------|
| **Microsoft 365** | Proprietary | Cloud | ✅ iOS/Android | ✅ | ❌ | Microsoft ecosystem |
| **Google Workspace** | Proprietary | Cloud | ✅ iOS/Android | ✅ | ❌ | Google-first organizations |
| **AFFiNE** | MIT (CE) | TypeScript/Rust | ✅ iOS/iPadOS | ✅ Local-first | ✅ | Notion + whiteboard hybrid |
| **OnlyOffice** | AGPL-3.0 | Node.js/Native | ✅ iOS/Android | ✅ | ✅ (DocSpace) | Office format compatibility |
| **Collabora Office** | MPL-2.0 | C++/LibreOffice | ✅ iOS/Android | ✅ | ✅ | LibreOffice on mobile |
| **Vikunja** | AGPLv3 | Go/SQLite | ✅ iOS (unofficial) | ✅ | ✅ | Task management + iOS app |
| **Jotter** | Open Source | Python/Markdown | ✅ Android | ✅ 100% offline | ✅ | Markdown tasks + Android |
| **Tasks.org** | Open Source | Android-native | ✅ Android | ✅ | ✅ (CalDAV) | Privacy-focused Android tasks |
| **Joplin** | AGPL-3.0 | React Native | ✅ iOS/Android | ✅ | ✅ | Encrypted notes + sync |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Mobile Enterprise Productivity tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

**Note on the open-source ecosystem:** The mobile enterprise productivity space is **fragmented** compared to the all-in-one commercial suites. For **office documents**, **OnlyOffice** and **Collabora Office** provide strong Microsoft/LibreOffice compatibility on mobile [citation:4][citation:9]. For **workspace + notes + tasks**, **AFFiNE** offers the closest Notion-like experience with a native iOS app and local-first data control [citation:3]. For **task management**, **Vikunja** provides a native iOS client for self-hosted users , **Jotter** offers a fully offline Android app with Markdown storage [citation:8], and **Tasks.org** is the most mature Android-native option with CalDAV sync [citation:12]. **Joplin** remains the strongest open-source note-taking app with mobile clients and encrypted sync . No single open-source app replicates the full breadth of Microsoft 365 or Google Workspace on mobile, but these tools cover the core productivity workflows for self-hosted deployments.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
