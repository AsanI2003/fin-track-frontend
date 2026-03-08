# Fin-Track Frontend 💳

The user-facing dashboard for Fin-Track, a modern personal finance and subscription manager. Built with a focus on minimalism, speed, and real-time data visualization.

## 🚀 Features
- **Interactive Dashboard**: Real-time summary of balance, income, and expenses.
- **Visual Analytics**: Dynamic charts (Recharts/Chart.js) to track spending habits over time.
- **Subscription Management**: Track recurring payments and get notified before they are due.
- **Responsive UI**: Optimized for mobile and desktop using Tailwind CSS.
- **Secure Auth**: Integration with JWT-based authentication flows.

## 🛠️ Tech Stack
- **Library**: React.js (Vite)
- **Styling**: Tailwind CSS
- **State Management**: Context API / Zustand
- **Data Fetching**: Axios
- **Icons & UI**: Lucide React / Shadcn UI

## 📦 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/AsanI2003/fin-track-frontend.git](https://github.com/AsanI2003/fin-track-frontend.git)
   cd fin-track-frontend <br> <br>
Install dependencies: <br>
npm install <br> <br>

Configure Environment: <br>
Create a .env file in the root:<br>
VITE_API_BASE_URL=http://localhost:5000/api  <br> <br>

Run the development server:   <br>
npm run dev    <br>  <br> 

Project Structure  <br> 
src/  <br> 
├── components/   # Reusable UI components (Buttons, Inputs, Cards)  <br> 
├── hooks/        # Custom hooks for API calls and logic <br> 
├── pages/        # Dashboard, Login, Signup, Transactions <br> 
├── services/     # API integration logic using Axios <br> 
└── utils/        # Formatting and helper functions <br>  <br> 
