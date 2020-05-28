<!DOCTYPE html>
<html lang="en">
<head>

    <meta name="author" content="Danial"/>
    <meta name="description" content="Fast money"/>
    <meta charset="UTF-8">
    <title>Fast money</title>
</head>
<style>

    table, th, td {
        padding: 5px;
        text-align: center;
        border-radius: 20px 20px 20px 20px;
        border: 1px inset black;


    }

    th, td {
        box-shadow: 10px 3px 3px black;
        background-color: lightgreen;
    }

    table {
        border-spacing: 15px;
        visibility: hidden;
        box-shadow: 5px 5px 1px 1px black;
        background-image: linear-gradient(-90deg, lightcoral, orange);

    }

    #board1 {
        position: absolute;
        top: 6%;
        left: 15%;
    }

    #board2 {
        position: absolute;
        top: 6%;
        left: 66%;
    }

    body {
        background-image: linear-gradient(-90deg, lightskyblue, yellow);
        height: 100px;


    }

    h1 {
        text-align: center;
        color: white;
        position: absolute;
        top: 10%;
        left: 45%;
    }


    #fam1 {
        position: absolute;
        top: 10%;
        left: -7%;


    }

    #fam2 {
        position: absolute;
        top: 10%;
        right: -7%;

    }

    #fam3 {
        position: absolute;
        top: 65%;
        left: -7%;

    }

    #fam4 {
        position: absolute;
        top: 65%;
        right: -7%;

    }

    #instructions {
        color: white;
        text-align: center;
        list-style-type: none;
    }

    ul {
        list-style-type: none;

    }

    .startgame {
        position: absolute;
        top: 63%;
        left: 46%;
    }

    #player1 {
        visibility: hidden;
    }

    #intr {
        position: absolute;
        left: 23%;
        top: 20%;
    }

    #questionsasked {
        white-space: nowrap;
    }

    #howtoplay {
        position: absolute;
        top: 25%;
        left: 30%;
    }

    #x1 {
        position: absolute;
        top: 32%;
        left: 63%;


    }

    #x2 {
        position: absolute;
        top: 42%;
        left: 63%;


    }

    #x3 {
        position: absolute;
        top: 52%;
        left: 63%;


    }

    #x4 {
        position: absolute;
        top: 62%;
        left: 63%;


    }

    #x5 {
        position: absolute;
        top: 72%;
        left: 63%;


    }

    #point1 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 33%;
        left: 63%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;


    }

    #point2 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 43%;
        left: 63%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;
    }

    #point3 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 53%;
        left: 63%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;
    }

    #point4 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 63%;
        left: 63%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;
    }

    #point5 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 73%;
        left: 63%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;
    }

    #p2x1 {
        position: absolute;
        top: 32%;
        left: 70%;


    }

    #p2x2 {
        position: absolute;
        top: 42%;
        left: 70%;


    }

    #p2x3 {
        position: absolute;
        top: 52%;
        left: 70%;


    }

    #p2x4 {
        position: absolute;
        top: 62%;
        left: 70%;


    }

    #p2x5 {
        position: absolute;
        top: 72%;
        left: 70%;


    }

    #p2point1 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 33%;
        left: 70%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;


    }

    #p2point2 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 43%;
        left: 70%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;
    }

    #p2point3 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 53%;
        left: 70%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;
    }

    #p2point4 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 63%;
        left: 70%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;
    }

    #p2point5 {
        border-style: solid;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 73%;
        left: 70%;
        border-color: darkblue;
        border-width: thick;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        font-size: xx-large;
    }

    .startgame button {
        width: 100px;
        height: 50px;
        background: greenyellow;
        transition: width 0.5s linear;

    }

    .startgame button:hover {
        width: 120px;
        background-image: linear-gradient(-90deg, lightskyblue, yellow);
    }

    button:hover {
        background-image: linear-gradient(-90deg, lightseagreen, lightskyblue);


    }


    #p1name:hover {
        border-color: darkred;


    }

    #p2name:hover {
        border-color: darkred;


    }

    #q1:hover {
        border-color: slateblue;
    }

    #q1no {
        position: absolute;
        top: 40%;
        left: 45%;
        border-style: solid;
        border-color: #e21f00;
        visibility: hidden;
    }

    #q2no {
        position: absolute;
        top: 50%;
        left: 45%;
        border-style: solid;
        border-color: #e21f00;
        visibility: hidden;
    }

    #q3no {
        position: absolute;
        top: 60%;
        left: 45%;
        border-style: solid;
        border-color: #e21f00;
        visibility: hidden;
    }

    #q4no {
        position: absolute;
        top: 70%;
        left: 45%;
        border-style: solid;
        border-color: #e21f00;
        visibility: hidden;
    }

    #q5no {
        position: absolute;
        top: 80%;
        left: 45%;
        border-style: solid;
        border-color: #e21f00;
        visibility: hidden;
    }

    #timer1 {
        font-size: xx-large;
        border-style: inset;
        border-width: thick;
        margin-left: 1265px;
        margin-right: 65px;
        margin-top: -120px;
        text-align: center;
        visibility: hidden;


    }

    #timer2 {
        font-size: xx-large;
        border-style: inset;
        border-width: thick;
        margin-left: 1265px;
        margin-right: 65px;
        margin-top: -55px;
        text-align: center;
        visibility: hidden;


    }

    #scorekeep {
        border-style: inset;
        border-color: orangered;
        border-radius: 20px 20px 20px 20px;
        text-align: center;
        width: 50px;
        height: 50px;
        position: absolute;
        top: 12%;
        left: 4.5%;
        visibility: hidden;
        font-size: xx-large;
        color: #e21f00;

    }


