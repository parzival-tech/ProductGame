# Product vs. Project Management Challenge

This is an interactive game designed to help users understand the key differences between product management and project management by dragging statements to the correct role.

## How to Play

1.  Open the `index.html` file in a web browser.
2.  The game will start automatically.
3.  Read the statement presented in the middle of the screen.
4.  Drag the statement card to either the "Product Management" zone or the "Project Management" zone based on which role it best describes.
5.  Receive immediate feedback on your choice:
    *   **Correct**: The zone will pulse green, your score will increase, and a success message will appear.
    *   **Incorrect**: The zone will shake, and a message indicating the correct category will appear.
6.  Click the "Next Statement" button to proceed (if available).
7.  Continue until all statements have been categorized.
8.  At the end of the game, your final score and the total number of correct answers will be displayed.
9.  Click "Restart Game" to play again.

## Features

*   **Interactive Drag and Drop**: Engage with game elements directly.
*   **Immediate Feedback**: Learn instantly if your choice is correct or incorrect with visual cues and messages.
*   **Score Tracking**: See your score update in real-time.
*   **Responsive Design**: Adapts to different screen sizes for a good experience on desktop and mobile (touch-enabled).
*   **Clear UI**: User-friendly interface styled with Tailwind CSS.

## Technical Details

*   **Frontend**: Built with HTML, vanilla JavaScript, and Tailwind CSS (via CDN).
*   **Game Logic**: All game logic, including statement shuffling, drag/drop handling, scoring, and feedback, is contained within the `<script>` tag in `index.html`.
*   **Styling**: Primarily handled by Tailwind CSS classes directly in the HTML, with some additional custom CSS in an inline `<style>` tag for animations and specific component styling.

This game is a self-contained HTML file and requires no additional setup to run, other than opening it in a modern web browser.
