# Frontmate

Frontmate is a collaborative code editor that allows real-time collaboration on coding projects. Designed for developers, the application includes features such as live code editing, automatic syncing, and communication tools to enhance team collaboration and productivity. The frontend is deployed on Vercel, while the backend is hosted on Render for efficient performance and scalability.

## Live Demo

Experience Frontmate live here: [https://frontmate.vercel.app/](https://frontmate.vercel.app/)

---

## Features

- **Real-Time Collaboration**: Work together with your team on code in real-time.
- **Automatic Syncing**: Your code and changes are automatically synchronized across all team members.
- **Multi-language Support**: The editor supports a range of languages including JavaScript, Python, and more.
- **Customizable UI**: The interface is designed for ease of use and flexibility, tailored to your coding needs.
- **Communication Tools**: Chat, notifications, and collaborative tools integrated into the editor.

---

## Technologies Used

- **Next.js**: A React framework for building server-rendered and statically generated websites.
- **React**: A core JavaScript library for building interactive UIs.
- **Tailwind CSS**: A utility-first CSS framework for creating custom designs quickly.
- **Vercel**: A platform for frontend deployment and hosting.
- **Render**: A backend hosting and deployment solution.

---

## Environment Variables

The following environment variables are required for the project:

### Frontend (.env.local)

```
NEXT_PUBLIC_BACKEND_URL=your_backend_url
NEXT_PUBLIC_API_KEY=your_frontend_api_key
```

### Backend (.env)

```
DATABASE_URL=your_database_connection_url
SECRET_KEY=your_backend_secret_key
```

---

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn
- A Render account for hosting the backend
- A Vercel account for hosting the frontend

### Installation

1. **Clone the Repository**:

   ```
   git clone https://github.com/ayush-sharaf/frontmate.git
   cd frontmate
   ```

2. **Install Dependencies**:

   ```
   npm install
   ```

3. **Set Up Environment Variables**:

   Ensure the correct `.env.local` for the frontend and `.env` for the backend are added with relevant environment variable values.

4. **Start the Backend First**:

   - Go to the `server` folder:

     ```
     cd server
     ```

   - Install dependencies and start the backend:

     ```
     npm install
     npm start
     ```

   The backend should be running now.

5. **Run the Frontend**:

   - Open a new terminal window or tab.
   - Go to the `frontend` folder and start the frontend:

     ```
     cd frontend
     npm run dev
     ```

   Visit [http://localhost:3000](http://localhost:3000) in your browser to view the frontend.

---

## Deployment

### Frontend

1. **Deploy to Vercel**:
   - Link the repository to Vercel for deployment.
   - Add your environment variables in the Vercel dashboard.

2. **Backend Deployment**:
   - Use Render or other backend hosting services for deployment.
   - Add necessary environment variables via the Render dashboard.

3. **Test & Connect**:
   - After deployment, ensure both frontend and backend communicate via the set API URLs.

---

## Contributing

We welcome contributions to improve Frontmate! To contribute:

1. Fork the repository on GitHub.
2. Create a new branch: `git checkout -b feature-name`.
3. Implement your changes, then commit and push your code.
4. Submit a pull request for review.

---


## Acknowledgements

- Next.js for the foundation of the frontend.
- Vercel for hosting and seamless deployment.
- Render for robust backend hosting.
- Open-source libraries and communities for their contributions.
