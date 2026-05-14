# Fin-Track-Frontend

The user-facing dashboard for Fin-Track, a modern personal finance and subscription manager. Built with a focus on minimalism, speed, and real-time data visualization.

# Highlights

# Dashboard
<img width="919" height="417" alt="Screenshot 2026-05-14 135730" src="https://github.com/user-attachments/assets/05afbc30-8443-4e94-a571-f39da97fee69" />


# FinTrack AI
<img width="935" height="401" alt="Screenshot 2026-05-14 135916" src="https://github.com/user-attachments/assets/9fe438de-b28c-407c-a6be-f61e5504729b" />


## Features
- **Interactive Dashboard**: Real-time summary of balance, income, and expenses.
- **AI Chatbot**: personalized chat bot built using Groq AI
- **Visual Analytics**: Dynamic charts (Recharts/Chart.js) to track spending habits over time.
- **Subscription Management**: Track recurring payments and get notified before they are due.
- **Responsive UI**: Optimized for mobile and desktop using Tailwind CSS.
- **Secure Auth**: Integration with JWT-based authentication flows.

## Tech Stack
- **Library**: React.js (Vite)
- **Styling**: Tailwind CSS
- **State Management**: Context API / Zustand
- **Data Fetching**: Axios
- **Icons & UI**: Lucide React / Shadcn UI

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/AsanI2003/fin-track-frontend.git](https://github.com/AsanI2003/fin-track-frontend.git)
   cd fin-track-frontend 
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
