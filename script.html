const questions = [
    {
        question: "who is the papa of neeraj?",
        answers:[
            {text: "GOD", correct: false}, 
            {text: "Amar", correct: false},
            {text: "Mayank jain", correct: true},
            {text: "No one", correct: false}, 

        ]
    },
    {
        question: "Who is shivam ?",
        answers: [
            {text: "Coder", correct: false}, 
            {text: "chinaar No. 1", correct: true}, 
            {text: "Neeraj's Father", correct: false}, 
            {text: "graduated student", correct: false}, 
        ]
    },
    {
        question: "What does Amar do in the office?", 
        answers: [
            {text: "office work", correct: false},
            {text: "nothing", correct: false},
            {text: "Tel chatai", correct: true},
            {text: "gameplay", correct: false},
        ]
    },
    
];

const questionElement = document.getElementById("question"); 
const answerButtons = document.getElementById("answer-buttons"); 
const nextButton = document.getElementById("next-btn"); 

let currentQuestionIndex = 0; 
let score = 0;

function startQuiz(){
    currentQuestionIndex = 0;
    score = 0; 
    nextButton.innerHTML = "Next"; 
    showQuestion(); 
}

function showQuestion(){
    resetState();
    let currentQuestion = questions[currentQuestionIndex];
    let questionNo = currentQuestionIndex + 1; 
    questionElement.innerHTML = questionNo + ". " + currentQuestion.question; 


    currentQuestion.answers.forEach(answer => {
        const button = document.createElement("button"); 
        button.innerHTML = answer.text; 
        button.classList.add("btn"); 
        answerButtons.appendChild(button);
        if(answer.correct){
            button.dataset.correct = answer.correct;
        }
        button.addEventListener("click", selectAnswer);
    });
}

function resetState(){
    nextButton.style.display = "none";
    while(answerButtons.firstChild){
        answerButtons.removeChild(answerButtons.firstChild);
    }
}


function selectAnswer(e){
    const selectedBtn = e.target; 
    const isCorrect = selectedBtn.dataset.correct === "true"; 
    if(isCorrect){
        selectedBtn.classList.add("correct");
        score++;
    }else{
        selectedBtn.classList.add("incorrect");
    }
    Array.from(answerButtons.children).forEach(button => {
        if(button.dataset.correct === "true"){
            button.classList.add("correct");
        }
        button.disabled = true; 
    }

    ); 
    nextButton.style.display = "block"; 
}

function showScore(){
    resetState(); 
    questionElement.innerHTML = `You scored ${score} out of ${questions.length}!`; 
    nextButton.innerHTML = "Play Again"; 
    nextButton.style.display = 'block'; 
}


function handleNextButton(){
    currentQuestionIndex++;
    if(currentQuestionIndex < questions.length){
        showQuestion(); 
    }else{
        showScore();
    }
}


nextButton.addEventListener("click", ()=>{
    if(currentQuestionIndex < questions.length){
        handleNextButton(); 
    }else{
        startQuiz(); 
    }
})



startQuiz(); 