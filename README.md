# Learning-Cursive
A learning environment to help kids learn how to write in cursive.
# What I Made
I created an interactive app for kids to learn how to write cursive. Users practice by tracing cursive letters on-screen with a pen tool. The app includes a fun, cartoony interface designed to make handwriting practice feel like a game rather than a task.
# How It Works
1. The user chooses a writing tool — pencil, marker, or crayon.
2. A random cursive letter appears on the screen.
3. The user traces the letter with the selected tool.
4. The app analyzes accuracy by comparing the user’s stroke pattern to the sample letter.
5. It provides feedback and a score based on how closely the user’s tracing matches the model.

This environment was designed using an interactive canvas-based UI (for example, with p5.js or Figma prototype simulation).

## Why I Made It
Handwriting practice apps often lack engagement for kids. My goal was to create a tool that combines fun interaction, freedom of choice, and visual feedback, so kids stay motivated while learning proper cursive technique.



## Design Principles and Methods

### 1. Engagement — Optimizing Choice and Autonomy
To keep users engaged, I included tool customization. Learners can select from a pencil, marker, or crayon — allowing them to express personal preference while practicing. This small choice increases a sense of ownership and enjoyment.

### 2. Representation — Illustrate Through Multiple Media
The app uses text, visuals, and interactive motion.
- Text: shows letter names and instructions
- Visuals: displays example cursive strokes
- Interactivity: real-time tracing feedback

This multimodal approach supports different learning styles and helps reinforce memory through multiple sensory channels.

### 3. Engagement — Sustaining Effort and Persistence
The app encourages continued effort by providing action-oriented feedback. After each trace, it scores the accuracy and displays encouraging prompts like “Nice curves!” or “Try keeping your loops smoother next time!”



## How We Measure Learning
The system measures learning through:
- Accuracy scores (percentage match to model letter)
- Progress tracking (average improvement across attempts)
- Consistent feedback patterns (whether users correct specific errors like spacing or slant)

Learning is demonstrated when users show higher accuracy scores and smoother letter formations after several attempts.



## Test Results

### 1 Instance Where the Environment Did Well
The feedback scoring system worked smoothly and motivated users to retry letters. Test users enjoyed seeing their improvement visualized after each attempt.

### 1 Instance Where It Struggled
The pen tool input sometimes lagged, especially when switching tools mid-session. This caused tracing strokes to appear slightly delayed.

### 2 Suggestions for Improvement
1. Optimize pen input responsiveness — reduce delay when users switch tools.
2. Add progression levels — for example, users unlock words after mastering individual letters to make practice feel more like a journey.


## How to Run
1. https://v0-cursive-writing-app.vercel.app
3. Use the mouse or stylus to start tracing letters.
4. Switch tools with the toolbar on the left.
