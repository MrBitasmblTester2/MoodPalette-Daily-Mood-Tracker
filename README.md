# MoodPalette-Daily-Mood-Tracker

## Description
A simple and visually appealing web app that allows users to log their daily moods and view them as a colorful calendar heatmap.

## Tech Stack
- React

## Requirements
- Mood selection interface (Use emoji or color buttons for mood selection)
- Calendar heatmap display (Map moods to colors and show them on a monthly grid)
- Local storage persistence (Save moods locally so data stays after refresh)

## Installation
1. Clone the repo:
   bash
   git clone https://github.com/yourusername/MoodPalette-Daily-Mood-Tracker.git
   cd MoodPalette-Daily-Mood-Tracker
   
2. Install dependencies:
   bash
   npm install
   
3. Start the app:
   bash
   npm start
   

## Usage
Open http://localhost:3000 in your browser. Select your mood each day using the emoji or color buttons. View your mood history on the calendar heatmap. Data is persisted locally and remains after page refresh.

## Implementation Steps
1. Initialize a React project using Create React App.
2. Create a `MoodSelector` component with emoji or color buttons for mood selection.
3. Implement local storage logic to save and retrieve daily mood entries.
4. Develop a `CalendarHeatmap` component that maps moods to colors and displays them on a monthly grid.
5. Integrate state management in the `App` component to track selected moods and feed data to both components.
6. Style the UI for a clean and visually appealing experience.
7. Test functionality: select moods, refresh the page, and verify that data persists and heatmap updates correctly.