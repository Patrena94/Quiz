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
    assistance from Jamie with refractoring the function countdown.