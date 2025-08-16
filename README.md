QuickForm is a lightweight, cross-platform mobile app designed to collect ideas, feedback, and uploads from users — even when offline. Built with Flutter, Python (FastAPI), and SQLite, it’s optimized for real-world deployment, especially in communities with limited connectivity.

## 🎯 Purpose

Empower users to share ideas, questions, and campaign feedback with minimal friction. Every submission becomes part of the movement’s story — teachable, remixable, and emotionally resonant.

## 🛠️ Tech Stack

| Layer         | Technology         | Role                                  |
|---------------|--------------------|----------------------------------------|
| Frontend      | Flutter             | Form UI, offline caching, sync status |
| Backend       | Python (FastAPI)    | API endpoints, validation, file handling |
| Local Storage | SQLite              | Offline form storage, sync queue      |

## ✨ Features

- 📝 Submit ideas, feedback, and optional file/image
- 📶 Offline mode with auto-sync when online
- 🔔 Submission status: Pending / Synced / Reviewed
- 🌐 Multilingual toggle (Bahasa ↔ English)
- 🎙️ Optional voice-to-text input (future phase)

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-org/quickform.git
cd quickform

