<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Quiz App</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: #fff;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .quiz-container {
      background: #2d2d2d;
      border-radius: 20px;
      padding: 30px;
      width: 90%;
      max-width: 500px;
      box-shadow: 0px 10px 25px rgba(0, 0, 0, 0.3);
      text-align: center;
    }

    h1 {
      margin-bottom: 20px;
      font-size: 28px;
    }

    .question {
      font-size: 20px;
      margin-bottom: 20px;
    }

    .options button {
      display: block;
      background: #444;
      border: none;
      border-radius: 12px;
      padding: 12px;
      margin: 10px 0;
      width: 100%;
      font-size: 16px;
      color: #fff;
      cursor: pointer;
      transition: background 0.3s;
    }

    .options button:hover {
      background: #667eea;
    }

    .next-btn {
      margin-top: 20px;
      background: #667eea;
      border: none;
      border-radius: 12px;
      padding: 12px 20px;
      font-size: 16px;
      cursor: pointer;
      color: #fff;
      display: none;
    }

    .next-btn:hover {
      background: #764ba2;
    }

    .score {
      font-size: 22px;
      margin-top: 20px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  
  <div class="quiz-container">
    <h1>Quiz App</h1>
    <div class="question" id="question">Question text</div>
    <div class="options" id="options"></div>
    <button class="next-btn" id="nextBtn">Next</button>
    <div class="score" id="score"></div>
  </div>

  <script>
    const questions = [
      {
        question: "What is the capital of France?",
        options: ["Berlin", "Madrid", "Paris", "Lisbon"],
        answer: "Paris"
      },
      {
        question: "Which language runs in a web browser?",
        options: ["Java", "C", "Python", "JavaScript"],
        answer: "JavaScript"
      },
      {
        question: "What does CSS stand for?",
        options: ["Cascading Style Sheets", "Colorful Style Syntax", "Computer Style Sheets", "Creative Style System"],
        answer: "Cascading Style Sheets"
      },
      {
        question: "Which HTML tag is used for JavaScript?",
        options: ["<javascript>", "<js>", "<script>", "<code>"],
        answer: "<script>"
      },
      {
        question: "Which HTML tag is used to define the largest heading?",
        options: ["<h1>", "<heading>", "<h6>", "<head>"],
        answer: "<h1>"
      },
      {
        question: "Which property in CSS is used to change text color?",
        options: ["font-style", "text-color", "color", "background-color"],
        answer: "color"
      },
      {
        question: "Which attribute is used in HTML to provide an alternate text for an image?",
        options: ["title", "alt", "src", "href"],
        answer: "alt"
      },
      {
        question: "Which CSS property controls the size of text?",
        options: ["font-size", "text-style", "text-size", "font-weight"],
        answer: "font-size"
      },
      {
        question: "In HTML, which tag is used to create a hyperlink?",
        options: ["<a>", "<link>", "<href>", "<url>"],
        answer: "<a>"
      },
      {
        question: "Which CSS property is used to change the background color of an element?",
        options: ["color", "bgcolor", "background-color", "background"],
        answer: "background-color"
      },
      {
        question: "What is the default display property of a <div> element?",
        options: ["inline", "block", "flex", "inline-block"],
        answer: "block"
      },
      {
        question: "Which HTML element is used to create an ordered list?",
        options: ["<ul>", "<ol>", "<li>", "<list>"],
        answer: "<ol>"
      },
      {
        question: "Which CSS property is used to make text bold?",
        options: ["text-style", "font-weight", "font-bold", "text-bold"],
        answer: "font-weight"
      },
      {
        question: "Which tag is used to display a line break in HTML?",
        options: ["<break>", "<br>", "<lb>", "<newline>"],
        answer: "<br>"
      },
      {
        question: "What does the 'id' attribute in HTML do?",
        options: ["Specifies a unique identifier", "Specifies a class name", "Specifies an inline style", "Specifies a script"],
        answer: "Specifies a unique identifier"
      },
      {
        question: "Which CSS property is used to center text?",
        options: ["text-align", "align", "center-text", "font-align"],
        answer: "text-align"
      },
      {
        question: "Which HTML element is used to display an image?",
        options: ["<src>", "<image>", "<img>", "<picture>"],
        answer: "<img>"
      },
      {
        question: "Which CSS property sets the space between letters?",
        options: ["line-height", "letter-spacing", "word-spacing", "font-spacing"],
        answer: "letter-spacing"
      },
      {
        question: "Which HTML element is used for creating a dropdown menu?",
        options: ["<input>", "<list>", "<select>", "<dropdown>"],
        answer: "<select>"
      },
      {
        question: "Which CSS property is used to create rounded corners?",
        options: ["border-radius", "corner-style", "round-corner", "border-style"],
        answer: "border-radius"
      }
    ];

    const questionEl = document.getElementById("question");
    const optionsEl = document.getElementById("options");
    const nextBtn = document.getElementById("nextBtn");
    const scoreEl = document.getElementById("score");

    let currentQuestionIndex = 0;
    let score = 0;

    function loadQuestion() {
      resetState();
      const currentQuestion = questions[currentQuestionIndex];
      questionEl.textContent = currentQuestion.question;

      currentQuestion.options.forEach(option => {
        const button = document.createElement("button");
        button.textContent = option;
        button.onclick = selectAnswer;
        optionsEl.appendChild(button);
      });
    }

    function resetState() {
      nextBtn.style.display = "none";
      optionsEl.innerHTML = "";
    }

    function selectAnswer(e) {
      const selectedBtn = e.target;
      const answer = questions[currentQuestionIndex].answer;
      if (selectedBtn.textContent === answer) {
        selectedBtn.style.background = "#28a745";
        score++;
      } else {
        selectedBtn.style.background = "#dc3545";
      }

      Array.from(optionsEl.children).forEach(button => {
        button.disabled = true;
        if (button.textContent === answer) {
          button.style.background = "#28a745";
        }
      });

      nextBtn.style.display = "block";
    }

    function showScore() {
      resetState();
      questionEl.textContent = "Quiz Completed!";
      scoreEl.textContent = `Your Score: ${score} / ${questions.length}`;
      nextBtn.textContent = "Play Again";
      nextBtn.style.display = "block";
    }

    function handleNextBtn() {
      currentQuestionIndex++;
      if (currentQuestionIndex < questions.length) {
        loadQuestion();
      } else {
        showScore();
      }
    }

    nextBtn.addEventListener("click", () => {
      if (currentQuestionIndex < questions.length) {
        handleNextBtn();
      } else {
        currentQuestionIndex = 0;
        score = 0;
        nextBtn.textContent = "Next";
        scoreEl.textContent = "";
        loadQuestion();
      }
    });

    loadQuestion();
  </script>
</body>
</html>
