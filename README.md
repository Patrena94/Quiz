# Quiz
created a Javascript file and Highscore Html.
started code fo Qindex.html
added a button to the Highscore.html
selected question, choices and answers formated and entered into Qindex.html.
Created the style.css file.
started by adding background color to the body. Right aligned the Timer.
inserted Start button with color, active, and dimensions.
inserted submit button with color, active, and dimensions.
initial textbox provided with a background color of grey with and active color of smoked white.
answer choice buttons were decorated with color and radius was provided.
changed the text input filed to grey
updated style.css file to show the gobackBtn and clearHighschoreBtn as Teal. Also updated the dimensions for these butttons.
changed the choice buttons to teal from violet.
removed option 5 which was an empty choice button.
<div class="timer">Time Remaining: <span id="time">0</span></div>
 remove:
 function countDown() { 
    var timeInterval =setInterval(function(){
    if(timeRemaining> 1){
    timerEl.textContent= timeRemaining + 'seconds remaining';
    timeRemaining--;
    } else if(timeRemaining==0){timerEl.textContent = timeLeft + 'second remaining';
timeRemaining--;
} else{timerEl.textContent = '';
    clearInterval(pidClock);
    questionsDiv.classList.add("hide")
    initialDiv.classList.remove("hide")
    displayMessage();
    assistance from Jamie removing the visibility of the start button.
    consider the following code for checking the answers to questions. 
//var checkAnswer = "a"
//<div class="option1" id="a"onclick="checkAnswer('1')">1</div>
   // let score =0;
  //  function checkAnswer ("a")
 //   {if (questions[runningquestionIndex].correct ==answer){ score++; 
  //  answerisCorrect();
////}else {answerisWrong();
//}
//if(runningquestionIndex < lastquestionIndex)
//{ count =0; runningquestionIndex++;
  //  questionrender();
//}else
//{ clearInterval(Timer);
  //  }
  //<div class="option2" id="a"onclick="checkAnswer('1')">1</div>
   // let score =0;
  //  function checkAnswer ("a")
 //   {if (questions[runningquestionIndex].correct ==answer){ score++; 
  //  answerisCorrect();
////}else {answerisWrong();
//}
//if(runningquestionIndex < lastquestionIndex)
//{ count =0; runningquestionIndex++;
  //  questionrender();
//}else
//{ clearInterval(Timer);
  //  }
    //}

    function loadQuestion(){
    title.textContent=questions[questionIndex].q
    option1.textContent=questions[questionIndex].c[0]
    option2.textContent=questions[questionIndex].c[1]
    option3.textContent=questions[questionIndex].c[2]
    option4.textContent=questions[questionIndex].c[3]
}
loadQuestion()
    <
    updated link on go back button to make it functional.
    removed index.html optional placeholder file.
    set a max for the number of initials you could provide.
    Add All done statement.
    Centered start button/header
    Enlarged font on header
    changed header font color for the statement to Navy Blue.