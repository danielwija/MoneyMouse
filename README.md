# MoneyMouse 💰🐭

![A cute mouse sneaking away with food](https://images.unsplash.com/photo-1425082661705-1834bfd09dca?auto=format&fit=crop&q=80)

Like a sneaky mouse in your pantry, expenses can quietly nibble away at your savings. MoneyMouse turns the tables by helping you catch those sneaky spending habits and protect your financial cheese! 🧀

## 📋 About MoneyMouse

<table>
<tr>
<td width="70%">

A full-stack financial management application developed for the Future Business Leaders of America (FBLA) Coding & Programming competition. MoneyMouse combines modern technology with intuitive design to help users track expenses and visualize their financial journey.

</td>
<td width="30%" align="center">

![FBLA Logo](./.github/assets/fbla-logo.png)

</td>
</tr>
</table>

## 🚀 Tech Stack

Our application leverages modern technologies to deliver a seamless and responsive user experience:

### Frontend
- **React (v19)** - Latest version of the popular JavaScript library for building dynamic user interfaces
- **Vite** - Next-generation frontend tooling for faster development and optimized builds
- **Material-UI** - Comprehensive library of pre-built components following Google's Material Design
- **Chart.js & Recharts** - Powerful charting libraries for creating interactive and beautiful financial visualizations
- **React Router** - Enables seamless navigation and routing in our single-page application
- **Bootstrap** - Provides responsive grid system and additional styling utilities
- **Date Management** - Utilizing Day.js and Moment.js for precise date handling and calculations
- **State Management** - React's built-in hooks and context for efficient state management

### Backend
- **Node.js** - JavaScript runtime for building scalable server-side applications
- **Express.js** - Fast, unopinionated web framework for Node.js
- **SQLite3** - Lightweight, serverless database for reliable data storage
- **CORS** - Cross-Origin Resource Sharing for secure client-server communication
- **RESTful API** - Well-structured endpoints following REST principles
- **Error Handling** - Comprehensive error handling and logging
- **Data Validation** - Server-side validation for data integrity

### Development Tools
- **ESLint** - Code linting for maintaining code quality
- **Git** - Version control for collaborative development
- **npm** - Package management and script automation
- **Development Mode** - Hot reloading for both frontend and backend
- **Chrome DevTools** - For debugging and performance optimization

### Security Features
- **Input Sanitization** - Protection against malicious inputs
- **Data Validation** - Both client and server-side validation
- **Secure Headers** - Implementation of security-related HTTP headers
- **Error Handling** - Secure error messages and logging

## 📁 Project Structure

```
.
├── client/          # Frontend React application
│   ├── src/         # Source code
│   ├── public/      # Static assets
│   └── ...
└── server/          # Backend Node.js application
    ├── server.js    # Main server file
    └── data.json    # Data storage
```

## 🛠️ Setup & Installation

### Prerequisites
- Node.js (Latest LTS version recommended)
- npm or yarn package manager

### Frontend Setup
1. Navigate to the client directory:
   ```bash
   cd client
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
   The frontend will be available at `http://localhost:5173`

### Backend Setup
1. Navigate to the server directory:
   ```bash
   cd server
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm run dev
   ```
   The backend API will be available at `http://localhost:3000`

## 📊 Features

- Personal finance tracking
- Expense management
- Data visualization with charts
- Responsive design
- Real-time updates

## 🧪 Development

- Run `npm run lint` in the client directory to check for code style issues
- Use `npm run build` to create a production build
- The server supports hot-reloading in development mode