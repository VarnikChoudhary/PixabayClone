# Pixabay Clone 📸

A fully responsive image gallery application built with **React.js** and **Tailwind CSS**, powered by the **Pixabay API**. This project allows users to search for high-quality images, filter them by categories, and view detailed information about each image.

## ✨ Features
- **Image Search:** Real-time search functionality to find specific images.
- **Responsive Design:** Fully optimized for mobile, tablet, and desktop views using Tailwind CSS.
- **Image Details:** Click on an image to view detailed information (views, downloads, tags, etc.).
- **Dynamic Filtering:** Browse images based on trending tags and categories.
- **Infinite/Pagination Support:** Efficiently browse through thousands of images provided by the Pixabay API.

## 🛠️ Technologies Used
- **Frontend:** [React.js](https://reactjs.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **API:** [Pixabay API](https://pixabay.com/api/docs/)
- **Icons:** Lucide React / FontAwesome (if applicable)
- **Deployment:** Netlify / Vercel

## 📦 Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites
- [Node.js](https://nodejs.org/) (v14.0 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- A Pixabay API Key (Get it for free [here](https://pixabay.com/api/docs/))

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/VarnikChoudhary/PixabayClone.git
   cd PixabayClone
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Environment Setup:**
   Create a `.env` file in the root directory and add your Pixabay API key:
   ```env
   REACT_APP_PIXABAY_API_KEY=your_api_key_here
   ```

4. **Start the development server:**
   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000`.

## 📂 Project Structure
```text
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable UI components (Navbar, SearchBar, ImageCard)
│   ├── pages/           # Main application pages (Home, ImageDetails)
│   ├── App.js           # Main application logic
│   ├── index.js         # Entry point
│   └── index.css        # Global styles & Tailwind imports
├── tailwind.config.js   # Tailwind CSS configuration
└── package.json         # Project dependencies and scripts
```

## 📜 Available Scripts

In the project directory, you can run:

- `npm start`: Runs the app in development mode.
- `npm run build`: Builds the app for production to the `build` folder.
- `npm test`: Launches the test runner.

## 🤝 Contributing
Contributions are welcome! If you have ideas for improvements or find any bugs, feel free to open an issue or submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

---
**Created by [Varnik Choudhary](https://github.com/VarnikChoudhary)**
