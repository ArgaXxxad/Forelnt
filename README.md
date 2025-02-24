<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Путешествие с Boba</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      height: 100%;
      background-image: url('https://i.pinimg.com/736x/85/6c/3f/856c3f2af48efcc2b454ea2f998da548.jpg');
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      overflow-y: auto;
    }

    .content, .new-page-content, .quiz-page-content {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 20px;
      border-radius: 10px;
      width: 90%;
      max-width: 1000px;
      box-sizing: border-box;
      margin-bottom: 20px;
      max-height: 80vh;
      overflow-y: auto;
    }

    h1 {
      font-size: 2.5rem;
      color: #ffcc00;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
      margin-bottom: 20px;
    }

    p {
      font-size: 1.2rem;
      line-height: 1.6;
      margin-bottom: 20px;
      white-space: pre-line;
      max-height: 1000px; /* Задаем максимальную высоту для текста */
      overflow-y: auto; /* Прокрутка для текста */
    }

    .continue-button {
      background-color: #ff6600;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1.2rem;
      cursor: pointer;
      border-radius: 5px;
      position: fixed;
      bottom: 20px;
      right: 20px;
      transition: background-color 0.3s ease;
    }

    .continue-button:hover {
      background-color: #cc5200;
    }

    .new-page-content img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .back-button {
      background-color: #ff6600;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1.2rem;
      cursor: pointer;
      border-radius: 5px;
      margin-top: 20px;
      transition: background-color 0.3s ease;
    }

    .back-button:hover {
      background-color: #cc5200;
    }

    /* Викторина стиль */
    .quiz-page-content {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .question {
      margin-bottom: 20px;
      font-size: 1.2rem;
    }

    input[type="text"] {
      padding: 5px;
      font-size: 1rem;
      border-radius: 5px;
      border: none;
      margin-top: 10px;
    }

    button {
      background-color: #3498db;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 5px;
      margin: 10px;
    }

    button:hover {
      background-color: #2980b9;
    }

    #result {
      font-size: 1.2rem;
      margin-top: 20px;
    }

    /* Добавить прокрутку для викторины */
    .quiz-container {
      max-height: 50vh;
      overflow-y: auto;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <!-- Основной контент -->
  <div class="content" id="main-content">
    <h1>Дорогая Boba,</h1>
    <p>
        Эта игра — не просто набор вопросов и заданий. Это путешествие в наше прошлое, настоящее и будущее. Каждый вопрос, каждая загадка — это напоминание о моментах, которые сделали нас теми, кто мы есть.
      
        Помнишь тот день? Тот самый, когда я споткнулся, отдавая тебе книгу и пытаясь уйти с достоинством? Это было неловко, смешно и... безумно искренне. Я никогда не забуду, как ты улыбнулась, и да я не был как БОМЖ одет.
        
        А теперь давай поговорим о чём-то важном. Второй вопрос, который я задал тебе, звучал так:
        «Пусть будет терпимее к чужим чувствам. В этой Вселенной и так маловато искренней любви.»
        
        Эти слова — не просто фраза. Это призыв. Призыв быть внимательнее к тем, кто рядом. К их эмоциям, переживаниям, мечтам и страхам. Ведь каждый из нас несёт в себе целый мир, полный радостей и боли.
        
        «Пусть будет терпимее к чужим чувствам» — это напоминание о том, что:
        
        Мы должны слушать друг друга не только ушами, но и сердцем.
        
        Мы должны избегать резких суждений, ведь за каждым словом скрывается чья-то история.
        
        Мы должны уважать чужую правду, даже если она отличается от нашей.
        
        А фраза «В этой Вселенной и так маловато искренней любви» — это правда, которую мы часто забываем. Мир полон суеты, эгоизма и страхов. Но именно поэтому так важно дарить друг другу тепло, поддержку и понимание.
        
        И знаешь, Boba, я не просто так выбрал тематику «Смешариков» для этой игры. Для меня эти персонажи — не просто мультфильм. Это символ чего-то большего.
        
        Помнишь, как мы смотрели «Смешариков»? Ты всегда говорила, что я — Заяц, а ты — Ёжик. И знаешь, что мне в этом нравится? Заяц и Ёжик — это не просто друзья. Они — команда. Они поддерживают друг друга, даже когда всё идёт не так. Они смешные, искренние и настоящие.
        
        Именно такими я вижу нас. Мы — команда. Мы — два персонажа одной истории, которая пишется каждый день. И даже если иногда мы спотыкаемся, как я в тот день с книгой, мы всегда находим способ улыбнуться и идти дальше.
        
        Boba, в этой игре я хочу напомнить тебе и себе, что наша история — это не просто случайность. Это выбор. Выбор быть терпимее, добрее и искреннее. Выбор любить, даже когда это сложно.
        
        Готовься, ведь впереди нас ждут новые вопросы, загадки и воспоминания. И каждый из них — это шаг к тому, чтобы стать лучше. Для себя, для друг друга и для этого мира, где так мало искренней любви.
    </p>
    <button class="continue-button" onclick="goToNextPage()">Продолжить</button>
  </div>

  <!-- Новая страница с фотографией -->
  <div class="new-page-content" id="new-page-content" style="display: none;">
    <img src="https://i.pinimg.com/736x/b5/0a/df/b50adf247399e8999d5555c3524a3675.jpg" alt="Пример изображения">
    <h1>Продолжение путешествия</h1>
    <p>У тебя есть фото моей спины с этой ветровкой, иди туда где ты сделала это фото. Отскакинруй QR там.</p>
    <button class="continue-button" onclick="goToQuizPage()">Продолжить викторину</button>
  </div>

  <!-- Страница викторины -->
  <div class="quiz-page-content" id="quiz-page-content" style="display: none;">
    <h1>Викторина: Наша история</h1>
    <p>Ответь на вопросы и проверь, насколько хорошо ты помнишь наши моменты.</p>
    <div class="quiz-container" id="quiz"></div>
    <button onclick="checkAnswers()">Завершить викторину</button>
    <p id="result"></p>
  </div>

  <script>
    // Переход на страницу с фотографией
    function goToNextPage() {
      document.getElementById('main-content').style.display = 'none';
      document.getElementById('new-page-content').style.display = 'block';
    }

    // Переход на страницу викторины
    function goToQuizPage() {
      document.getElementById('new-page-content').style.display = 'none';
      document.getElementById('quiz-page-content').style.display = 'block';
    }

    // Викторина
    const questions = [
      {
        question: "1. Где мы сидели, когда ты призналась мне в чувствах?",
        answers: ["В парке", "На скамейке", "В торговый центр"],
        correct: 1
      },
      {
        question: "2. Куда мы уходили, чтобы спрятаться от твоих родителей?",
        answers: ["В соседний двор", "В торговый центр", "В кино"],
        correct: 0
      },
      {
        question: "3. Когда ты согласилась встречаться со мной раньше срока?",
        answers: ["26 января", "14 февраля", "8 марта"],
        correct: 0
      },
      {
        question: "4. Что ты любила делать с моими пальцами, даже когда это было больно?",
        answers: ["Кусать", "Держать", "Целовать"],
        correct: 0
      },
      {
        question: "5. Как ты смотрела на меня, даже когда мы расставались?",
        answers: ["С влюблёнными глазами", "С грустью", "С улыбкой"],
        correct: 0
      },
      {
        question: "6. Какой фразой ты всегда поддерживала меня?",
        answers: ["Ты сможешь!", "ЛОХ", "Я рядом"],
        correct: 1
      },
      {
        question: "7. Куда ты приезжала, когда я улетал или прилетал?",
        answers: ["На вокзал", "В аэропорт", "На автобусную остановку"],
        correct: 1
      },
      {
        question: "8. Что ты любила делать, когда мы виделись?",
        answers: [], // Этот вопрос будет с текстовым полем
        correct: null
      },
      {
        question: "9. Кто первый поцеловал другого?",
        answers: ["Я", "Ты", "Никто"],
        correct: 1
      },
      {
        question: "10. Что ты сказала про жалюзи на нашей первой прогулке?",
        answers: ["Красивая", "Ничего", "Какие красивые жалюзи!"],
        correct: 0
      },
      {
        question: "11. Что мы любили делать во время звонков?",
        answers: ["Спать", "Смотреть фильмы", "Все"],
        correct: 2
      },
      {
        question: "12. Что мы делали, когда ты шла в душ?",
        answers: ["Ты мне звонил", "Писали сообщения", "Молчали"],
        correct: 0
      },
      {
        question: "13. Чем ты любила делиться со мной?",
        answers: ["Сплетнями", "Едой", "Книгами"],
        correct: 0
      },
      {
        question: "14. Что ты стала делать больше, чтобы порадовать меня?",
        answers: ["Стараться", "Готовить", "Все"],
        correct: 2
      },
      {
        question: "15. Какой момент из наших звонков ты помнишь больше всего?",
        answers: ["Когда мы смеялись", "Когда я рассказывал сказку", "Когда мы просто молчали"],
        correct: 0
      },
      {
        question: "16. Что я хочу сказать тебе сейчас?",
        answers: ["Я скучаю.", "Прости меня.", "ВЭЙЙТТ трурурур"],
        correct: 2
      }
    ];

    let quizHTML = "";
    questions.forEach((q, index) => {
      quizHTML += `<div class="question">`;
      quizHTML += `<p>${q.question}</p>`;
      if (index === 7) {
        // Текстовое поле для 8-го вопроса
        quizHTML += `<input type="text" id="answer${index}" placeholder="Напишите ваш ответ...">`;
      } else {
        q.answers.forEach((answer, i) => {
          quizHTML += `<input type="radio" name="question${index}" value="${i}" id="answer${index}_${i}">
            <label for="answer${index}_${i}">${answer}</label><br>`;
        });
      }
      quizHTML += `</div>`;
    });
    document.getElementById('quiz').innerHTML = quizHTML;

    // Проверка ответов
    function checkAnswers() {
      let score = 0;
      questions.forEach((q, index) => {
        if (index === 7) {
          const answer = document.getElementById(`answer${index}`).value;
          if (answer.toLowerCase() === q.answers[q.correct].toLowerCase()) {
            score++;
          }
        } else {
          const selectedAnswer = document.querySelector(`input[name="question${index}"]:checked`);
          if (selectedAnswer && selectedAnswer.value == q.correct) {
            score++;
          }
        }
      });
      document.getElementById('result').innerHTML = `Ваш результат: ${score} из ${questions.length}`;
    }
  </script>
</body>
</html>
