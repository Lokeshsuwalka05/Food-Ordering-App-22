# 🍽️ Namaste React — Swiggy Clone

> A fully functional Swiggy-style food delivery frontend application built following [Akshay Saini's Namaste React Live Course](https://namastedev.com/learn/namaste-react)

[![React](https://img.shields.io/badge/React-19.1.0-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-2.8.2-764ABC?logo=redux&logoColor=white)](https://redux-toolkit.js.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.11-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Parcel](https://img.shields.io/badge/Parcel-2.15.4-E9B13C?logo=parcel&logoColor=white)](https://parceljs.org/)

## ✨ Features

- ⚛️ **Modern React** — Built with React 19 and functional components using Hooks
- 🔄 **State Management** — Redux Toolkit for efficient and scalable state management
- 🧭 **Routing** — React Router v7 for seamless navigation and dynamic routing
- 🎨 **Styling** — Tailwind CSS with utility-first approach for responsive design
- 📦 **Fast Bundling** — Parcel bundler for lightning-fast development experience
- 🍽️ **Restaurant Browsing** — Browse restaurants with Swiggy-like UI/UX
- 🔍 **Smart Search** — Real-time search and filter functionality
- 🛒 **Shopping Cart** — Add items to cart with quantity management
- 🌐 **Live Data** — Integration with real-time Swiggy API
- 🧪 **Well Tested** — Comprehensive test coverage using Jest and React Testing Library
- 📱 **Responsive Design** — Mobile-first approach, works on all devices

## 🎯 Demo

![App Demo](https://via.placeholder.com/800x400.png?text=Add+Your+Demo+GIF+Here)

**[🔗 Live Demo](https://your-deployment-url.com)** • **[📹 Video Walkthrough](https://youtube.com/your-video)**

## 📦 Tech Stack

### Frontend Core

| Technology    | Version | Purpose              |
| ------------- | ------- | -------------------- |
| React         | ^19.1.0 | UI library           |
| React DOM     | ^19.1.0 | React rendering      |
| React Router  | ^7.7.1  | Client-side routing  |
| Redux Toolkit | ^2.8.2  | State management     |
| React Redux   | ^9.2.0  | React-Redux bindings |

### Styling

| Technology           | Version | Purpose                     |
| -------------------- | ------- | --------------------------- |
| Tailwind CSS         | ^4.1.11 | Utility-first CSS framework |
| @tailwindcss/postcss | ^4.1.11 | PostCSS integration         |

### Build Tools

| Technology | Version | Purpose             |
| ---------- | ------- | ------------------- |
| Parcel     | ^2.15.4 | Zero-config bundler |

### Testing

| Technology            | Version | Purpose                 |
| --------------------- | ------- | ----------------------- |
| Jest                  | ^30.1.1 | Testing framework       |
| React Testing Library | ^16.3.0 | React component testing |
| Jest DOM              | ^6.8.0  | DOM testing utilities   |
| JSDOM                 | ^30.1.1 | DOM implementation      |

### Transpilation

| Technology          | Version | Purpose             |
| ------------------- | ------- | ------------------- |
| Babel Core          | ^7.28.3 | JavaScript compiler |
| @babel/preset-env   | ^7.28.3 | Modern JS support   |
| @babel/preset-react | ^7.27.1 | JSX transformation  |

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Lokeshsuwalka05/namaste-react.git
   cd namaste-react
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm start
   ```

   Open [http://localhost:1234](http://localhost:1234) in your browser

4. **Build for production**
   ```bash
   npm run build
   ```
   Production files will be in the `dist` folder

## 🧪 Testing

Run all tests:

```bash
npm test
```

Watch mode for development:

```bash
npm run test:watch
```

Coverage report:

```bash
npm run test:coverage
```

## 📁 Project Structure

```
namaste-react/
├── src/
│   ├── components/           # React components
│   │   ├── Header.js
│   │   ├── RestaurantCard.js
│   │   ├── RestaurantMenu.js
│   │   └── Cart.js
│   ├── utils/               # Utility functions & constants
│   │   ├── constants.js
│   │   ├── mockData.js
│   │   └── useRestaurantMenu.js
│   ├── redux/               # Redux store & slices
│   │   ├── store.js
│   │   └── cartSlice.js
│   ├── App.js               # Root component
│   └── index.js             # Entry point
├── __tests__/               # Test files
├── public/                  # Static assets
├── index.html               # HTML template
├── package.json
├── tailwind.config.js
├── .babelrc
└── README.md
```

## 🎨 Key Components

### Restaurant Listing

Browse restaurants with rich cards displaying cuisine, ratings, delivery time, and cost for two.

### Restaurant Menu

Detailed menu page with categories, item descriptions, and add-to-cart functionality.

### Shopping Cart

Full-featured cart with item management, quantity updates, and price calculation.

### Search & Filter

Real-time search across restaurants with smart filtering options.

## 🔧 Configuration

### Tailwind CSS

Customize your theme in `tailwind.config.js`:

```javascript
module.exports = {
  content: ["./src/**/*.{js,jsx}"],
  theme: {
    extend: {
      // Your custom theme
    },
  },
};
```

### Babel

React and modern JavaScript support configured in `.babelrc`:

```json
{
  "presets": [
    "@babel/preset-env",
    ["@babel/preset-react", { "runtime": "automatic" }]
  ]
}
```

## 🌐 Deployment

### Vercel (Recommended)

```bash
npm install -g vercel
vercel
```

### Netlify

```bash
npm run build
# Drag and drop the dist folder to Netlify
```

### GitHub Pages

```bash
npm run build
# Configure GitHub Pages to serve from dist folder
```

## 📚 Learning Resources

This project is built following the [Namaste React](https://namastedev.com/learn/namaste-react) course by Akshay Saini. Key concepts covered:

- React fundamentals and advanced patterns
- State management with Redux Toolkit
- Custom Hooks and HOCs
- Performance optimization
- Testing React applications
- Building production-ready apps

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the **ISC License** - see the LICENSE file for details.

## 👨‍💻 Author

**Lokesh Suwalka**

- GitHub: [@Lokeshsuwalka05](https://github.com/Lokeshsuwalka05)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- [Akshay Saini](https://twitter.com/akshaymarch7) for the amazing Namaste React course
- [Swiggy](https://www.swiggy.com/) for design inspiration
- The React and Redux communities for excellent documentation

## ⭐ Show Your Support

If you found this project helpful or learned something from it, please give it a ⭐ on GitHub!

---

<p align="center">Made with ❤️ and React</p>
