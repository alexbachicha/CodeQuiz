# 04 Web APIs: Code Quiz

[The Office Fan Quiz!](https://alexbachicha.github.io/CodeQuiz/)

## Your Task

As you proceed in your journey to becoming a full-stack web developer, it’s likely that you’ll be asked to complete a coding assessment, perhaps as part of an interview process. A typical coding assessment is a combination of multiple-choice questions and interactive coding challenges. 

To help you become familiar with these tests and give you a chance to apply the skills from this module, this week’s homework invites you to build a timed coding quiz with multiple-choice questions. This app will run in the browser, and will feature dynamically updated HTML and CSS powered by JavaScript code that you write. It will have a clean, polished, and responsive user interface. This week’s coursework will teach you all the skills you need to succeed in this assignment.


## User Story

```
AS A coding boot camp student
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores
SO THAT I can gauge my progress compared to my peers
```


## Acceptance Criteria

```
GIVEN I am taking a code quiz
WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and score
```


## Instructions 


The quiz asks the user a series of questions about the television show, The Office. The user is given 75 seconds to start out with but each wrong answer results in a deduction of 15 seconds. The user's final score is the resulting number of seconds left on the timer after the last question is answerd.

To start the quiz, the user clicks the button that says "Start Quiz".

![Home Screen](https:///Users/bachicha/code/WebApiCodeQuiz/CodeQuiz/assets/ss1_welcome.png)

Once the quiz is started, the user is promted with a question and four answer choices. After choosing an answer, the quiz will notify the user whether their answer was correct. If it's not correct, 15 seconds are deducted from the current time. The next question is then loaded.

![Example of Questions](https:///Users/bachicha/code/WebApiCodeQuiz/CodeQuiz/assets/ss2_question.png)

After the final question is answered, the user is shown their score and is prompted to enter their initials. When submit is pressed, the initials and score are saved to the local storage. This means even after the browser is refreshed, the scores and user initials will still be there.

![Highscore Page](https://Users/bachicha/code/WebApiCodeQuiz/CodeQuiz/assets/ss3_hs.png)


## Overall Project Experience


I found this project to be the hardest one yet. It was quite overwhelming and I found myself pushed for time most of the way. Before starting this project, I felt completely lost. I still feel a bit lost when it comes to the complexities of Javascript and the sheer amount of ways you can code your projects. 
I used various resources to pull random bits and pieces together to form what I have now as my "The Office" themed Code Quiz.

ERROR Update as of 6:22P 10/24/20. I cannot get my screenshots to load in this README.md file. I have tried multiple times and methods to get them to show and they just will not work for me. Still trying to troubleshoot here and there until submission deadline.


## Acknowledgements


* [UCD Coding Bootcamp Repo](https://ucdavis.bootcampcontent.com/ucdavis-boot-camp/ucd-sac-fsf-pt-09-2020-u-c)
* [Google](http://google.com)
* [W3Schools](https://www.w3schools.com/)
