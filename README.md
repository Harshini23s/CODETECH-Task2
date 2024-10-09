NAME: B.Harshini
COMPANY: CODETECH IT SOLUTIONS
ID: CT08DS8025
DOMAIN: FRONTEND DEVELOPER
DURATON: SEPTEMBER TO OCTOBER 2024
MENTOR: Neela Santhosh Kumar

OVERVIEW OF THE PROJECT
PROJECT: INTERACTIVE QUIZ APPLICATION

An interactive quiz application where users can answer
multiple-choice questions and receive feedback.

output:
![Screenshot (143)](https://github.com/user-attachments/assets/84823533-e36f-4258-ac7f-ec48236d1fcb)

![Screenshot (145)](https://github.com/user-attachments/assets/c1256a19-f914-43f1-965f-bf802b28e2c5)

![Screenshot (146)](https://github.com/user-attachments/assets/3da6eeef-5744-4ae6-bd85-a7f38fcefacc)

TECHNOLOGIES USED:
1. HTML5
2. CSS
3. JAVASCRIPT

1. HTML (Structure)
This defines the structure of the webpage and the quiz interface.

2.div.quiz-container: Contains the entire quiz interface.
div#question: Displays the question text.
div.answers: Contains four buttons for multiple-choice answers.
#next-btn: Button to move to the next question.
#result: Displays the score when the quiz is complete.

3.The body has flex to center the quiz.
Buttons are styled with hover effects and background colors.
next-btn and result are hidden initially using display: none

4.Questions Array: Contains the quiz questions and answers, with a boolean correct field.
startQuiz(): Initializes the quiz and shows the first question.
showQuestion(): Displays the current question and its answers.
selectAnswer(): Handles the answer selection. If correct, it increments the score.
resetState(): Clears the answers from the previous question.
showResult(): Displays the final score and resets the quiz.





