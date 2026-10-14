# Coding Blogs — Frontend

A web application for publishing, reading, and exploring programming-related articles. Coding Blogs aims to provide developers with a place to share technical knowledge, discover tutorials, and learn about software development.

## ✨ Features

- 📝 Browse and read technical blog posts
- 🔍 Discover programming-related content
- 📚 Explore articles by topic or category, if supported
- ✍️ Create and manage blog posts, if supported
- 👤 User authentication and profile management, if supported
- 📱 Responsive interface for desktop and mobile devices

## 🛠️ Tech Stack

- **Frontend:** Angular 16
- **Language:** TypeScript
- **Styling:** SCSS, Tailwind
- **API Integration:** REST API
- **Package Manager:** npm

## 🚀 Getting Started

### Prerequisites

- Node.js
- npm

### Installation

```bash
git clone https://github.com/fsd-freelancers/codingBlogs.git
cd codingBlogs
npm install
```

### Configuration

Configure the backend API URL using the environment configuration supported by your frontend.

Example:

```env
API_BASE_URL=http://localhost:3000
```

### Run the Application

Use the development command defined in your `package.json`. For example:

```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

## 🔗 Backend Integration

The frontend communicates with the backend API to retrieve or manage blog content and other application data supported by the project.

Ensure that the API URL, authentication configuration, and CORS settings match the backend.

## 🔒 Security

- Validate user inputs.
- Handle API errors appropriately.
- Keep private credentials out of frontend code.
- Use secure authentication and authorization flows where applicable.

- GitHub: [fsd-freelancers](https://github.com/fsd-freelancers)
- Repository: [codingBlogs](https://github.com/fsd-freelancers/codingBlogs)

---

Built for developers who enjoy sharing knowledge.
