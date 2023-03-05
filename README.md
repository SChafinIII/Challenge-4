# Challenge-4 - Coding Quiz
The goal of this assignment was to clear the following criteria following the below User Story:
- AS A coding boot camp student
- I WANT to take a timed quiz on JavaScript fundamentals that stores high scores
- SO THAT I can gauge my progress compared to my peers

With the following Acceptance Criteria: 
- GIVEN I am taking a code quiz
- WHEN I click the start button
- THEN a timer starts and I am presented with a question
- WHEN I answer a question
- THEN I am presented with another question
- WHEN I answer a question incorrectly
- THEN time is subtracted from the clock
- WHEN all questions are answered or the timer reaches 0
- THEN the game is over
- WHEN the game is over
- THEN I can save my initials and score

## Code Version 1.0
The current application allows a user to access a code quiz and begin the quiz by clicking `start`. This then prompts the user with a series of questions allowing them to answer via radio buttons before procceding to the next question. Your total score is then reviewed at the end of the quiz. 

As of current, selecting an incorrect answer does not reduce your timer and selecting a correct answer does not increase your timer. You are also unable to save high scores at this time. However, this will be updated in future versions to include this criteria. 

**Deployed Application** 
https://schafiniii.github.io/Challenge-4/

## Usage
1. Open the webiste within your browser. 
2. Select `Start.`
3. A timer will begin to count down. Select your answers via the radio buttons and click `next question.`
4. Repeat step 3 until all questions are answered.
5. The timer will stop and you will recieve your score. 

![image of code quiz before start](/Develop/codequiz2.png)

![image of started code quiz with timer and questions on screen](/Develop/codequiz3.png)

![image of final quiz results for user view](/Develop/codequiz1.png)

##Credits
I followed sources from the following websites and utilised CSS templates from the following sites. 

> https://simplestepscode.com/javascript-quiz-tutorial/

> https://gamedevacademy.org/javascript-quiz-tutorial/

> https://profile.w3schools.com/refresh-session?redirect_url=https%3A%2F%2Fwww.w3schools.com%2Fjs%2Fjs_timing.asp

> https://stackoverflow.com/questions/29971898/how-to-create-an-accurate-timer-in-javascript

## MIT License
Copyright (c) [2023] [Steven W Chafin III]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.