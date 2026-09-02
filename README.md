# Diary Verse (SilentLines)

> **A safe, emotional, and private online diary to write freely, save what matters, or burn and release what hurts.**

---

## ⚠️ Important Notices & Backend Connection

> [!IMPORTANT]
> - **Port 2228 Requirement:** Always run the development server on port **`2228`** (`http://localhost:2228`) to ensure correct backend connection and CORS authorization.
> - **Backend / CORS Access:** If you cannot access the backend, it means the administrator of Diary Verse has disabled CORS. Without admin approval or proper CORS configuration, backend connectivity may be restricted.
> - **Enable CORS for Testing:** If you need CORS enabled to verify backend integration, please reach out to us:
>   - 📧 **Email:** [DiaryVerse@snapcourse.in](mailto:DiaryVerse@snapcourse.in)

---

## ✨ Features

- ✍️ **Private Journaling:** Write and reflect with an expressive, clean text editor.
- 🔥 **Burn Notes:** Emotionally release negative thoughts by virtually burning entries.
- 💾 **Save & Organize:** Keep meaningful memories secure and accessible.
- 🎭 **Mood Tracking & Calendar:** Log your daily mood and visualize your emotional journey over time.
- 🎵 **Ambient Background Music:** Focus and relax with curated audio options.
- 📱 **PWA Ready:** Progressive Web App support for installation across desktop and mobile devices.
- 🔒 **Privacy First:** Built with user privacy and safety as core values.

---

## 🛠️ Tech Stack

- **Frontend:** [React 18](https://react.dev/) + [Vite 7](https://vite.dev/)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Routing:** [React Router v7](https://reactrouter.com/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **Authentication:** Auth0 / Mock Auth
- **PWA:** `vite-plugin-pwa`

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18+ recommended)
- `npm` or `yarn`

### 1. Clone & Install Dependencies

```bash
git clone <repository-url>
cd diaryentry-main
npm install
```

### 2. Configure Environment Variables

Create a `.env` file in the root directory (based on `.env.example`):

```env
# API Endpoint URL
VITE_API_URL=https://diary.snapcourse.in/diaryapi

# Toggle for Mock Auth Mode (true/false)
VITE_USE_MOCK_AUTH=false
```

### 3. Run Locally

Start the Vite development server on port `2228`:

```bash
npm run dev
```

The application will be accessible at:
👉 **[http://localhost:2228/](http://localhost:2228/)**

### 4. Build for Production

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

## 🤝 Contributing & Support

We aspire to make **Diary Verse** popular worldwide to provide a peaceful and private mental space for everyone. We warmly welcome your support and contributions!

- If you would like to contribute improvements or features, feel free to fork the repository, make your changes, and submit a pull request.
- For questions, feedback, or backend permissions, contact us at **[DiaryVerse@snapcourse.in](mailto:DiaryVerse@snapcourse.in)**.