</style>
<body>
<div class="everything">
    <table style="width:20%" id="board1">
        <tr>
            <th id="player1name1"></th>
            <th id="player2name1"></th>
            <th>Total</th>
        </tr>
        <tr>
            <td id="player1score1"></td>
            <td id="player2score1"></td>
            <td id="totalscore1"></td>
        </tr>
    </table>
    <table style="width:20%" id="board2">
        <tr>
            <th id="player1name2"></th>
            <th id="player2name2"></th>
            <th>Total</th>
        </tr>
        <tr>
            <td id="player1score2"></td>
            <td id="player2score2"></td>
            <td id="totalscore2"></td>
        </tr>
    </table>
    <div id="x1">
        <img src=" https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="x2">
        <img src="https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="x3">
        <img src="https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="x4">
        <img src="https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="x5">
        <img src="https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="p2x1">
        <img src=" https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="p2x2">
        <img src="https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="p2x3">
        <img src="https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="p2x4">
        <img src="https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="p2x5">
        <img src="https://vignette.wikia.nocookie.net/gameshows/images/2/22/Family_Feud_Strike_Indicator.png/revision/latest/scale-to-width-down/340?cb=20160216060413"
             style="height:18%; width:18%" alt="x">
    </div>
    <div id="border">
    </div>
    <h1>Fast Money</h1>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <div id="instructions">
        <div id="howtoplay">
            <h4>How to play</h4>
            <ul>
                <li>1. This is a 2 player game, Pick 2 people to play</li>
                <li>2. Player 1 stays and player 2 goes somewhere else</li>
                <li>3. 5 questions will appear and you will have 1 minute to answer them</li>
                <li>4. Once you are done it will be player 2's turn and the same thing will happen</li>
                <li>5. Player 2 will not be allowed to give the same answer as player 1</li>
                <li>6. Points are awarded depending on your answer</li>
                <li>7. If the total points is above 200 you win if not you lose</li>
            </ul>
        </div>
        <div id="fam1">
            <img src=" https://image.cnbcfm.com/api/v1/image/105029061-fast-money-1900-podcast.png?v=1519655151&w=678&h=381"
                 style="height:50%; width:50%" alt="fast money">
        </div>
        <div id="fam2">
            <img src="https://image.cnbcfm.com/api/v1/image/105029061-fast-money-1900-podcast.png?v=1519655151&w=678&h=381"
                 style="height:50%; width:50%" alt="fast money">
        </div>
        <div id="fam3">
            <img src=" https://image.cnbcfm.com/api/v1/image/105029061-fast-money-1900-podcast.png?v=1519655151&w=678&h=381"
                 style="height:50%; width:50%" alt="fast money">
        </div>
        <div id="fam4">
            <img src="https://image.cnbcfm.com/api/v1/image/105029061-fast-money-1900-podcast.png?v=1519655151&w=678&h=381"
                 style="height:50%; width:50%" alt="fast money">
        </div>
        <div class="startgame">
            <button onclick="startgame()">Start Game</button>
        </div>
    </div>
    <div id="player1">
        <div id="intr">
            <h4>
                Player 1 answer these questions and press submit when finished, you have only 1 minute to do so... Good
                Luck!!!
            </h4>
        </div>
        <div id="questionsasked">
            <div id="q1">
                <h2>
                </h2>
            </div>
            <div id="q2">
                <h2>
                </h2>
            </div>
            <div id="q3">
                <h2>
                </h2>
            </div>
            <div id="q4">
                <h2>
                </h2>
            </div>
            <div id="q5">
                <h2>
                </h2>
            </div>
        </div>
    </div>
    <div id="point1">
        <h1>
        </h1>
    </div>
    <div id="point2">
        <h1>
        </h1>
    </div>
    <div id="point3">
        <h1>
        </h1>
    </div>
    <div id="point4">
        <h1>
        </h1>
    </div>
    <div id="point5">
        <h1>
        </h1>
    </div>
    <div id="p2point1">
        <h1>
        </h1>
    </div>
    <div id="p2point2">
        <h1>
        </h1>
    </div>
    <div id="p2point3">
        <h1>
        </h1>
    </div>
    <div id="p2point4">
        <h1>
        </h1>
    </div>
    <div id="p2point5">
        <h1>
        </h1>
    </div>
    <div id="p1name">
        <h1>
        </h1>
    </div>
    <div id="p2name">
        <h1>
        </h1>
    </div>
    <div id="q1no">
        <h4>
        </h4>
    </div>
    <div id="q2no">
        <h4>
        </h4>
    </div>
    <div id="q3no">
        <h4>
        </h4>
    </div>
    <div id="q4no">
        <h4>
        </h4>
    </div>
    <div id="q5no">
        <h4>
        </h4>
    </div>
    <div id="timer1">
        <h4>
        </h4>
    </div>
    <div id="timer2">
        <h4>
        </h4>
    </div>
    <audio id="win" hidden>
        <source src="win.mp3" type="audio/mpeg">
    </audio>
    <audio id="loss" hidden>
        <source src="loss.mp3" type="audio/mpeg">
    </audio>
    <div id="scorekeep">
    </div>
    <div id="highscoreimage">
        <img src="data:image/png;base64,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"
             style="height:11%; width:7%; position: absolute; top: 0.5%; left: 3%;" alt="high score">
    </div>
