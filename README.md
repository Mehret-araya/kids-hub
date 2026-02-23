� **Kids Hub**

Kids Hub is an interactive, educational web application for children that combines music, art, quizzes, and storytelling in a single playful experience. The front‑end is built with React and Vite, and communicates with a simple Node/Express backend (located in `back-endd/server`).

### ✨ Key Features
- **Interactive Piano** – Play notes and explore melodies using a virtual keyboard.
- **Drawing Pad** – A canvas powered by Konva where kids can draw and save their artwork.
- **Educational Quizzes** – Fun multiple‑choice quizzes that reinforce learning.
- **Story Teller** – Browse and listen to short stories read aloud.
- **User Authentication** – Register/login to save progress and access personalized content.
- **Localization** – Built–in language support for a multilingual experience.

### 🚀 Running Locally
#### Front‑end
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start development server:
   ```bash
   npm run dev
   ```
3. The app will be available at `http://localhost:5173` by default.

#### Back‑end
1. Change to the server directory:
   ```bash
   cd back-endd/server
   ```
2. Install dependencies and create a `.env` file with `MONGODB_URI` and `JWT_SECRET`.
3. Start the server:
   ```bash
   npm install
   npm start
   ```
4. The API runs on `http://localhost:3000` (can be configured in `App.js`).

> The front‑end uses `VITE_API_BASE_URL` to locate the backend; set it in a `.env` file or via environment variables.

### ⚙️ Deployment Notes
- Deploy the front‑end to Vercel, Netlify, or any static host.
- If using Vercel for the backend, create a separate project pointing to `back-endd/server`.
- Ensure `MONGODB_URI` and `JWT_SECRET` are configured as environment variables.

### 🤝 Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. Be sure to follow existing coding styles and add tests where appropriate.

### 📄 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### 📫 Contact
For questions or feedback, reach out to `mehretaraya499@gmail.com`.
