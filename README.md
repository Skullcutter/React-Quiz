# React Quiz

A modern, interactive quiz application built with React that tests your knowledge of React concepts. This project demonstrates advanced React patterns including useReducer for state management, component composition, and timer functionality.

## 🌟 Key Features

- **Interactive Quiz Interface**: Clean, modern UI with smooth transitions.

- **Timer Functionality**: Each quiz session has a time limit to add challenge.

- **Progress Tracking**: Visual progress bar showing current question and completion status.

- **Score System**: Points awarded based on correct answers with highscore tracking.

- **State Management**: Complex state handled efficiently with useReducer.

- **Component Architecture**: Well-organized, reusable component structure.

- **Error Handling**: Graceful error states for better user experience.

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/react-quiz-app.git
   cd react-quiz-app
   ```

2. **Install dependencies**

   ```bash
   npm install
     # or
   yarn install
   ```

3. **Start the JSON server (for questions data)**

     ***Note: Make sure that server runs smoothly, properly***
  
   - **Inside ```package.json``` file include:**
      ```
      "server": "json-server --watch data/questions.json --port 8000"
      ```
      
   - **Then start the server to run app smoothly**
      ```
      npm run server
      ```


4. **Start the development server**

   ```bash
   npm start
   # or
   yarn start
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000` to view the app.

## 📁 Project Structure

```
src/
├── Components/
│   ├── App.js              # Main application component
│   ├── Header.js           # App header with logo
│   ├── Main.js             # Main content wrapper
│   ├── StartScreen.js      # Welcome screen
│   ├── Question.js         # Question display component
│   ├── Options.js          # Answer options component
│   ├── NextButton.js       # Navigation button
│   ├── Progress.js         # Progress indicator
│   ├── Timer.js            # Countdown timer
│   ├── FinishScreen.js     # Results screen
│   ├── Footer.js           # Footer wrapper
│   ├── Loader.js           # Loading component
│   └── Error.js            # Error display component
|   └──  DateCounter.js     # Example useReducer implementation
├── index.css              # Global styles
└── index.js               # App entry point
```

## 🎮 How to Use

1. **Start Quiz**: Click "Let's start" button on the welcome screen.

2. **Answer Questions**: Select your answer from the multiple choice options.

3. **Navigate**: Use "Next" button to proceed to the next question.

4. **Complete**: View your results and highscore on the finish screen.

5. **Restart**: Click "Restart quiz" to try again.

## 🎯 Learning Objectives

This project demonstrates several important React concepts:

### Core React Concepts

- **useReducer Hook**: Complex state management with actions and reducers.

- **useEffect Hook**: Side effects for data fetching and timers.

- **Component Composition**: Building complex UIs from smaller components.

- **Props Drilling**: Passing data between components.

- **Conditional Rendering**: Dynamic UI based on application state.

### Advanced Patterns

- **State Machine Pattern**: Managing different application states (loading, ready, active, finished).

- **Action Dispatching**: Centralized state updates through actions.

- **Timer Implementation**: Real-time countdown with cleanup.

- **Error Boundaries**: Graceful error handling and user feedback.

## 🛠️ Technologies Used

- **React 18**: Latest React with hooks.

- **JavaScript (ES6+)**: Modern JavaScript features.

- **CSS3**: Custom properties, flexbox, grid.

- **JSON Server**: Mock REST API for development.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
