\# 📊 Team Project Manager v2.0



> A modern, intuitive team collaboration app with real-time cloud synchronization and conflict resolution.



\[!\[Live Demo](https://img.shields.io/badge/demo-live-success)](https://lyode.github.io/team-project-manager/)

\[!\[License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

\[!\[Version](https://img.shields.io/badge/version-2.0.0-purple)](docs/CHANGELOG.md)



---



\## ✨ Features



\### 🎯 Core Functionality

\- \*\*📋 Project Management\*\* - Create, edit, and organize multiple projects

\- \*\*✅ Task Tracking\*\* - Assign tasks with priorities, due dates, and status tracking

\- \*\*👥 Team Collaboration\*\* - Manag# 📊 Team Project Manager v2.0



> A modern, intuitive team collaboration app with real-time cloud synchronization and conflict resolution.



\[!\[Live Demo](https://img.shields.io/badge/demo-live-success)](https://lyode.github.io/team-project-manager/)

\[!\[License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

\[!\[Version](https://img.shields.io/badge/version-2.0.0-purple)](docs/CHANGELOG.md)



---



\## ✨ Features



\### 🎯 Core Functionality

\- \*\*📋 Project Management\*\* - Create, edit, and organize multiple projects

\- \*\*✅ Task Tracking\*\* - Assign tasks with priorities, due dates, and status tracking

\- \*\*👥 Team Collaboration\*\* - Manage team members and assignments

\- \*\*📊 Multiple Views\*\* - Dashboard, Kanban, List, and Activity views



\### ☁️ Cloud Sync \& Collaboration

\- \*\*Auto-Sync\*\* - Configurable automatic synchronization (30s - 5min intervals)

\- \*\*Manual Sync\*\* - Push/Pull data on demand with one click

\- \*\*Conflict Resolution\*\* - Smart 3-way conflict handling (Cloud / Local / Merge)

\- \*\*Offline Mode\*\* - Work offline, sync when connection returns

\- \*\*User Attribution\*\* - Track who created/modified each item



\### 📜 Activity \& History

\- \*\*Activity Log\*\* - Complete audit trail of all changes

\- \*\*User Tracking\*\* - See who did what and when

\- \*\*Change Notifications\*\* - Toast notifications for all actions



\### 🎨 Customization \& Accessibility

\- \*\*18 Color Themes\*\* - Purple, Navy, Steel, Slate, Sage, Olive, Forest, Plum, Mauve, and more

\- \*\*Night Mode\*\* - Easy on the eyes for late-night work

\- \*\*Font Scaling\*\* - 4 sizes (S, M, L, XL) for better readability

\- \*\*Contrast Control\*\* - Normal, Low, High, Extra High contrast modes

\- \*\*Responsive Design\*\* - Works on desktop, tablet, and mobile



\### 💾 Data Management

\- \*\*Export/Import\*\* - JSON-based data backup and transfer

\- \*\*Local Storage\*\* - Automatic local saving for offline work

\- \*\*Version Control\*\* - Sync versioning to prevent data loss



---



\## 🚀 Quick Start



\### Option 1: Use Live Demo

1\. Visit the \[Live Demo](https://lyode.github.io/team-project-manager/)

2\. Enter your name when prompted

3\. Click the ☁️ button to set up sync (optional)

4\. Start creating projects!



\### Option 2: Self-Host

1\. Download or clone this repository

2\. Open `index.html` in any modern web browser

3\. No build process or server required!



```bash

\# Clone the repository

git clone https://github.com/lyode/team-project-manager.git

cd team-project-manager



\# Open in browser

open index.html  # Mac

start index.html # Windows

xdg-open index.html # Linux

```



---



\## ⚙️ Setup Guide



\### Basic Setup (No Cloud Sync)

1\. Open the app

2\. Enter your name

3\. Start adding projects and tasks

4\. Data saves automatically to your browser



\### Cloud Sync Setup (Recommended for Teams)

1\. Get a \*\*free API key\*\* from \[JSONBin.io](https://jsonbin.io)

&nbsp;  - Sign up (free tier: 10,000 requests/month)

&nbsp;  - Create a new bin

&nbsp;  - Copy your API key

2\. In the app:

&nbsp;  - Click ☁️ sync button

&nbsp;  - Paste your API key

&nbsp;  - Enable auto-sync in Settings (optional)

3\. Share the same bin ID with your team members

4\. Everyone enters the same API key to collaborate



📖 \*\*Detailed Setup Instructions:\*\* \[docs/SETUP.md](docs/SETUP.md)



---



\## 📖 Usage



\### Creating Projects

1\. Click the \*\*+\*\* button (bottom right)

2\. Select "📁 New Project"

3\. Fill in project details

4\. Click Save



\### Adding Tasks

1\. Click the \*\*+\*\* button

2\. Select "📋 New Task"

3\. Choose project, assignee, dates

4\. Click Save



\### Switching Views

\- \*\*Dashboard\*\* - Card-based project overview

\- \*\*Kanban\*\* - Drag \& drop task board (Due / In Progress / Coming)

\- \*\*List\*\* - Spreadsheet-style task list

\- \*\*Activity\*\* - Complete change history



\### Syncing Data

\- \*\*Manual Sync:\*\*

&nbsp; - Click ☁️ button

&nbsp; - OK = Pull from cloud (get latest)

&nbsp; - Cancel = Push to cloud (save yours)

\- \*\*Auto-Sync:\*\*

&nbsp; - Settings → Enable Auto-Sync

&nbsp; - Choose interval (1-5 minutes)



\### Handling Conflicts

When changes conflict, you'll see 3 options:

\- \*\*☁️ Use Cloud Version\*\* - Replace local with cloud data

\- \*\*💾 Use My Version\*\* - Overwrite cloud with local data

\- \*\*🔀 Merge Both\*\* - Combine intelligently (no duplicates)



---



\## 🛠️ Tech Stack



\- \*\*Frontend:\*\* Pure HTML5, CSS3, JavaScript (ES6+)

\- \*\*Storage:\*\* LocalStorage for offline data

\- \*\*Cloud Sync:\*\* JSONBin.io API

\- \*\*Dependencies:\*\* Zero! No frameworks, no build process

\- \*\*Browser Support:\*\* All modern browsers (Chrome, Firefox, Safari, Edge)



---



\## 📁 File Structure



```

team-project-manager/

├── index.html              # Main application file (all-in-one)

├── README.md               # This file

├── LICENSE                 # MIT License

├── .gitignore             # Git ignore rules

└── docs/

&nbsp;   ├── SETUP.md           # Detailed setup guide

&nbsp;   ├── CHANGELOG.md       # Version history

&nbsp;   └── DEPLOYMENT.md      # Deployment options

```



---



\## 🎯 Roadmap



\### v2.1 (Planned)

\- \[ ] Push notifications for task assignments

\- \[ ] Search and advanced filtering

\- \[ ] Task comments and discussions

\- \[ ] File attachments (images, PDFs)

\- \[ ] Interactive Gantt chart



\### v3.0 (Future)

\- \[ ] Firebase backend option

\- \[ ] Real-time collaboration

\- \[ ] Mobile apps (iOS/Android)

\- \[ ] Calendar integration

\- \[ ] Time tracking



\*\*See full roadmap:\*\* \[docs/CHANGELOG.md](docs/CHANGELOG.md)



---



\## 🤝 Contributing



Contributions are welcome! Here's how:



1\. Fork the repository

2\. Create a feature branch (`git checkout -b feature/amazing-feature`)

3\. Commit your changes (`git commit -m 'Add amazing feature'`)

4\. Push to the branch (`git push origin feature/amazing-feature`)

5\. Open a Pull Request



See \[CONTRIBUTING.md](CONTRIBUTING.md) for details.



---



\## 📄 License



This project is licensed under the \*\*MIT License\*\* - see the \[LICENSE](LICENSE) file for details.



---



\## 🙏 Acknowledgments



\- Icons: Unicode Emoji

\- Color schemes: Custom darker professional tones

\- Inspired by modern project management tools

\- Built with ❤️ for teams who need simple, effective collaboration



---



\## 📞 Support



\- \*\*Issues:\*\* \[GitHub Issues](https://github.com/lyode/team-project-manager/issues)

\- \*\*Discussions:\*\* \[GitHub Discussions](https://github.com/lyode/team-project-manager/discussions)

\- \*\*Email:\*\* lyodengck@gmail.com



---



\## 🌟 Star History



If you find this project useful, please consider giving it a star! ⭐



---



\*\*Made with ❤️ by \[lyode ng](https://github.com/lyode)\*\*



\*Last updated: January 2025\*e team members and assignments

\- \*\*📊 Multiple Views\*\* - Dashboard, Kanban, List, and Activity views



\### ☁️ Cloud Sync \& Collaboration

\- \*\*Auto-Sync\*\* - Configurable automatic synchronization (30s - 5min intervals)

\- \*\*Manual Sync\*\* - Push/Pull data on demand with one click

\- \*\*Conflict Resolution\*\* - Smart 3-way conflict handling (Cloud / Local / Merge)

\- \*\*Offline Mode\*\* - Work offline, sync when connection returns

\- \*\*User Attribution\*\* - Track who created/modified each item



\### 📜 Activity \& History

\- \*\*Activity Log\*\* - Complete audit trail of all changes

\- \*\*User Tracking\*\* - See who did what and when

\- \*\*Change Notifications\*\* - Toast notifications for all actions



\### 🎨 Customization \& Accessibility

\- \*\*18 Color Themes\*\* - Purple, Navy, Steel, Slate, Sage, Olive, Forest, Plum, Mauve, and more

\- \*\*Night Mode\*\* - Easy on the eyes for late-night work

\- \*\*Font Scaling\*\* - 4 sizes (S, M, L, XL) for better readability

\- \*\*Contrast Control\*\* - Normal, Low, High, Extra High contrast modes

\- \*\*Responsive Design\*\* - Works on desktop, tablet, and mobile



\### 💾 Data Management

\- \*\*Export/Import\*\* - JSON-based data backup and transfer

\- \*\*Local Storage\*\* - Automatic local saving for offline work

\- \*\*Version Control\*\* - Sync versioning to prevent data loss



---



\## 🚀 Quick Start



\### Option 1: Use Live Demo

1\. Visit the \[Live Demo](https://lyode.github.io/team-project-manager/)

2\. Enter your name when prompted

3\. Click the ☁️ button to set up sync (optional)

4\. Start creating projects!



\### Option 2: Self-Host

1\. Download or clone this repository

2\. Open `index.html` in any modern web browser

3\. No build process or server required!



```bash

\# Clone the repository

git clone https://github.com/lyode/team-project-manager.git

cd team-project-manager



\# Open in browser

open index.html  # Mac

start index.html # Windows

xdg-open index.html # Linux

```



---



\## ⚙️ Setup Guide



\### Basic Setup (No Cloud Sync)

1\. Open the app

2\. Enter your name

3\. Start adding projects and tasks

4\. Data saves automatically to your browser



\### Cloud Sync Setup (Recommended for Teams)

1\. Get a \*\*free API key\*\* from \[JSONBin.io](https://jsonbin.io)

&nbsp;  - Sign up (free tier: 10,000 requests/month)

&nbsp;  - Create a new bin

&nbsp;  - Copy your API key

2\. In the app:

&nbsp;  - Click ☁️ sync button

&nbsp;  - Paste your API key

&nbsp;  - Enable auto-sync in Settings (optional)

3\. Share the same bin ID with your team members

4\. Everyone enters the same API key to collaborate



📖 \*\*Detailed Setup Instructions:\*\* \[docs/SETUP.md](docs/SETUP.md)



---



\## 📖 Usage



\### Creating Projects

1\. Click the \*\*+\*\* button (bottom right)

2\. Select "📁 New Project"

3\. Fill in project details

4\. Click Save



\### Adding Tasks

1\. Click the \*\*+\*\* button

2\. Select "📋 New Task"

3\. Choose project, assignee, dates

4\. Click Save



\### Switching Views

\- \*\*Dashboard\*\* - Card-based project overview

\- \*\*Kanban\*\* - Drag \& drop task board (Due / In Progress / Coming)

\- \*\*List\*\* - Spreadsheet-style task list

\- \*\*Activity\*\* - Complete change history



\### Syncing Data

\- \*\*Manual Sync:\*\*

&nbsp; - Click ☁️ button

&nbsp; - OK = Pull from cloud (get latest)

&nbsp; - Cancel = Push to cloud (save yours)

\- \*\*Auto-Sync:\*\*

&nbsp; - Settings → Enable Auto-Sync

&nbsp; - Choose interval (1-5 minutes)



\### Handling Conflicts

When changes conflict, you'll see 3 options:

\- \*\*☁️ Use Cloud Version\*\* - Replace local with cloud data

\- \*\*💾 Use My Version\*\* - Overwrite cloud with local data

\- \*\*🔀 Merge Both\*\* - Combine intelligently (no duplicates)



---



\## 🛠️ Tech Stack



\- \*\*Frontend:\*\* Pure HTML5, CSS3, JavaScript (ES6+)

\- \*\*Storage:\*\* LocalStorage for offline data

\- \*\*Cloud Sync:\*\* JSONBin.io API

\- \*\*Dependencies:\*\* Zero! No frameworks, no build process

\- \*\*Browser Support:\*\* All modern browsers (Chrome, Firefox, Safari, Edge)



---



\## 📁 File Structure



```

team-project-manager/

├── index.html              # Main application file (all-in-one)

├── README.md               # This file

├── LICENSE                 # MIT License

├── .gitignore             # Git ignore rules

└── docs/

&nbsp;   ├── SETUP.md           # Detailed setup guide

&nbsp;   ├── CHANGELOG.md       # Version history

&nbsp;   └── DEPLOYMENT.md      # Deployment options

```



---



\## 🎯 Roadmap



\### v2.1 (Planned)

\- \[ ] Push notifications for task assignments

\- \[ ] Search and advanced filtering

\- \[ ] Task comments and discussions

\- \[ ] File attachments (images, PDFs)

\- \[ ] Interactive Gantt chart



\### v3.0 (Future)

\- \[ ] Firebase backend option

\- \[ ] Real-time collaboration

\- \[ ] Mobile apps (iOS/Android)

\- \[ ] Calendar integration

\- \[ ] Time tracking



\*\*See full roadmap:\*\* \[docs/CHANGELOG.md](docs/CHANGELOG.md)



---



\## 🤝 Contributing



Contributions are welcome! Here's how:



1\. Fork the repository

2\. Create a feature branch (`git checkout -b feature/amazing-feature`)

3\. Commit your changes (`git commit -m 'Add amazing feature'`)

4\. Push to the branch (`git push origin feature/amazing-feature`)

5\. Open a Pull Request



See \[CONTRIBUTING.md](CONTRIBUTING.md) for details.



---



\## 📄 License



This project is licensed under the \*\*MIT License\*\* - see the \[LICENSE](LICENSE) file for details.



---



\## 🙏 Acknowledgments



\- Icons: Unicode Emoji

\- Color schemes: Custom darker professional tones

\- Inspired by modern project management tools

\- Built with ❤️ for teams who need simple, effective collaboration



---



\## 📞 Support



\- \*\*Issues:\*\* \[GitHub Issues](https://github.com/lyode/team-project-manager/issues)

\- \*\*Discussions:\*\* \[GitHub Discussions](https://github.com/lyode/team-project-manager/discussions)

\- \*\*Email:\*\* lyodengck@gmail.com



---



\## 🌟 Star History



If you find this project useful, please consider giving it a star! ⭐



---



\*\*Made with ❤️ by \[lyode ng](https://github.com/lyode)\*\*



\*Last updated: January 2025\*

