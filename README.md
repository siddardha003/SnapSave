<div align="center">
<h1 align="center">SnapSave - A Smart Storage Solution</h1>
</div>

<table>
  <tr>
    <td width="30%" align="center">
      <img src="public/assets/icons/snapsave_favicon.png" alt="Project Banner" width="250"/>
    </td>
    <td width="70%">
      <p>
        <b>A Storage Management and File Sharing Platform that lets users effortlessly upload, organize, and share files. 
        Built with the Next.js and the Appwrite Node SDK, utilizing advanced features for seamless 
        file management.</b> <br/><br/>
        <b>🔗 Live Demo:</b> https://snap-save.vercel.app
      </p>
    </td>
  </tr>
</table>

## <a name="tech-stack">⚙️ Tech Stack</a>
<div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
</div>

## <a name="features">🔋 Features</a>

👉 **User Authentication with Appwrite**: Implement signup, login, and logout functionality using Appwrite's authentication system.

👉 **FIle Uploads**: Effortlessly upload a variety of file types, including documents, images, videos, and audio, ensuring all your important data.

👉 **Manage Files**: Users can browse, download, view, rename & delete their uploaded files.

👉 **File Sharing**: Users can easily share their uploaded files with others, enabling collaboration and easy access to important content.

👉 **Dashboard**: Dynamic dashboard that showcases total and consumed storage, recent uploads, and a summary of files grouped by type.

👉 **Global Search**: Users can quickly find files and shared content across the platform with a robust global search feature.

👉 **Sorting Options**: Organize files efficiently by sorting them by date, name, or size, making file management a breeze.

👉 **Modern Responsive Design**: A fresh and minimalist UI that emphasizes usability, ensuring a clean aesthetic across all devices.

## <a name="quick-start">🤸 Quick Start</a>

### 1. Clone the Repository
```bash
git clone https://github.com/siddardha003/SnapSave.git
cd SnapSave

# Install the dependencies
npm install
```

### 2. Set Up Environment Variables
```env
# Create a new file named `.env.local` in the root of your project
NEXT_PUBLIC_APPWRITE_ENDPOINT=""
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""
```

### 3. Running the Project
```bash
# Start Development Server
npm run dev

# Open http://localhost:3000 to view the project.
```

## <a name="Screenshots">📸 Screenshots</a>

<table>
  <tr>
    <td align="center" width="50%">
      <h3>Login Page</h3>
      <img src="public\assets\images\authscreen.png" alt="Login Page" width="100%"/>
    </td>
    <td align="center" width="50%">
      <h3>Dashboard</h3>
      <img src="public\assets\images\dashboard.png" alt="Dashboard" width="100%"/>
    </td>
  </tr>
</table>
