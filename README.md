# 💊 Daily Dose - AI-Powered Medical Management

![Project Banner](https://via.placeholder.com/1200x600/1e40af/FFFFFF?text=MedSync+AI+Prescription+Manager)
*Intelligent prescription tracking with smart reminders and insightful analytics*

[![Watch the video](https://img.youtube.com/vi/nG58YcTXeRo/maxresdefault.jpg)](https://youtu.be/nG58YcTXeRo)

### [Watch this video on YouTube](https://youtu.be/nG58YcTXeRo)

## ✨ Features

### 🤖 AI-Powered Prescription Parser and Wellness analyzer
- **Smart Text Recognition**: Automatically extracts medication details from prescription images and detect user feelings
- **Natural Language Processing**: Understands dosage, frequency, feelings and instructions from text input
- **Accuracy Validation**: Cross-references parsed data for reliability

### 📅 Smart Calendar Integration
- **Google Calendar Sync**: Automatic reminder creation for medication schedules
- **Customizable Alerts**: Flexible timing and notification preferences
- **Conflict Detection**: Identifies scheduling conflicts and suggests optimizations

### 📊 Beautiful Analytics Dashboard
- **Medication Adherence Tracking**: Visualize your consistency with interactive charts
- **Dosage Trends**: Monitor medication patterns over time
- **Health Insights**: AI-generated recommendations based on your data
- **Real-time Updates**: Live data visualization with smooth animations

### 🎨 Seamless User Experience
- **Dark/Light Mode Toggle**: Choose your preferred theme with persistent settings
- **Responsive Design**: Flawless experience across all devices
- **Intuitive Interface**: Clean, modern design focused on usability
- **Accessibility First**: WCAG compliant with keyboard navigation and screen reader support

## 🚀 Tech Stack

### Frontend
- **React 18** - Modern, component-based UI with hooks
- **Tailwind CSS** - Utility-first styling with dark mode support
- **Recharts/Chart.js** - Beautiful, interactive data visualizations
- **Framer Motion** - Smooth animations and transitions

### Backend
- **Express.js** - Fast, minimalist web framework for Node.js
- **Google Calendar API** - Secure calendar integration
- **AI/ML Services** - Prescription parsing and analysis


### Quick Start
```bash
# Clone the repository
git clone https://github.com/lghuy05/daily-dose.git

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Set up environment variables
cp .env.example .env
# Configure your API keys and database URLs

# Start development servers
# Backend (runs on port 5000)
cd backend && npm run dev

# Frontend (runs on port 3000)
cd frontend && npm run dev
