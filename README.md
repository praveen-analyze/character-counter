# Real-Time Character Counter

This repository contains a simple web project that implements a **real-time character counter** for a text area.  
The counter updates as the user types and displays how many characters have been typed and how many remain.

Repository: https://github.com/praveen-analyze/character-counter.git

---

## Project Description

This is a minimal and interactive frontend project built using **HTML, CSS, and JavaScript**.

The application allows a user to:

- Type a message into a text area
- View the number of characters typed
- See how many characters remain out of the maximum allowed
- Receive a warning when the character limit is reached

---

## Features

- Text area with defined maximum character limit (200 characters)
- Real-time updating character counter
- Display of typed and remaining characters
- Warning message when the limit is reached
- Basic styling for clarity and usability
- Prevents typing beyond the maximum limit

---

## How It Works

1. The text area listens for the `input` event.
2. Whenever the user types, JavaScript captures the current text length.
3. The counter is updated in real time:
   - `X/200 characters`
4. If the character limit is reached, a warning message is shown.
5. The built-in `maxlength` attribute prevents further typing after the limit.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

---

## Validation Details

- Maximum characters: 200  
- Characters typed and characters remaining are shown simultaneously
- Warns the user when the limit has been reached

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/praveen-analyze/character-counter.git
