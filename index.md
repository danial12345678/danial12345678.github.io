<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Bowling</title>
</head>
<body>
<script>

    let thro= 1;
    let score=0;
    let turns=1;
    while(turns<=10) {
        while (thro > 0) {
            let one = prompt('how many pins did you knock down on your first throw?');
            one = Number(one);
            let two = prompt('how many pins did you knock down on your second throw?');
            two = Number(two);
            if (Number(one) + Number(two) === 10 && Number(two) > 0) {
                alert('spare!!!');
                score = Number(score) + 5;
                thro = thro - 1;
            } else if (one === 10 && two === 0) {
                score = score + 10;
                alert('strike!!!');
                thro = thro - 1;
            }
            else if(one+two>10 ||one+two<0){
                alert('try again');
                one = prompt('how many pins did you knock down on your first throw?');
                one = Number(one);
                two = prompt('how many pins did you knock down on your second throw?');
                two = Number(two);
            }
            else{
                thro=thro-1;
            }
            score = Number(score) + Number(one) + Number(two);
            document.write(String('turn'+turns+' '+score + 'pts'));
            document.write("<br/>");
        }

        turns=turns+1;
        thro=thro+1;
        alert('frame '+turns)
    }

</script>
</body>
</html>