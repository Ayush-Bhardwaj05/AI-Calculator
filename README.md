# AI Calculator

This is an AI-powered calculator that allows users to input handwritten mathematical expressions and get results in real-time. The calculator processes the image input using machine learning and displays the results on the canvas. The project features LaTeX rendering for mathematical expressions and a drawing canvas for user input.

---

## Table of Contents

- [Pages Overview](#pages-overview)
- [Canvas Page](#canvas-page)
- [Calculation Features](#calculation-features)
- [LaTeX Rendering](#latex-rendering)
- [Clear and Reset Functionality](#clear-and-reset-functionality)
- [User Interface](#user-interface)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Frontend Setup](#frontend-setup)
- [Backend Setup](#backend-setup)
- [Accessing the Application](#accessing-the-application)

---

## Pages Overview

### Canvas Page

The Canvas page allows users to draw mathematical expressions, which the AI processes to produce answers.

- **Drawing**: Users can draw equations or expressions using a pencil tool.
- **Eraser Mode**: Users can switch to eraser mode to correct drawings.
- **Result Display**: Results are rendered directly on the canvas using LaTeX.

![image](https://github.com/user-attachments/assets/a6b4c633-5be2-4f7e-a016-4ee4f2556c28)
  

---

## Calculation Features

- **AI Processing**: The calculator processes the image of the drawn expression using a machine learning model hosted on the backend.
- **Latex Result**: After processing, the AI returns the answer and renders both the expression and the result in LaTeX on the canvas.
- **Dynamic Updates**: Results are updated in real-time on the canvas after calculation.

### LaTeX Rendering

The results are displayed using LaTeX, providing a clear and structured view of the equation and its corresponding result.

### Clear and Reset Functionality

- **Clear Drawing**: Users can clear the current drawing using the reset button, which clears the canvas and resets the state.
- **Erase feature**: Users can erase some parts of the drawing which might not be needed in the calculation. 
---

## User Interface

- **Styled Components**: The interface uses styled-components for modular, responsive design.
- **Color Swatches**: Users can choose the pencil color from a palette of swatches for drawing on the canvas.
- **Responsive**: Designed for smooth experience across devices.

---

## Technologies Used

- **Frontend**: HTML, SCSS, TypeScript, React.js
- **Backend**: Python (FastAPI), Uvicorn, Axios
- **Other**: LaTeX, Draggable for moving LaTeX-rendered equations, Axios for API requests

---

## Getting Started

To run the project locally, you will need to install the following dependencies:

- Node.js
- npm
- Python

---

## Installation

### Frontend Setup:

1. Clone the project repository:

```bash
git clone [Your GitHub Repository Link]
```

2. Navigate to the frontend directory:

```bash
cd ai-calculator/calc-fe
```

3. Install the frontend dependencies:

```bash
npm install
```

4. Start the frontend development server:

```bash
npm run dev
```

### Backend Setup:

1. Navigate to the backend directory:

```bash
cd ai-calculator/calc-be
```

2. Install the Python dependencies:

```bash
pip install -r requirements.txt
```

3. Start the backend server:

```bash
python main.py
```

---

## Accessing the Application

- The frontend runs on port 3000. Open a web browser and navigate to `http://localhost:3000` to use the app.
- The backend runs on port 8900. You can access the API routes via `http://localhost:8900`.

---

## Database Management

Currently, the AI Calculator does not require database management as it processes data in real-time on the backend.
