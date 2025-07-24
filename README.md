# World Capital Quiz

<img width="1915" height="904" alt="image" src="https://github.com/user-attachments/assets/7be2969d-d1d8-40c8-b5dc-555dbf812be0" />

<img width="1908" height="901" alt="image" src="https://github.com/user-attachments/assets/45f38d52-92d2-4fcc-bf3d-18a2620293dd" />

<img width="1912" height="898" alt="image" src="https://github.com/user-attachments/assets/31baa1d8-57c5-4042-b4e1-090e9ec42193" />


A simple web-based quiz application that tests users' knowledge of world capitals. Built with Node.js, Express.js, and EJS templating.

---

## Features

- **Interactive Quiz:** Answer questions about world capitals.
- **Score Tracking:** Keep track of correct answers throughout the quiz.
- **Random Questions:** Questions are presented in random order.
- **Immediate Feedback:** Get instant feedback on whether your answer was correct.
- **Responsive Design:** Works on both desktop and mobile devices.

---

## Technologies Used

- Node.js
- Express.js
- EJS (Embedded JavaScript templates)
- body-parser
- CSS (for styling)

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-github-username>/world-capital-quiz.git
   cd world-capital-quiz
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the server:**
   ```bash
   node index.js
   ```

4. **Open your browser and go to:**
   ```
   http://localhost:3000
   ```

---

## How to Play

1. Visit the home page to start the quiz.
2. You'll be presented with a country name.
3. Enter the capital city of that country.
4. Submit your answer to see if it's correct.
5. Your score will be tracked as you continue answering questions.

---

## Quiz Data

The quiz currently includes capitals for:
- France (Paris)
- United Kingdom (London)
- United States of America (New York)

*Note: You can easily expand the quiz by adding more country-capital pairs to the `quiz` array in `index.js`.*

---

## Folder Structure

```
world-capital-quiz/
├── public/           # Static files (CSS, images, etc.)
├── views/            # EJS templates
│   └── index.ejs     # Main quiz page
├── index.js          # Main server file
├── package.json
└── README.md
```

---

## Customization

To add more countries and capitals, edit the `quiz` array in `index.js`:

```javascript
let quiz = [
  { country: "France", capital: "Paris" },
  { country: "United Kingdom", capital: "London" },
  { country: "United States of America", capital: "New York" },
  // Add more countries here
  { country: "Germany", capital: "Berlin" },
  { country: "Japan", capital: "Tokyo" },
];
```

---

## Author

Developed by [BahaaJber](https://github.com/BahaaJber1).
