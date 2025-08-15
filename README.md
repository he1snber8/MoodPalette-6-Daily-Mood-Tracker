# MoodPalette-6-Daily-Mood-Tracker

A simple and visually appealing web app that allows users to log their daily moods and view them as a colorful calendar heatmap.

## Tech Stack
- Vue.js

## Requirements
- Mood selection interface (Hint: Use emoji or color buttons for mood selection)
- Calendar heatmap display (Hint: Map moods to colors and show them on a monthly grid)
- Local storage persistence (Hint: Save moods locally so data stays after refresh)

## Installation
1. Ensure you have Node.js (>=12.x) and npm or yarn installed.
2. Clone the repository:
   bash
   git clone https://github.com/your-username/MoodPalette-6-Daily-Mood-Tracker.git
   cd MoodPalette-6-Daily-Mood-Tracker
   
3. Install dependencies:
   bash
   npm install
   # or
   yarn install
   
4. Start the development server:
   bash
   npm run serve
   # or
   yarn serve
   

_No environment variables are required for this project._

## Usage
1. Open your browser and navigate to the address shown in the terminal (usually http://localhost:8080).
2. On the main screen, select an emoji or color button that represents your current mood.
3. Your mood will be recorded for the current date and displayed on the calendar heatmap.
4. Hover over any date cell to see the exact mood entry.
5. Refresh or reopen the app—your data is saved in local storage and will persist.

## Implementation Steps
1. Initialize a new Vue.js project using Vue CLI.
2. Create a `MoodSelector.vue` component with a set of emoji/color buttons.
3. Build a `HeatmapCalendar.vue` component that renders a monthly grid and maps mood values to colors.
4. Implement local storage functions to save and retrieve mood entries by date.
5. Wire up state management (using Vue's reactive data or Vuex) to share mood data between components.
6. Add CSS styles or a utility-first library (e.g., Tailwind CSS) to make the UI visually appealing.
7. Test the application in different browsers to ensure calendar rendering and data persistence work correctly.

<!-- No API endpoints are needed since all data is stored locally -->