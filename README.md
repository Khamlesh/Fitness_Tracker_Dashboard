# Fitness Tracker Dashboard

A comprehensive web application for tracking fitness activities, displaying statistics, and recommending personalized workout plans. Built with React, TypeScript, and Tailwind CSS.

## 🎯 Features

### 📊 Dashboard Overview
- **Real-time Metrics**: View daily calories burned, workout time, and progress
- **Quick Actions**: Log workouts, set goals, and schedule activities
- **Progress Tracking**: Visual progress bars for daily and weekly goals
- **Recent Activities**: Quick overview of today's fitness activities

### 🏃‍♂️ Activity Tracking
- **Multiple Activity Types**: Running, walking, cycling, swimming, weightlifting, yoga, and more
- **Detailed Logging**: Track duration, calories, distance, and add notes
- **Search & Filter**: Find activities by type, date, or notes
- **CRUD Operations**: Add, edit, and delete fitness activities

### 📈 Statistics & Analytics
- **Weekly Progress Charts**: Bar charts showing daily calorie burn
- **Activity Distribution**: Pie charts for workout type breakdown
- **Monthly Trends**: Line charts for long-term progress tracking
- **Performance Metrics**: Average workout duration, total distance, calories per hour
- **Recent Highlights**: Top performing activities

### 💪 Personalized Workout Plans
- **AI-Powered Recommendations**: Based on fitness goals and activity level
- **Difficulty Levels**: Beginner, intermediate, and advanced plans
- **Custom Plans**: Create your own workout routines
- **Exercise Library**: Detailed instructions for each exercise
- **Progress Tracking**: Monitor plan completion and progress

### 👤 User Profile Management
- **Personal Information**: Age, weight, height, fitness goals
- **Health Metrics**: BMI calculation and body composition tracking
- **Goal Setting**: Customizable daily calories, weekly workouts, weight goals
- **Activity Level**: Sedentary to very active lifestyle options
- **Profile Customization**: Edit personal details and preferences

## 🚀 Technology Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom design system
- **Charts**: Recharts for data visualization
- **Icons**: Lucide React for beautiful icons
- **State Management**: React Context API with useReducer
- **Routing**: React Router DOM for navigation
- **Date Handling**: date-fns for date manipulation
- **Animations**: Framer Motion for smooth transitions

## 🛠️ Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd fitness-tracker-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### Build for Production

```bash
npm run build
```

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   └── Sidebar.tsx     # Navigation sidebar
├── context/            # React context for state management
│   └── FitnessContext.tsx
├── pages/              # Main application pages
│   ├── Dashboard.tsx   # Main dashboard view
│   ├── Activities.tsx  # Activity tracking page
│   ├── Statistics.tsx  # Analytics and charts
│   ├── WorkoutPlans.tsx # Workout plan management
│   └── Profile.tsx     # User profile and settings
├── App.tsx             # Main application component
├── index.tsx           # Application entry point
└── index.css           # Global styles and Tailwind imports
```

## 🎨 Design System

### Color Palette
- **Primary**: Blue gradient (#0ea5e9 to #0369a1)
- **Success**: Green (#10b981)
- **Warning**: Orange (#f59e0b)
- **Error**: Red (#ef4444)
- **Info**: Blue (#3b82f6)
- **Purple**: (#8b5cf6)

### Components
- **Cards**: Clean, rounded containers with subtle shadows
- **Buttons**: Consistent button styles with hover effects
- **Forms**: Accessible form inputs with focus states
- **Metrics**: Gradient backgrounds for key statistics
- **Charts**: Responsive chart containers with proper spacing

## 🔧 Customization

### Adding New Activity Types
1. Update the `Activity` interface in `FitnessContext.tsx`
2. Add new type to the activity type union
3. Update the activity form in `Activities.tsx`
4. Add corresponding icons and colors

### Creating Custom Workout Plans
1. Define exercise structure in the `Exercise` interface
2. Add new plan templates in `WorkoutPlans.tsx`
3. Update recommendation logic based on user preferences

### Styling Modifications
- Modify `tailwind.config.js` for custom colors and animations
- Update component classes in individual files
- Add new utility classes in `src/index.css`

## 📱 Responsive Design

The application is fully responsive and works on:
- **Desktop**: Full-featured dashboard with side-by-side layouts
- **Tablet**: Optimized layouts for medium screens
- **Mobile**: Stacked layouts with touch-friendly interactions

## 🚀 Performance Features

- **Lazy Loading**: Components load only when needed
- **Memoization**: Optimized calculations with useMemo
- **Efficient State Updates**: Minimal re-renders with proper state management
- **Responsive Charts**: Charts adapt to container size changes

## 🔒 Data Management

- **Local State**: All data stored in React context
- **Persistent Storage**: Ready for localStorage or backend integration
- **Data Validation**: Form validation and error handling
- **Real-time Updates**: Immediate UI updates on data changes

## 🧪 Testing

```bash
# Run tests
npm test

# Run tests with coverage
npm test -- --coverage
```

## 📦 Deployment

### Build and Deploy
```bash
npm run build
```

The build folder contains optimized production files ready for deployment to:
- Netlify
- Vercel
- AWS S3
- Any static hosting service

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **Icons**: Lucide React for beautiful, consistent icons
- **Charts**: Recharts for powerful data visualization
- **Styling**: Tailwind CSS for utility-first styling
- **Design Inspiration**: Modern fitness and health applications

## 📞 Support

For questions or support, please open an issue in the repository or contact the development team.

---

**Built with ❤️ for fitness enthusiasts everywhere**
