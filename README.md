# 📚 GenBook - Digital EPUB Library

<div align="center">

![GenBook Banner](assets/genbook-banner.png)

**A comprehensive bilingual digital library for browsing books, tracking reading progress, and building a vibrant reading community.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Blocks](https://img.shields.io/badge/Platform-Blocks-blue.svg)](https://blocks.app)
[![Language: TypeScript](https://img.shields.io/badge/Language-TypeScript-blue.svg)](https://www.typescriptlang.org/)

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Documentation](#-documentation) • [Contributing](#-contributing)

</div>

---

## ✨ Features

### 📖 **Book Management**
- Browse extensive book collection with beautiful cover displays
- Filter by genre, author, and series
- Search functionality across titles and authors
- Alphabetical sorting for easy navigation
- Support for both standalone novels and book series

### 📊 **Reading Journal**
- Track reading progress with current page tracking
- Multi-dimensional rating system:
  - ⭐ **Overall Rating** (1-5 stars)
  - 🌶️ **Spice Rating** (heat/romance level)
  - 🖤 **Darkness Rating** (dark themes/angst)
  - 💧 **Tears Rating** (emotional impact)
- Reading status tracking (Reading, Completed, Want to Read, Paused)
- Personal notes and public community comments
- Start/completion date tracking
- Favorites system with quick access

### 👥 **Community Features**
- View community ratings and averages for all books
- Read other readers' comments and reviews
- Time-based activity feed (Today, This Week, This Month, Earlier)
- User profiles with display names and profile photos
- Discover what others are reading and rating

### 📧 **E-Reader Integration**
- Send books directly to e-reader devices via email
- Support for multiple formats (EPUB, MOBI)
- Compatible with:
  - Amazon Kindle
  - Kobo
  - Vivlio
  - Onyx Boox
  - PocketBook
  - Barnes & Noble Nook
  - Other e-readers

### 🌍 **Bilingual Support**
- Full English and Spanish translations
- Seamless language switching
- All UI elements and content translated

### 🎨 **Beautiful UI/UX**
- Vibrant literary-inspired theme
- Responsive design (mobile, tablet, desktop)
- Holiday effects system (snow, hearts, pumpkins, leaves, fireworks)
- Smooth animations and transitions
- Intuitive navigation with sidebar

### 🔐 **Authentication & Roles**
- Public browsing (no login required)
- Google OAuth login
- Email magic link authentication
- Admin role for statistics and management
- User-specific data isolation

---

## 🎯 Demo

**Live App**: [GenBook Demo](https://692fdf83115becfd6903b9ad.blocks-app.diy)

### Screenshots

<div align="center">

| Book Gallery | Book Details | Reading Journal |
|:---:|:---:|:---:|
| ![Gallery](assets/screenshots/gallery.png) | ![Details](assets/screenshots/details.png) | ![Journal](assets/screenshots/journal.png) |

| Series Library | Genre Discovery | Admin Dashboard |
|:---:|:---:|:---:|
| ![Series](assets/screenshots/series.png) | ![Genres](assets/screenshots/genres.png) | ![Admin](assets/screenshots/admin.png) |

</div>

---

## 🛠️ Tech Stack

### **Frontend**
- **Framework**: React 18 with TypeScript
- **UI Library**: shadcn/ui (Radix UI primitives)
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Routing**: React Router
- **State Management**: React Hooks (useState, useEffect, useMemo, useCallback)

### **Backend**
- **Platform**: Blocks AI App Builder
- **Database**: PostgreSQL (managed by Blocks)
- **Authentication**: OAuth 2.0 (Google), Magic Links
- **File Storage**: Blocks File Storage
- **Email**: Gmail API integration

### **Key Libraries**
- `date-fns` - Date manipulation
- `react-markdown` - Markdown rendering
- `@radix-ui/*` - Accessible UI primitives

---

## 📁 Project Structure
