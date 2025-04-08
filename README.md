# Microbiology Lab Week Game 2025 🔬🧪

Welcome to the **Microbiology Lab Week Game 2025**! This is a fun, interactive browser game created to celebrate Lab Week, focusing on the core microbiology skill of Gram staining and microscopic identification.

## 🎮 How to Play

This game is designed as a **single, self-contained HTML file**. No installation or internet connection (after downloading) is required!

1.  **Download:** Get the `[YourFileName].html` file (replace `[YourFileName]` with the actual name you saved it as, e.g., `microbiology_game.html`).
2.  **Open:** Simply double-click the downloaded HTML file. It will open in your default web browser (Chrome, Firefox, Edge, Safari, etc.).
3.  **Play!** Follow the on-screen prompts to enter your name and begin the game.

**Note:** The Hall of Fame uses your browser's `localStorage`. This means scores are saved *only* on the specific computer and browser you are playing on. Clearing browser data will clear the Hall of Fame.

## ✨ Game Flow & Features

The game takes you through a simulated STAT Gram stain process:

1.  **Start Screen:**
    *   Enter your name to play.
    *   View the "Happy Lab Week 2025 from Micro/Molecular!" banner.
    *   Option to view the Hall of Fame before starting.
    *   Background microbiology-themed decorations.
2.  **Intro Sequence:**
    *   "Your shift starts..."
    *   "Bark Bark Bark!" - Alert for a positive blood culture!
3.  **Prepare Smear Mini-Game:**
    *   Drag and drop items in the correct sequence:
        1.  Alcohol Wipe ➔ BC Bottle Top
        2.  Needle ➔ BC Bottle Top
        3.  BC Bottle ➔ Slide Area
    *   Visual feedback provided for each step.
4.  **Fixing the Slide:**
    *   Instruction screen after successful smear prep.
    *   Click "Fix the Slide!" button.
    *   Confirmation screen with a simple visual effect simulating fixing.
    *   Click "Stain the Slide!" to proceed.
5.  **Phase 1: Gram Staining:**
    *   Drag the reagent bottles (Crystal Violet, Iodine, Decolorizer, Safranin) onto the slide graphic in the **correct order**.
    *   Reagent bottles appear in a **random order** each time.
    *   The "smear" on the slide visually changes color with correct reagent application (including a "wash" effect for decolorizer).
    *   Hover over reagent bottles for tooltips explaining their function.
    *   **Crucially:** Dropping the **wrong reagent** at any step results in immediate game failure!
6.  **Phase 2: Microscope Identification:**
    *   Transition to a simulated microscope view (dark background, bright field).
    *   View a randomly selected Gram stain image (GPC Clusters, GPC Chains, GPR, GNR, or GNC).
    *   Select the correct morphology description from multiple-choice buttons.
7.  **Victory Screen:**
    *   Displayed upon correct identification in Phase 2.
    *   Shows a congratulatory message with your name.
    *   Your name is added to the Hall of Fame (if not already present).
    *   Background victory flair/decorations.
    *   Options to Play Again or View Hall of Fame.
8.  **Failure Screen:**
    *   Displayed upon incorrect reagent use in Phase 1 OR incorrect identification in Phase 2.
    *   Shows the "Game Over" message and the funny "Goldie/Write-up" flair with an incident report graphic.
    *   If failure occurred in Phase 2, it displays the correct morphology.
    *   Options to Try Again, View Hall of Fame, or Go Back to Start.
9.  **Hall of Fame:**
    *   Displays a list of all players who have successfully completed the game on that browser.
    *   Includes a button to **Clear the Hall of Fame** (with confirmation).
    *   Options to Play Again or Go Back to Start.

## 💻 Technology Used

*   **HTML:** Structure and content.
*   **CSS:** Styling, layout (Flexbox), backgrounds, visual effects (shadows, glows), simple animations (@keyframes).
*   **JavaScript:** Game logic, DOM manipulation, event handling (click, drag & drop), `localStorage` for persistence, randomization (`Math.random`).
*   **SVG:** Embedded vector graphics for icons, decorations, banner elements, and the "Goldie" report, ensuring crisp visuals and self-containment.

---

Have fun celebrating Lab Week! 🎉
