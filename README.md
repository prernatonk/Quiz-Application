# Quiz-Application
Core Features:

Interactive quiz with multiple-choice questions
Three difficulty levels: Easy, Medium, and Hard
Progress tracking
Immediate feedback on answers
Final score display
Project Structure:

Components:

App.tsx: Main component managing quiz state and flow
QuizCard.tsx: Displays questions and answer options
ProgressBar.tsx: Shows quiz progress
Results.tsx: Displays final score
DifficultySelector.tsx: Allows users to choose difficulty level
Data:

questions.ts: Contains quiz questions with varying difficulty levels
Easy: 5 general knowledge questions
Medium: 10 questions (includes easy questions)
Hard: 15 questions (includes all questions)
Features Breakdown:
Difficulty Levels:

Easy: Basic knowledge questions
Medium: More challenging questions
Hard: Advanced scientific concepts
Question Display:

Clear question text
Multiple choice options
Visual feedback for correct/incorrect answers
Icons and color coding for better UX
Progress Tracking:

Progress bar showing current question number
Percentage completion
Current score tracking
Results:

Final score display
Performance feedback
Option to restart quiz
Technical Implementation:

Built with React and TypeScript
Styled with Tailwind CSS
Uses Lucide React for icons
State management with React hooks
Responsive design for all screen sizes
User Flow:
User selects difficulty level
Questions are filtered based on difficulty
User answers questions one by one
Immediate feedback after each answer
Final results shown after completing all questions
Option to restart with different difficulty

