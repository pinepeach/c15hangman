let word_bank = {
    'COMMITTEE': 'A group that is in charge of a specific task.',
    'LOKI': 'Lowkey',
    'BLACKWIDOW': 'See you in a minute',
    'THOR': 'Noobmaster69',
    'DATABASE': 'We don\'t know what\'s happening',
    'DRAX': 'When is Gamora?',
    'SPIDERMAN': 'Mr. Stark, I don\'t feel so good',
    'IRONMAN': 'Even in Death I am The Hero',
    'HULK': 'SMASH',
    'CAPTAINAMERICA': 'He was worthy',
    'AVENGERS': 'Assemble',
    'GROOT': 'I am...',
    'TESSERACT': 'Space Stone',
    'AETHER': 'Reality Stone',
    'VORMIR': 'Soul Stone',
    'BOBA': 'SAT Drink',
    'REDSKULL': 'I guide others to a treasure I cannot possess',
    'VISION': 'Mind Stone',
    'ORB': 'Power Stone'
}
let hangman_pics = ['img/7.gif', 'img/6.gif', 'img/5.gif', 'img/4.gif', 'img/3.gif', 'img/2.gif', 'img/1.gif', 'img/0.gif']
let score = 0
let lives = 7
let CorrectClicks = 0
function createButtons() {
    for (i = 65; i < 91; i++) {
        if (i == 79) {
            document.write('<br><br>')
        }
        let btn = document.createElement('button')
        btn.innerHTML = String.fromCharCode(i);
        btn.id = 'button_id'
        document.body.appendChild(btn)
        btn.onclick = function buttonOnClick() {
            console.log(btn.innerHTML + ' clicked')
            btn.id = 'buttonClicked'
            for (i = 0; i < wordList.length; i++) {
                if (wordList[i] == btn.innerHTML) {
                    blankList[i] = btn.innerHTML
                    wordListJoin = blankList.join('  ')
                    document.getElementById('word').innerHTML = wordListJoin
                    CorrectClicks += 1
                    addpoint()
                }
            }
            if (!wordList.includes(btn.innerHTML)) {
                lostlife()
                losepoint()
            }
            Solved()
        }
    }
}
function lostlife() {
    lives -= 1;
    livestext.innerHTML = 'You have ' + lives + ' lives left';
    changeImage()
    if (lives == 0) {
        for (i = 65; i < 91; i++) {
            try {
                document.getElementById('button_id').id = 'buttonClicked'
            }
            catch{
                console.log(i + ' is already gone')
            }
        }
        LosingMessage()
    }
}
function losepoint() {
    score -= 1;
    document.getElementById("score").innerHTML = 'Score: ' + score
}
function addpoint() {
    score += 1;
    document.getElementById("score").innerHTML = 'Score: ' + score
}
function displayWord() {
    let i = Math.floor(Math.random() * 19)
    let randomWord = Object.keys(word_bank)
    let randomHint = Object.values(word_bank)
    return [randomWord[i], randomHint[i]]
}
function LosingMessage() {
    let name = prompt('What\'s your name?')
    word.innerHTML = 'GAME OVER ' + name.toUpperCase()
    if((name == null) || (name == '')){
        word.innerHTML = 'GAME OVER LOSER!'
    }
}
function SolvedMessage() {
    let name = prompt('What\'s your name?')
    word.innerHTML = 'CONGRATULATIONS ' + name.toUpperCase() +'!'
    if((name == null) || (name == '')){
        word.innerHTML = 'CONGRATULATIONS WINNER!'
    }
}
function Solved() {
    if (CorrectClicks == randomWord.length) {
        for (i = 65; i < 91; i++) {
            try {
                document.getElementById('button_id').id = 'buttonClicked'
            }
            catch{
                console.log(i + ' is already gone')
            }
        }
        SolvedMessage()
    }
}
function hideWords(randomWord) {
    let wordList = randomWord.split('')
    let wordReplace = '__ '.repeat(parseInt(wordList.length))
    blankList = wordReplace.split(' ')
    blankList.pop()
    wordListJoin = blankList.join('  ')
    document.getElementById('word').innerHTML = wordListJoin
    return [wordList, blankList]
}
function refresh() {
    window.location.reload(true)
}
document.getElementById('restart').onclick = refresh
function changeImage() {
    document.getElementById('hangmanImg').src = hangman_pics[lives]
}
function play(){
    createButtons()
    displayWordFunction = displayWord()
    randomWord = displayWordFunction[0]
    console.log(randomWord)
    randomHint = displayWordFunction[1]
    hint.innerHTML = 'Hint: ' + randomHint
    hideWordsFunction = hideWords(randomWord)
    wordList = hideWordsFunction[0]
    blankList = hideWordsFunction[1]
    livestext.innerHTML = 'You have ' + lives + ' lives left'
    changeImage()
}
play()