</div>
<script>
    //hide stuff
    document.getElementById('highscoreimage').style.visibility = 'hidden';
    document.getElementById("x1").style.visibility = 'hidden';
    document.getElementById("x2").style.visibility = 'hidden';
    document.getElementById("x3").style.visibility = 'hidden';
    document.getElementById("x4").style.visibility = 'hidden';
    document.getElementById("x5").style.visibility = 'hidden';
    document.getElementById("point1").style.visibility = "hidden";
    document.getElementById("point2").style.visibility = "hidden";
    document.getElementById("point3").style.visibility = "hidden";
    document.getElementById("point4").style.visibility = "hidden";
    document.getElementById("point5").style.visibility = "hidden";
    document.getElementById('p2x1').style.visibility = "hidden";
    document.getElementById('p2x2').style.visibility = "hidden";
    document.getElementById('p2x3').style.visibility = "hidden";
    document.getElementById('p2x4').style.visibility = "hidden";
    document.getElementById('p2x5').style.visibility = "hidden";
    document.getElementById('p2point1').style.visibility = "hidden";
    document.getElementById('p2point2').style.visibility = "hidden";
    document.getElementById('p2point3').style.visibility = "hidden";
    document.getElementById('p2point4').style.visibility = "hidden";
    document.getElementById('p2point5').style.visibility = "hidden";

    let input1;
    let timer1 = 59;
    let timer2 = 59;
    let input2;
    let input3;
    let input4;
    let input5;
    let answer1;
    let answer2;
    let answer3;
    let answer4;
    let answer5;
    let getquestionbtn;
    let p1submitbtn;
    let text;
    let p1score = 0;
    let p2score = 0;
    let totalscore = 0;
    let p1nameinput;
    let p2nameinput;
    let p1name;
    let p2name;
    let player1answer1;
    let player1answer2;
    let player1answer3;
    let player1answer4;
    let player1answer5;
    let playagain;

    let currscorep1 = 0;

    function startgame() {
        document.getElementById("instructions").style.visibility = "hidden";
        document.body.style.backgroundColor = "green";
        document.getElementById("player1").style.visibility = "visible"; //got this from w3schools
        getquestionbtn = document.createElement("button");
        getquestionbtn.id = 'getquestions';
        text = document.createTextNode("Get your questions");
        getquestionbtn.appendChild(text);
        document.body.appendChild(getquestionbtn);
        getquestionbtn.onclick = player1start;
        getquestionbtn.style.position = "absolute";
        getquestionbtn.style.top = "35%";
        getquestionbtn.style.left = "46%";
        p1nameinput = document.createElement("INPUT");
        document.body.appendChild(p1nameinput);
        p1nameinput.setAttribute("type", "text");
        p1nameinput.setAttribute("id", "p1name");
        p1nameinput.setAttribute("placeholder", "insert p1 name"); //https://stackoverflow.com/questions/1626107/text-in-html-field-to-disappear-when-clicked
        p2nameinput = document.createElement("INPUT");
        p2nameinput.setAttribute("type", "text");
        p2nameinput.setAttribute("id", "p2name");
        p2nameinput.style.color = "black";
        p1nameinput.style.color = "black";
        p2nameinput.setAttribute("placeholder", "insert p2 name");
        document.body.appendChild(p2nameinput);
        p1nameinput.style.position = "absolute";
        p1nameinput.style.top = "40%";
        p1nameinput.style.left = "37%";
        p2nameinput.style.position = "absolute";
        p2nameinput.style.top = "40%";
        p2nameinput.style.left = "53%";


    }

    let question1;
    let question2;
    let question3;
    let question4;
    let question5;
    let questionset;
    let text1;
    let p2start;

    function player1start() {
        sethighscore1();
        document.getElementById('highscoreimage').style.visibility = 'visible';
        document.getElementById('scorekeep').style.visibility = 'visible';

        if (p1nameinput.value === '') {
            p1name = 'P1';
        } else {
            p1name = p1nameinput.value;
        }
        if (p2nameinput.value === '') {
            p2name = 'P2';
        } else {
            p2name = p2nameinput.value;
        }
        document.getElementById('player1name1').innerHTML = p1name;
        document.getElementById('player1name2').innerHTML = p1name;
        document.getElementById('player2name1').innerHTML = p2name;
        document.getElementById('player2name2').innerHTML = p2name;
        document.getElementsByClassName('player2name').innerHTML = p2name;
        document.getElementById('board1').style.visibility = 'visible';
        document.getElementById('board2').style.visibility = 'visible';
        p2nameinput.parentNode.removeChild(p2nameinput);
        p1nameinput.parentNode.removeChild(p1nameinput);


        let questiongenerator = Math.floor(Math.random() * 3) + 1;
        if (questiongenerator === 1) {
            questionset = 1;
            question1 = "Name a reason you might get rid of a family heirloom";
            question2 = "Name something you haven't done since high school gym class";
            question3 = "Tell me something that costs a dollar or less";
            question4 = "Name a country that speaks spanish";
            question5 = "Name a liquid in your kitchen that you hope no one accidentally drinks";


        } else if (questiongenerator === 2) {
            questionset = 2;
            question1 = "Where do kids nowadays spend most of their time?";
            question2 = "Name something that breaks down";
            question3 = "Name a famous wizard";
            question4 = "How many pairs of socks does a fast food worker wear in a week";
            question5 = "Name another word for book";

        } else if (questiongenerator === 3) {
            questionset = 3;
            question1 = "Name something that people do just once a week";
            question2 = "Name a piece of furniture that might be hand made";
            question3 = "How long is an 'unbearable' commute";
            question4 = "Name something you always have to keep plugged in";
            question5 = "Name a Harry potter character";

        }
        getquestionbtn.parentNode.removeChild(getquestionbtn);
        //create P1 input  //https://www.w3schools.com/jsref/dom_obj_text.asp
        input1 = document.createElement("INPUT");
        input1.setAttribute("type", "text");
        input1.setAttribute("id", "input1");
        document.body.appendChild(input1);
        input1.style.borderColor = 'grey';
        document.getElementById("q1").innerHTML = question1;
        input1.style.position = "absolute";
        input1.style.top = "35%";
        input1.style.left = "50%";

        document.getElementById("q1").style.position = "absolute";
        document.getElementById("q1").style.top = "35%";
        document.getElementById("q1").style.left = "15%";
        document.getElementById("q1").style.textwrap = "nowrap";
        input1.style.boxShadow = "0px 0px 10px blue";


        input2 = document.createElement("INPUT");
        input2.setAttribute("type", "text");
        input2.setAttribute("id", "input2");
        document.body.appendChild(input2);
        document.getElementById("q2").innerHTML = question2;
        input2.style.position = "absolute";
        input2.style.top = "45%";
        input2.style.left = "50%";
        input2.style.borderColor = 'grey';
        document.getElementById("q2").style.position = "absolute";
        document.getElementById("q2").style.top = "45%";
        document.getElementById("q2").style.left = "15%";
        document.getElementById("q2").style.textwrap = "nowrap";
        input2.style.boxShadow = "0px 0px 10px red";


        input3 = document.createElement("INPUT");
        input3.setAttribute("type", "text");
        input3.setAttribute("id", "input3");
        document.body.appendChild(input3);
        document.getElementById("q3").innerHTML = question3;
        input3.style.position = "absolute";
        input3.style.top = "55%";
        input3.style.left = "50%";
        input3.style.borderColor = 'grey';
        document.getElementById("q3").style.position = "absolute";
        document.getElementById("q3").style.top = "55%";
        document.getElementById("q3").style.left = "15%";
        document.getElementById("q3").style.textwrap = "nowrap";
        input3.style.boxShadow = "0px 0px 10px yellow";


        input4 = document.createElement("INPUT");
        input4.setAttribute("type", "text");
        input4.setAttribute("id", "input4");
        document.body.appendChild(input4);
        document.getElementById("q4").innerHTML = question4;
        input4.style.position = "absolute";
        input4.style.top = "65%";
        input4.style.left = "50%";
        input4.style.borderColor = 'grey';
        document.getElementById("q4").style.position = "absolute";
        document.getElementById("q4").style.top = "65%";
        document.getElementById("q4").style.left = "15%";
        document.getElementById("q4").style.textwrap = "nowrap";
        input4.style.boxShadow = "0px 0px 10px red";


        input5 = document.createElement("INPUT");
        input5.setAttribute("type", "text");
        input5.setAttribute("id", "input5");
        document.body.appendChild(input5);
        document.getElementById("q5").innerHTML = question5;
        input5.style.position = "absolute";
        input5.style.top = "75%";
        input5.style.left = "50%";
        input5.style.borderColor = 'grey';
        document.getElementById("q5").style.position = "absolute";
        document.getElementById("q5").style.top = "75%";
        document.getElementById("q5").style.left = "15%";
        document.getElementById("q5").style.textwrap = "nowrap";
        input5.style.boxShadow = "0px 0px 10px blue";


        //Submit button
        p1submitbtn = document.createElement("button");
        text1 = document.createTextNode("Submit Answers");
        document.body.appendChild(p1submitbtn);
        p1submitbtn.appendChild(text1);
        p1submitbtn.onclick = p1submit;
        p1submitbtn.style.position = "absolute";
        p1submitbtn.style.top = "85%";
        p1submitbtn.style.left = "46%";


        //set the timer
        setTimeout(t1, 60000);
        setInterval(vis_t1, 1000);
        document.getElementById('timer1').style.visibility = "visible";


    }

    function p1submit() {
        answer1 = document.getElementById("input1").value;
        answer2 = document.getElementById("input2").value;
        answer3 = document.getElementById("input3").value;
        answer4 = document.getElementById("input4").value;
        answer5 = document.getElementById("input5").value;
        answer1 = answer1.toLowerCase();
        answer2 = answer2.toLowerCase();
        answer3 = answer3.toLowerCase();
        answer4 = answer4.toLowerCase();
        answer5 = answer5.toLowerCase();
        //https://www.w3schools.com/jsref/jsref_includes.asp
        if (questionset === 1) {
            if (answer1.includes("broken")) {
                p1score = p1score + 29;
                document.getElementById('point1').innerHTML = '29';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("ugly")) {
                p1score = p1score + 22;
                document.getElementById('point1').innerHTML = '22';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("divorce")) {
                p1score = p1score + 18;
                document.getElementById('point1').innerHTML = '18';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("sell") || answer1.includes("money")) {
                p1score = p1score + 12;
                document.getElementById('point1').innerHTML = '12';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("stuff")) {
                p1score = p1score + 10;
                document.getElementById('point1').innerHTML = '10';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("feud")) {
                p1score = p1score + 5;
                document.getElementById('point1').innerHTML = '5';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("moving")) {
                p1score = p1score + 2;
                document.getElementById('point1').innerHTML = '2';
                document.getElementById("point1").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x1").style.visibility = "visible";
            }
            if (answer2.includes("run")) {
                p1score = p1score + 25;
                document.getElementById('point2').innerHTML = '25';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("pushup")) {
                p1score = p1score + 21;
                document.getElementById('point2').innerHTML = '21';
                document.getElementById("point2").style.visibility = "visible";

            } else if (answer2.includes("dodgeball")) {
                p1score = p1score + 23;
                document.getElementById('point2').innerHTML = '23';
                document.getElementById("point2").style.visibility = "visible";

            } else if (answer2.includes("sit") || answer2.includes("crunch")) {
                p1score = p1score + 9;
                document.getElementById('point2').innerHTML = '9';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("lift") || answer2.includes("weight")) {
                p1score = p1score + 8;
                document.getElementById('point2').innerHTML = '8';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("swim")) {
                document.getElementById('point2').innerHTML = '5';
                p1score = p1score + 5;
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("change") || answer2.includes("locker")) {
                p1score = p1score + 3;
                document.getElementById('point2').innerHTML = '3';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("tennis")) {
                p1score = p1score + 2;
                document.getElementById('point2').innerHTML = '2';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("exercise")) {
                p1score = p1score + 2;
                document.getElementById('point2').innerHTML = '2';
                document.getElementById("point2").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x2").style.visibility = "visible";
            }
            if (answer3.includes("fruit")) {
                p1score = p1score + 29;
                document.getElementById('point3').innerHTML = '29';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("fast") || answer3.includes("food")) {
                p1score = p1score + 23;
                document.getElementById('point3').innerHTML = '23';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("soft") || answer3.includes("drink") || answer3.includes("soda")) {
                p1score = p1score + 17;
                document.getElementById('point3').innerHTML = '17';
                document.getElementById("point3").style.visibility = "visible";

            } else if (answer3.includes("news") || answer3.includes("paper")) {
                p1score = p1score + 10;
                document.getElementById('point3').innerHTML = '10';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("stamp")) {
                p1score = p1score + 6;
                document.getElementById('point3').innerHTML = '6';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("gum")) {
                p1score = p1score + 4;
                document.getElementById('point3').innerHTML = '4';
                document.getElementById("point3").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x3").style.visibility = "visible";
            }
            if (answer4.includes("spain")) {
                p1score = p1score + 38;
                document.getElementById('point4').innerHTML = '38';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("mexico")) {
                p1score = p1score + 24;
                document.getElementById('point4').innerHTML = '24';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("usa") || answer4.includes("us") || answer4.includes("united")) {
                p1score = p1score + 10;
                document.getElementById('point4').innerHTML = '10';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("cuba")) {
                p1score = p1score + 10;
                document.getElementById('point4').innerHTML = '10';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("argentina")) {
                p1score = p1score + 4;
                document.getElementById('point4').innerHTML = '4';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("costa")) {
                p1score = p1score + 3;
                document.getElementById('point4').innerHTML = '3';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("chile")) {
                p1score = p1score + 3;
                document.getElementById('point4').innerHTML = '3';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("columbia")) {
                p1score = p1score + 3;
                document.getElementById('point4').innerHTML = '3';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("guatemala")) {
                p1score = p1score + 2;
                document.getElementById('point4').innerHTML = '2';
                document.getElementById("point4").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x4").style.visibility = "visible";
            }
            if (answer5.includes("soap")) {
                p1score = p1score + 46;
                document.getElementById('point5').innerHTML = '46';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("vinegar")) {
                p1score = p1score + 30;
                document.getElementById('point5').innerHTML = '30';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("oil")) {
                p1score = p1score + 16;
                document.getElementById('point5').innerHTML = '16';
                document.getElementById("point5").style.visibility = "visible";

            } else if (answer5.includes("soy")) {
                p1score = p1score + 4;
                document.getElementById('point5').innerHTML = '4';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("grease")) {
                p1score = p1score + 2;
                document.getElementById('point5').innerHTML = '2';
                document.getElementById("point5").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x5").style.visibility = "visible";
            }

        } else if (questionset === 2) {
            if (answer1.includes("room") || answer1.includes("bed")) {
                p1score = p1score + 28;
                document.getElementById('point1').innerHTML = '28';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("school")) {
                p1score = p1score + 22;
                document.getElementById('point1').innerHTML = '22';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("internet") || answer1.includes("web")) {
                p1score = p1score + 16;
                document.getElementById('point1').innerHTML = '16';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("mall") || answer1.includes("shop")) {
                p1score = p1score + 12;
                document.getElementById('point1').innerHTML = '12';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("friend")) {
                p1score = p1score + 10;
                document.getElementById('point1').innerHTML = '10';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("park") || answer1.includes("out")) {
                p1score = p1score + 4;
                document.getElementById('point1').innerHTML = '4';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("work")) {
                p1score = p1score + 4;
                document.getElementById('point1').innerHTML = '4';
                document.getElementById("point1").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x1").style.visibility = "visible";
            }
            if (answer2.includes("car")) {
                p1score = p1score + 44;
                document.getElementById('point2').innerHTML = '44';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("computer")) {
                p1score = p1score + 17;
                document.getElementById('point2').innerHTML = '17';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("communication")) {
                p1score = p1score + 7;
                document.getElementById('point2').innerHTML = '7';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("foreign")) {
                p1score = p1score + 2;
                document.getElementById('point2').innerHTML = '2';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("tv")) {
                p1score = p1score + 2;
                document.getElementById('point2').innerHTML = '2';
                document.getElementById("point2").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x2").style.visibility = "visible";
            }

            if (answer3.includes("harry")) {
                p1score = p1score + 37;
                document.getElementById('point3').innerHTML = '37';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("merlin")) {
                p1score = p1score + 26;
                document.getElementById('point3').innerHTML = '26';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("gandalf")) {
                p1score = p1score + 11;
                document.getElementById('point3').innerHTML = '11';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("oz")) {
                p1score = p1score + 9;
                document.getElementById('point3').innerHTML = '9';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("dr")) {
                p1score = p1score + 8;
                document.getElementById('point3').innerHTML = '8';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("voldemort")) {
                p1score = p1score + 3;
                document.getElementById('point3').innerHTML = '3';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("newt")) {
                p1score = p1score + 2;
                document.getElementById('point3').innerHTML = '2';
                document.getElementById("point3").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x3").style.visibility = "visible";
            }

            if (answer4.includes("7")) {
                p1score = p1score + 25;
                document.getElementById('point4').innerHTML = '25';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("10")) {
                p1score = p1score + 23;
                document.getElementById('point4').innerHTML = '23';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("14")) {
                p1score = p1score + 20;
                document.getElementById('point4').innerHTML = '20';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("15")) {
                p1score = p1score + 9;
                document.getElementById('point4').innerHTML = '9';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("2")) {
                p1score = p1score + 7;
                document.getElementById('point4').innerHTML = '7';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("20")) {
                p1score = p1score + 5;
                document.getElementById('point4').innerHTML = '5';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("5")) {
                p1score = p1score + 3;
                document.getElementById('point4').innerHTML = '3';
                document.getElementById("point4").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x4").style.visibility = "visible";
            }

            if (answer5.includes("novel")) {
                p1score = p1score + 55;
                document.getElementById('point5').innerHTML = '55';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("story")) {
                p1score = p1score + 16;
                document.getElementById('point5').innerHTML = '16';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("paperback")) {
                p1score = p1score + 10;
                document.getElementById('point5').innerHTML = '10';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("pamphlet")) {
                p1score = p1score + 4;
                document.getElementById('point5').innerHTML = '4';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("tome")) {
                p1score = p1score + 4;
                document.getElementById('point5').innerHTML = '4';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("volume")) {
                p1score = p1score + 3;
                document.getElementById('point5').innerHTML = '3';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("publication")) {
                p1score = p1score + 3;
                document.getElementById('point5').innerHTML = '3';
                document.getElementById("point5").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x5").style.visibility = "visible";
            }


        } else if (questionset === 3) {
            if (answer1.includes("church")) {
                p1score = p1score + 35;
                document.getElementById('point1').innerHTML = '35';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("groceries") || answer1.includes("shop")) {
                p1score = p1score + 24;
                document.getElementById('point1').innerHTML = '24';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("laundry")) {
                p1score = p1score + 12;
                document.getElementById('point1').innerHTML = '12';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("clean")) {
                p1score = p1score + 6;
                document.getElementById('point1').innerHTML = '6';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("sleep")) {
                p1score = p1score + 6;
                document.getElementById('point1').innerHTML = '6';
                document.getElementById("point1").style.visibility = "visible";
            } else if (answer1.includes("eat out")) {
                p1score = p1score + 4;
                document.getElementById('point1').innerHTML = '4';
                document.getElementById("point1").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x1").style.visibility = "visible";
            }

            if (answer2.includes("table")) {
                p1score = p1score + 41;
                document.getElementById('point2').innerHTML = '41';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("chair")) {
                p1score = p1score + 31;
                document.getElementById('point2').innerHTML = '31';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("shelf")) {
                p1score = p1score + 12;
                document.getElementById('point2').innerHTML = '12';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("dresser")) {
                p1score = p1score + 5;
                document.getElementById('point2').innerHTML = '5';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("bed")) {
                p1score = p1score + 2;
                document.getElementById('point2').innerHTML = '2';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("cabinet")) {
                p1score = p1score + 2;
                document.getElementById('point2').innerHTML = '2';
                document.getElementById("point2").style.visibility = "visible";
            } else if (answer2.includes("bench")) {
                p1score = p1score + 2;
                document.getElementById('point2').innerHTML = '2';
                document.getElementById("point2").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x2").style.visibility = "visible";
            }

            if (answer3.includes("1 hour") || answer3.includes('1')) {
                p1score = p1score + 41;
                document.getElementById('point3').innerHTML = '41';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("30 min")) {
                p1score = p1score + 26;
                document.getElementById('point3').innerHTML = '26';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("45 min")) {
                p1score = p1score + 15;
                document.getElementById('point3').innerHTML = '15';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("20 min")) {
                p1score = p1score + 6;
                document.getElementById('point3').innerHTML = '6';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("2 h")) {
                p1score = p1score + 5;
                document.getElementById('point3').innerHTML = '5';
                document.getElementById("point3").style.visibility = "visible";
            } else if (answer3.includes("1.5 hours")) {
                p1score = p1score + 2;
                document.getElementById('point3').innerHTML = '2';
                document.getElementById("point3").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x3").style.visibility = "visible";
            }


            if (answer4.includes("tv")) {
                p1score = p1score + 33;
                document.getElementById('point4').innerHTML = '33';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("phone")) {
                p1score = p1score + 25;
                document.getElementById('point4').innerHTML = '25';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("computer")) {
                p1score = p1score + 24;
                document.getElementById('point4').innerHTML = '24';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("lamp")) {
                p1score = p1score + 11;
                document.getElementById('point4').innerHTML = '11';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("headphones")) {
                p1score = p1score + 2;
                document.getElementById('point4').innerHTML = '2';
                document.getElementById("point4").style.visibility = "visible";
            } else if (answer4.includes("mouse")) {
                p1score = p1score + 2;
                document.getElementById('point4').innerHTML = '2';
                document.getElementById("point4").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x4").style.visibility = "visible";
            }


            if (answer5.includes("harry")) {
                p1score = p1score + 52;
                document.getElementById('point5').innerHTML = '52';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("hermione")) {
                p1score = p1score + 16;
                document.getElementById('point5').innerHTML = '16';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("ron")) {
                p1score = p1score + 14;
                document.getElementById('point5').innerHTML = '14';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("fred") || answer5.includes("george")) {
                p1score = p1score + 5;
                document.getElementById('point5').innerHTML = '5';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("newt")) {
                p1score = p1score + 5;
                document.getElementById('point5').innerHTML = '5';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("dumbledore")) {
                p1score = p1score + 3;
                document.getElementById('point5').innerHTML = '3';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("snape")) {
                p1score = p1score + 2;
                document.getElementById('point5').innerHTML = '2';
                document.getElementById("point5").style.visibility = "visible";
            } else if (answer5.includes("hagrid")) {
                p1score = p1score + 2;
                document.getElementById('point5').innerHTML = '2';
                document.getElementById("point5").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("x5").style.visibility = "visible";
            }
            //setting the answers P2 can't give

        }


        player1answer1 = answer1;
        player1answer2 = answer2;
        player1answer3 = answer3;
        player1answer4 = answer4;
        player1answer5 = answer5;


        document.getElementById('q1no').innerHTML = ("P2, you can't say " + player1answer1);
        document.getElementById('q2no').innerHTML = ("P2, you can't say " + player1answer2);
        document.getElementById('q3no').innerHTML = ("P2, you can't say " + player1answer3);
        document.getElementById('q4no').innerHTML = ("P2, you can't say " + player1answer4);
        document.getElementById('q5no').innerHTML = ("P2, you can't say " + player1answer5);
        document.getElementById('q1no').style.visibility = "visible";
        document.getElementById('q2no').style.visibility = "visible";
        document.getElementById('q3no').style.visibility = "visible";
        document.getElementById('q4no').style.visibility = "visible";
        document.getElementById('q5no').style.visibility = "visible";


        //remove submit button & add P2 button
        p1submitbtn.parentNode.removeChild(p1submitbtn);
        p2start = document.createElement("button");
        text1 = document.createTextNode("P2 Submit");
        document.body.appendChild(p2start);
        p2start.appendChild(text1);
        p2start.onclick = P2start;
        p2start.style.position = "absolute";
        p2start.style.top = "85%";
        p2start.style.left = "46%";

        setTimeout(t2, 60000);
        setInterval(vis_t2, 1000);
        document.getElementById('timer2').style.visibility = 'visible';
        document.getElementById('timer1').style.visibility = 'hidden';
        timer1 = 0;


        //clear inputs & swap text
        document.getElementById('input1').value = ' ';
        document.getElementById('input2').value = ' ';
        document.getElementById('input3').value = ' ';
        document.getElementById('input4').value = ' ';
        document.getElementById('input5').value = ' ';
        document.getElementById('intr').innerHTML = "P2 now it's your turn you can't give the same answer as P1, if you do you will be awarded 0 points";
        document.getElementById('intr').style.top = '25%';
        document.getElementById('intr').style.left = '27%';

        //update score board

        document.getElementById('player1score1').innerHTML = p1score;
        document.getElementById('player1score2').innerHTML = p1score;
        timestop2++;

    }

    function P2start() {
        answer1 = document.getElementById('input1').value;
        answer2 = document.getElementById('input2').value;
        answer3 = document.getElementById('input3').value;
        answer4 = document.getElementById('input4').value;
        answer5 = document.getElementById('input5').value;
        answer1 = answer1.toLowerCase();
        answer2 = answer2.toLowerCase();
        answer3 = answer3.toLowerCase();
        answer4 = answer4.toLowerCase();
        answer5 = answer5.toLowerCase();


        if (questionset === 1) {
            if (answer1.includes(player1answer1) || player1answer1.includes(answer1)){
                document.getElementById("p2x1").style.visibility = "visible";
                console.log(answer1);
                console.log(player1answer1);
            } else if (answer1.includes("broken")) {
                p2score = p2score + 29;
                document.getElementById('p2point1').innerHTML = '29';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("ugly")) {
                p2score = p2score + 22;
                document.getElementById('p2point1').innerHTML = '22';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("divorce")) {
                p2score = p2score + 18;
                document.getElementById('p2point1').innerHTML = '18';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("sell") || answer1.includes("money")) {
                p2score = p2score + 12;
                document.getElementById('p2point1').innerHTML = '12';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("stuff")) {
                p2score = p2score + 10;
                document.getElementById('p2point1').innerHTML = '10';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("feud")) {
                p2score = p2score + 5;
                document.getElementById('p2point1').innerHTML = '5';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("moving")) {
                p2score = p2score + 2;
                document.getElementById('p2point1').innerHTML = '2';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x1").style.visibility = "visible";
            }
            if (answer2.includes(player1answer2) || player1answer2.includes(answer2)) {
                document.getElementById("p2x2").style.visibility = "visible";
            } else if (answer2.includes("run")) {
                p2score = p2score + 25;
                document.getElementById('p2point2').innerHTML = '25';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("pushup")) {
                p2score = p2score + 21;
                document.getElementById('p2point2').innerHTML = '21';
                document.getElementById("p2point2").style.visibility = "visible";

            } else if (answer2.includes("dodgeball")) {
                p2score = p2score + 23;
                document.getElementById('p2point2').innerHTML = '23';
                document.getElementById("p2point2").style.visibility = "visible";

            } else if (answer2.includes("sit") || answer2.includes("crunch")) {
                p2score = p2score + 9;
                document.getElementById('p2point2').innerHTML = '9';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("lift") || answer2.includes("weight")) {
                p2score = p2score + 8;
                document.getElementById('p2point2').innerHTML = '8';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("swim")) {
                document.getElementById('p2point2').innerHTML = '5';
                p2score = p2score + 5;
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("change") || answer2.includes("locker")) {
                p2score = p2score + 3;
                document.getElementById('p2point2').innerHTML = '3';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("tennis")) {
                p2score = p2score + 2;
                document.getElementById('p2point2').innerHTML = '2';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("exercise")) {
                p2score = p2score + 2;
                document.getElementById('p2point2').innerHTML = '2';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x2").style.visibility = "visible";
            }
            if (answer3.includes(player1answer3) || player1answer3.includes(answer3)) {
                document.getElementById("p2x3").style.visibility = "visible";
            } else if (answer3.includes("fruit")) {
                p2score = p2score + 29;
                document.getElementById('p2point3').innerHTML = '29';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("fast") || answer3.includes("food")) {
                p2score = p2score + 23;
                document.getElementById('p2point3').innerHTML = '23';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("soft") || answer3.includes("drink") || answer3.includes("soda")) {
                p2score = p2score + 17;
                document.getElementById('p2point3').innerHTML = '17';
                document.getElementById("p2point3").style.visibility = "visible";

            } else if (answer3.includes("news") || answer3.includes("paper")) {
                p2score = p2score + 10;
                document.getElementById('p2point3').innerHTML = '10';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("stamp")) {
                p2score = p2score + 6;
                document.getElementById('p2point3').innerHTML = '6';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("gum")) {
                p2score = p2score + 4;
                document.getElementById('p2point3').innerHTML = '4';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x3").style.visibility = "visible";
            }
            if (answer4.includes(player1answer4) || player1answer4.includes(answer4)) {
                document.getElementById("p2x4").style.visibility = "visible";
            } else if (answer4.includes("spain")) {
                p2score = p2score + 38;
                document.getElementById('p2point4').innerHTML = '38';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("mexico")) {
                p2score = p2score + 24;
                document.getElementById('p2point4').innerHTML = '24';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("usa") || answer4.includes("us") || answer4.includes("united")) {
                p2score = p2score + 10;
                document.getElementById('p2point4').innerHTML = '10';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("cuba")) {
                p2score = p2score + 10;
                document.getElementById('p2point4').innerHTML = '10';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("argentina")) {
                p2score = p2score + 4;
                document.getElementById('p2point4').innerHTML = '4';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("costa")) {
                p2score = p2score + 3;
                document.getElementById('p2point4').innerHTML = '3';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("chile")) {
                p2score = p2score + 3;
                document.getElementById('p2point4').innerHTML = '3';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("columbia")) {
                p2score = p2score + 3;
                document.getElementById('p2point4').innerHTML = '3';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("guatemala")) {
                p2score = p2score + 2;
                document.getElementById('p2point4').innerHTML = '2';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x4").style.visibility = "visible";
            }
            if (answer5.includes(player1answer5) || player1answer5.includes(answer5)) {
                document.getElementById("p2x5").style.visibility = "visible";
            } else if (answer5.includes("soap")) {
                p2score = p2score + 46;
                document.getElementById('p2point5').innerHTML = '46';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("vinegar")) {
                p2score = p2score + 30;
                document.getElementById('p2point5').innerHTML = '30';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("oil")) {
                p2score = p2score + 16;
                document.getElementById('p2point5').innerHTML = '16';
                document.getElementById("p2point5").style.visibility = "visible";

            } else if (answer5.includes("soy")) {
                p2score = p2score + 4;
                document.getElementById('p2point5').innerHTML = '4';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("grease")) {
                p2score = p2score + 2;
                document.getElementById('p2point5').innerHTML = '2';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x5").style.visibility = "visible";
            }

        } else if (questionset === 2) {
            if (answer1.includes(player1answer1) || player1answer1.includes(answer1)) {
                document.getElementById("p2x1").style.visibility = "visible";
            } else if (answer1.includes("room") || answer1.includes("bed")) {
                p2score = p2score + 28;
                document.getElementById('p2point1').innerHTML = '28';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("school")) {
                p2score = p2score + 22;
                document.getElementById('p2point1').innerHTML = '22';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("internet") || answer1.includes("web")) {
                p2score = p2score + 16;
                document.getElementById('p2point1').innerHTML = '16';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("mall") || answer1.includes("shop")) {
                p2score = p2score + 12;
                document.getElementById('p2point1').innerHTML = '12';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("friend")) {
                p2score = p2score + 10;
                document.getElementById('p2point1').innerHTML = '10';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("park") || answer1.includes("out")) {
                p2score = p2score + 4;
                document.getElementById('p2point1').innerHTML = '4';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("work")) {
                p2score = p2score + 4;
                document.getElementById('p2point1').innerHTML = '4';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x1").style.visibility = "visible";
            }
            if (answer2.includes(player1answer2) || player1answer2.includes(answer2)) {
                document.getElementById("p2x2").style.visibility = "visible";
            } else if (answer2.includes("car")) {
                p2score = p2score + 44;
                document.getElementById('p2point2').innerHTML = '44';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("computer")) {
                p2score = p2score + 17;
                document.getElementById('p2point2').innerHTML = '17';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("communication")) {
                p2score = p2score + 7;
                document.getElementById('p2point2').innerHTML = '7';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("foreign")) {
                p2score = p2score + 2;
                document.getElementById('p2point2').innerHTML = '2';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("tv")) {
                p2score = p2score + 2;
                document.getElementById('p2point2').innerHTML = '2';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x2").style.visibility = "visible";
            }
            if (answer3.includes(player1answer3) || player1answer3.includes(answer3)) {
                document.getElementById("p2x3").style.visibility = "visible";
            } else if (answer3.includes("harry")) {
                p2score = p2score + 37;
                document.getElementById('p2point3').innerHTML = '37';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("merlin")) {
                p2score = p2score + 26;
                document.getElementById('p2point3').innerHTML = '26';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("gandalf")) {
                p2score = p2score + 11;
                document.getElementById('p2point3').innerHTML = '11';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("oz")) {
                p2score = p2score + 9;
                document.getElementById('p2point3').innerHTML = '9';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("dr")) {
                p2score = p2score + 8;
                document.getElementById('p2point3').innerHTML = '8';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("voldemort")) {
                p2score = p2score + 3;
                document.getElementById('p2point3').innerHTML = '3';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("newt")) {
                p2score = p2score + 2;
                document.getElementById('p2point3').innerHTML = '2';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x3").style.visibility = "visible";
            }
            if (answer4.includes(player1answer4) || player1answer4.includes(answer4)) {
                document.getElementById("p2x4").style.visibility = "visible";
            } else if (answer4.includes("7")) {
                p2score = p2score + 25;
                document.getElementById('p2point4').innerHTML = '25';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("10")) {
                p2score = p2score + 23;
                document.getElementById('p2point4').innerHTML = '23';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("14")) {
                p2score = p2score + 20;
                document.getElementById('p2point4').innerHTML = '20';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("15")) {
                p2score = p2score + 9;
                document.getElementById('p2point4').innerHTML = '9';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("2")) {
                p2score = p2score + 7;
                document.getElementById('p2point4').innerHTML = '7';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("20")) {
                p2score = p2score + 5;
                document.getElementById('p2point4').innerHTML = '5';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("5")) {
                p2score = p2score + 3;
                document.getElementById('p2point4').innerHTML = '3';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x4").style.visibility = "visible";
            }
            if (answer5.includes(player1answer5) || player1answer5.includes(answer5)) {
                document.getElementById("p2x5").style.visibility = "visible";
            } else if (answer5.includes("novel")) {
                p2score = p2score + 55;
                document.getElementById('p2point5').innerHTML = '55';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("story")) {
                p2score = p2score + 16;
                document.getElementById('p2point5').innerHTML = '16';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("paperback")) {
                p2score = p2score + 10;
                document.getElementById('p2point5').innerHTML = '10';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("pamphlet")) {
                p2score = p2score + 4;
                document.getElementById('p2point5').innerHTML = '4';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("tome")) {
                p2score = p2score + 4;
                document.getElementById('p2point5').innerHTML = '4';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("volume")) {
                p2score = p2score + 3;
                document.getElementById('p2point5').innerHTML = '3';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("publication")) {
                p2score = p2score + 3;
                document.getElementById('p2point5').innerHTML = '3';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x5").style.visibility = "visible";
            }


        } else if (questionset === 3) {
            if (answer1.includes(player1answer1) || player1answer1.includes(answer1)) {
                document.getElementById("p2x1").style.visibility = "visible";
            } else if (answer1.includes("church")) {
                p2score = p2score + 35;
                document.getElementById('p2point1').innerHTML = '35';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("groceries") || answer1.includes("shop")) {
                p2score = p2score + 24;
                document.getElementById('p2point1').innerHTML = '24';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("laundry")) {
                p2score = p2score + 12;
                document.getElementById('p2point1').innerHTML = '12';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("clean")) {
                p2score = p2score + 6;
                document.getElementById('p2point1').innerHTML = '6';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("sleep")) {
                p2score = p2score + 6;
                document.getElementById('p2point1').innerHTML = '6';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (answer1.includes("eat out")) {
                p2score = p2score + 4;
                document.getElementById('p2point1').innerHTML = '4';
                document.getElementById("p2point1").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x1").style.visibility = "visible";
            }
            if (answer2.includes(player1answer2) || player1answer2.includes(answer2)) {
                document.getElementById("p2x2").style.visibility = "visible";
            } else if (answer2.includes("table")) {
                p2score = p2score + 41;
                document.getElementById('p2point2').innerHTML = '41';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("chair")) {
                p2score = p2score + 31;
                document.getElementById('p2point2').innerHTML = '31';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("shelf")) {
                p2score = p2score + 12;
                document.getElementById('p2point2').innerHTML = '12';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("dresser")) {
                p2score = p2score + 5;
                document.getElementById('p2point2').innerHTML = '5';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("bed")) {
                p2score = p2score + 2;
                document.getElementById('p2point2').innerHTML = '2';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("cabinet")) {
                p2score = p2score + 2;
                document.getElementById('p2point2').innerHTML = '2';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (answer2.includes("bench")) {
                p2score = p2score + 2;
                document.getElementById('p2point2').innerHTML = '2';
                document.getElementById("p2point2").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x2").style.visibility = "visible";
            }
            if (answer3.includes(player1answer3) || player1answer3.includes(answer3)) {
                document.getElementById("p2x3").style.visibility = "visible";
            } else if (answer3.includes("1 hour") || answer3.includes('1')) {
                p2score = p2score + 41;
                document.getElementById('p2point3').innerHTML = '41';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("30 min")) {
                p2score = p2score + 26;
                document.getElementById('p2point3').innerHTML = '26';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("45 min")) {
                p2score = p2score + 15;
                document.getElementById('p2point3').innerHTML = '15';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("20 min")) {
                p2score = p2score + 6;
                document.getElementById('p2point3').innerHTML = '6';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("2 h")) {
                p2score = p2score + 5;
                document.getElementById('p2point3').innerHTML = '5';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (answer3.includes("1.5 hours")) {
                p2score = p2score + 2;
                document.getElementById('p2point3').innerHTML = '2';
                document.getElementById("p2point3").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x3").style.visibility = "visible";
            }
            if (answer4.includes(player1answer4) || player1answer4.includes(answer4)) {
                document.getElementById("p2x4").style.visibility = "visible";
            } else if (answer4.includes("tv")) {
                p2score = p2score + 33;
                document.getElementById('p2point4').innerHTML = '33';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("phone")) {
                p2score = p2score + 25;
                document.getElementById('p2point4').innerHTML = '25';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("computer")) {
                p2score = p2score + 24;
                document.getElementById('p2point4').innerHTML = '24';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("lamp")) {
                p2score = p2score + 11;
                document.getElementById('p2point4').innerHTML = '11';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("headphones")) {
                p2score = p2score + 2;
                document.getElementById('p2point4').innerHTML = '2';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (answer4.includes("mouse")) {
                p2score = p2score + 2;
                document.getElementById('p2point4').innerHTML = '2';
                document.getElementById("p2point4").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x4").style.visibility = "visible";
            }
            if (answer5.includes(player1answer5) || player1answer5.includes(answer5)) {
                document.getElementById("p2x5").style.visibility = "visible";
            } else if (answer5.includes("harry")) {
                p2score = p2score + 52;
                document.getElementById('p2point5').innerHTML = '52';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("hermione")) {
                p2score = p2score + 16;
                document.getElementById('p2point5').innerHTML = '16';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("ron")) {
                p2score = p2score + 14;
                document.getElementById('p2point5').innerHTML = '14';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("fred") || answer5.includes("george")) {
                p2score = p2score + 5;
                document.getElementById('p2point5').innerHTML = '5';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("newt")) {
                p2score = p2score + 5;
                document.getElementById('p2point5').innerHTML = '5';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("dumbledore")) {
                p2score = p2score + 3;
                document.getElementById('p2point5').innerHTML = '3';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("snape")) {
                p2score = p2score + 2;
                document.getElementById('p2point5').innerHTML = '2';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (answer5.includes("hagrid")) {
                p2score = p2score + 2;
                document.getElementById('p2point5').innerHTML = '2';
                document.getElementById("p2point5").style.visibility = "visible";
            } else if (currscorep1 === 0) {
                document.getElementById("p2x5").style.visibility = "visible";
            }

        }
        document.getElementById('q1no').style.visibility = "hidden";
        document.getElementById('q2no').style.visibility = "hidden";
        document.getElementById('q3no').style.visibility = "hidden";
        document.getElementById('q4no').style.visibility = "hidden";
        document.getElementById('q5no').style.visibility = "hidden";
        //update score
        totalscore = p1score + p2score;
        totalscore = String(totalscore);
        document.getElementById('player2score1').innerHTML = p2score;
        document.getElementById('player2score2').innerHTML = p2score;
        document.getElementById('totalscore1').innerHTML = totalscore;
        document.getElementById('totalscore2').innerHTML = totalscore;


        p2start.parentNode.removeChild(p2start);
        timer2 = 0;


        // win or lose
        if (totalscore < 200) {
            setTimeout(youlose, 2500);
        } else if (totalscore >= 200) {
            setTimeout(youwin, 2500);

        }
        sethighscore2();
    }

    function youlose() {
        document.body.style.backgroundImage = "url('https://i.pinimg.com/originals/c6/0b/0c/c60b0c9f441f523e67e64afc52bec690.gif')";
        document.getElementById('questionsasked').style.visibility = 'hidden';
        document.getElementById("x1").style.visibility = 'hidden';
        document.getElementById("x2").style.visibility = 'hidden';
        document.getElementById("x3").style.visibility = 'hidden';
        document.getElementById("x4").style.visibility = 'hidden';
        document.getElementById("x5").style.visibility = 'hidden';
        document.getElementById("point1").style.visibility = "hidden";
        document.getElementById("point2").style.visibility = "hidden";
        document.getElementById("point3").style.visibility = "hidden";
        document.getElementById("point4").style.visibility = "hidden";
        document.getElementById("point5").style.visibility = "hidden";
        document.getElementById('p2x1').style.visibility = "hidden";
        document.getElementById('p2x2').style.visibility = "hidden";
        document.getElementById('p2x3').style.visibility = "hidden";
        document.getElementById('p2x4').style.visibility = "hidden";
        document.getElementById('p2x5').style.visibility = "hidden";
        document.getElementById('p2point1').style.visibility = "hidden";
        document.getElementById('p2point2').style.visibility = "hidden";
        document.getElementById('p2point3').style.visibility = "hidden";
        document.getElementById('p2point4').style.visibility = "hidden";
        document.getElementById('p2point5').style.visibility = "hidden";
        document.getElementById('input1').style.visibility = "hidden";
        document.getElementById('input2').style.visibility = "hidden";
        document.getElementById('input3').style.visibility = "hidden";
        document.getElementById('input4').style.visibility = "hidden";
        document.getElementById('input5').style.visibility = "hidden";
        document.getElementById('intr').style.visibility = "hidden";

        //replace p2button with playagain button


        playagain = document.createElement("button");
        text1 = document.createTextNode("You lose, Play again?");
        document.body.appendChild(playagain);
        playagain.appendChild(text1);
        playagain.onclick = again;
        playagain.style.position = "absolute";
        playagain.style.top = "50%";
        playagain.style.left = "46%";
        playagain.style.width = '200px';
        playagain.style.height = '50px';
        playagain.style.backgroundColor = 'darkslateblue';
        document.getElementById('loss').play();
        timestop1++;


    }

    function youwin() {
        document.body.style.backgroundImage = "url('https://thumbs.gfycat.com/GlaringSmoggyCanvasback-size_restricted.gif')";
        document.getElementById('win').play();
        document.getElementById('questionsasked').style.visibility = 'hidden';
        document.getElementById("x1").style.visibility = 'hidden';
        document.getElementById("x2").style.visibility = 'hidden';
        document.getElementById("x3").style.visibility = 'hidden';
        document.getElementById("x4").style.visibility = 'hidden';
        document.getElementById("x5").style.visibility = 'hidden';
        document.getElementById("point1").style.visibility = "hidden";
        document.getElementById("point2").style.visibility = "hidden";
        document.getElementById("point3").style.visibility = "hidden";
        document.getElementById("point4").style.visibility = "hidden";
        document.getElementById("point5").style.visibility = "hidden";
        document.getElementById('p2x1').style.visibility = "hidden";
        document.getElementById('p2x2').style.visibility = "hidden";
        document.getElementById('p2x3').style.visibility = "hidden";
        document.getElementById('p2x4').style.visibility = "hidden";
        document.getElementById('p2x5').style.visibility = "hidden";
        document.getElementById('p2point1').style.visibility = "hidden";
        document.getElementById('p2point2').style.visibility = "hidden";
        document.getElementById('p2point3').style.visibility = "hidden";
        document.getElementById('p2point4').style.visibility = "hidden";
        document.getElementById('p2point5').style.visibility = "hidden";
        document.getElementById('input1').style.visibility = "hidden";
        document.getElementById('input2').style.visibility = "hidden";
        document.getElementById('input3').style.visibility = "hidden";
        document.getElementById('input4').style.visibility = "hidden";
        document.getElementById('input5').style.visibility = "hidden";
        document.getElementById('intr').style.visibility = "hidden";

        playagain = document.createElement("button");
        text1 = document.createTextNode("You Win!!, Play again?");
        document.body.appendChild(playagain);
        playagain.appendChild(text1);
        playagain.onclick = again;
        playagain.style.position = "absolute";
        playagain.style.top = "50%";
        playagain.style.left = "40%";
        playagain.style.width = '200px';
        playagain.style.height = '50px';
        playagain.style.backgroundColor = 'darkslateblue';
        timestop1++;
    }

    let timestop1 = 1;
    let timestop2 = 1;

    function t1() {
        if (timestop2 === 1) {
            p1submit();
        }
    }

    function t2() {
        if (timestop1 === 1) {
            P2start();
        }


    }

    function vis_t1() {
        if (timer1 >= 0) {
            timer1 = String(timer1);
            document.getElementById('timer1').innerHTML = timer1;
            timer1 = Number(timer1);
            timer1--;
        } else {
            document.getElementById('timer1').style.visibility = 'hidden';
        }

    }

    function vis_t2() {
        if (timer2 >= 0) {
            timer2 = String(timer2);
            document.getElementById('timer2').innerHTML = timer2;
            timer2 = Number(timer2);
            timer2--;
        } else {
            document.getElementById('timer2').style.visibility = 'hidden';
        }
    }


    function again() {
        window.location.reload(); //https://stackoverflow.com/questions/42049696/is-there-a-way-to-reset-an-html-page-using-a-javascript-function
    }

    let highscore = 0;


    function sethighscore1() {
        document.getElementById("scorekeep").innerHTML = localStorage.getItem("highscore");
        console.log(localStorage.getItem("highscore"))

    }

    let score;

    function sethighscore2() {
        console.log(totalscore);
        score = Number(localStorage.getItem('highscore'));
        if (totalscore > score) {
            localStorage.setItem("highscore", totalscore);
        }
        document.getElementById("scorekeep").innerHTML = localStorage.getItem("highscore");

    }
</script>


</body>
