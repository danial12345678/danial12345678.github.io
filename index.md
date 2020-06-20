<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>

        #c1 {
             background-color: lightskyblue;
             border-color: blue;
             padding: 15px 32px;
             text-align: center;
             text-decoration: none;
             display: inline-block;
             font-size: 16px;
             margin: 4px 2px;
            position:absolute;top: 0;left: 0;
         }
        #v {
            background-color: lightgreen;
            border-color: darkgreen;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            position:absolute;left: 200px;top: 0;
        }
        #c2 {
            background-color: lightskyblue;
            border-color: blue;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            position:absolute;left: 400px;top: 0;
        }
        #con1{
            position:absolute;top: 100px;left: 0;

        }
        #vowel{
            position:absolute;left: 200px;top: 100px;

        }
        #con2{
            position:absolute;left: 400px;top: 100px;

        }
    </style>
</head>
<body>

<button id="c1" onclick="clickc1()">Consonent</button>
<h1 id="con1">

</h1>
<button id="v" onclick="clickv()">Vowel</button>
<h1 id="vowel">

</h1>
<button id="c2" onclick="clickc2()">Consonent</button>
<h1 id="con2">

</h1>
<script>
    let c1='';
    let v='';
    let c2='';
 function clickc1(){
     if(c1===''){
         c1='B';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='B'){
         c1='C';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='C'){
         c1='D';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='D'){
         c1='F';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='F'){
         c1='G';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='G'){
         c1='H';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='H'){
         c1='J';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='J'){
         c1='K';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='K'){
         c1='L';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='L'){
         c1='M';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='M'){
         c1='N';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='N'){
         c1='P';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='P'){
         c1='Q';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='Q'){
         c1='R';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='R'){
         c1='S';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='S'){
         c1='T';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='T'){
         c1='V';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='V'){
         c1='W';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='W'){
         c1='X';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='X'){
         c1='Y';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='Y'){
         c1='Z';
         document.getElementById('con1').innerHTML=c1;
     }
     else if(c1==='Z'){
         c1='B';
         document.getElementById('con1').innerHTML=c1;
     }

 }
 function clickv(){
     if(v===''){
         v='A';
     document.getElementById('vowel').innerHTML=v;
     }
     else if(v==='A'){
         v='E';
         document.getElementById('vowel').innerHTML=v;
     }
     else if(v==='E'){
         v='I';
         document.getElementById('vowel').innerHTML=v;
     }
     else if(v==='I'){
         v='O';
         document.getElementById('vowel').innerHTML=v;
     }
     else if(v==='O'){
         v='U';
         document.getElementById('vowel').innerHTML=v;
     }
     else if(v==='U'){
         v='A';
         document.getElementById('vowel').innerHTML=v;
     }
 }
 function clickc2(){
     if(c2===''){
         c2='B';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='B'){
         c2='C';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='C'){
         c2='D';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='D'){
         c2='F';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='F'){
         c2='G';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='G'){
         c2='H';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='H'){
         c2='J';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='J'){
         c2='K';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='K'){
         c2='L';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='L'){
         c2='M';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='M'){
         c2='N';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2=='N'){
         c2='P';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='P'){
         c2='Q';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='Q'){
         c2='R';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='R'){
         c2='S';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='S'){
         c2='T';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='T'){
         c2='V';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='V'){
         c2='W';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='W'){
         c2='X';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='X'){
         c2='Y';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='Y'){
         c2='Z';
         document.getElementById('con2').innerHTML=c2;
     }
     else if(c2==='Z'){
         c2='B';
         document.getElementById('con2').innerHTML=c2;
     }

 }

</script>

</body>
</html>