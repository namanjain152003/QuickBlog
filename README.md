# QuickBlog

QuickBlog is an AI-powered blogging platform that allows users to generate and manage blog content effortlessly. It is designed to provide a seamless content creation experience.

## Features
* AI-powered blog generation
* User authentication and management
* Create, edit, and delete blog posts
* Responsive and clean UI
* Optimized media handling with ImageKit
* Backend built with Node.js and Express
* Data stored in MongoDB

## Technologies Used
* Frontend: React.js (in client folder)
* Backend: Node.js, Express.js (in server folder)
* Database: MongoDB
* Media Optimization: ImageKit
* AI Integration: Gemini API

# Installation
1. Clone the repository:
```bash
git clone https://github.com/namanjain152003/QuickBlog
cd quickblog
```

2. Backend Setup (server folder):
```bash
cd server
npm install
```

3. Set up environment variables (server/.env):
```bash
MONGODB_URI=<your-mongodb-uri>
GEMINI_API_KEY=<your-api-key>
IMAGEKIT_PUBLIC_KEY=<your-imagekit-public-key>
IMAGEKIT_PRIVATE_KEY=<your-imagekit-private-key>
IMAGEKIT_URL_ENDPOINT=<your-imagekit-private-key>
JWT_SECRET =<your-secret>
ADMIN_EMAIL=<your-admin-email>
ADMIN_PASSWORD=<your-admin-password>
```

4. Start the backend server:
```bash
npm run server
```

5.Frontend Setup (client folder):
```bash
cd ../client
npm install
```

6. Set up environment variables (client/.env):
```bash
VITE_BASE_URL= http://localhost:3000
VITE_ADMIN_EMAIL=<your-admin-email>
VITE_ADMIN_PASSWORD=<your-admin-password>
```

7. Start the frontend:
```bash
npm run dev
```


