# Real-Time Character Counter

This project is a simple web application that allows users to type a message into a text area while displaying a real-time character counter. The counter updates dynamically as the user types and ensures that the user does not exceed the maximum allowed character limit.

---

## Project Description

The application includes a text area where users can enter a message. A character counter displays:

- The number of characters typed
- The maximum allowed characters
- The remaining characters

If the user exceeds the character limit, further typing is prevented and a warning message is displayed.

---

## Features

- Text area with a defined maximum character limit (e.g., 200 characters)
- Real-time character counting
- Displays typed characters and remaining characters (e.g., 150/200 characters)
- Prevents typing beyond the maximum limit
- Shows a warning message when the limit is reached
- Simple and responsive user interface

---

## Technologies Used

- HTML5
- CSS3 (Optional styling)
- JavaScript (Vanilla JS)

---

## Functional Requirements

### 1. Text Area Setup
- An HTML `<textarea>` element is created.
- The maximum character limit is displayed (e.g., "200 characters max").

### 2. Real-Time Character Tracking
- An `input` event listener is attached to the text area.
- Every time the user types, the current character count is calculated.
- The counter updates dynamically.

### 3. Character Display Format
The counter shows:

### 4. Character Limit Enforcement
- If the user reaches the maximum character limit:
  - Further typing is prevented.
  - A warning message is displayed.
- The user cannot enter more than the allowed characters.

---

## How It Works

1. The `textarea` listens for the `input` event.
2. JavaScript calculates:
   - `currentLength = textarea.value.length`
   - `remaining = maxLimit - currentLength`
3. The counter text updates in real time.
4. If `currentLength` exceeds the limit:
   - Input is restricted.
   - A warning message appears.

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
