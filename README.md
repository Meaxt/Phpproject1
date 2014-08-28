Phpproject1
===========

Första projektet i kursen php
<html>
    <head>
        <meta charset="UTF-8">
        <title></title>
    </head>
    <body>
        <?php
       echo "Din iq plus din fingerlängd visar hur smart du är:";
        //först skapa vi variabler
        $iq = 10;
        $fingerlängd = 33;
        $summa = $iq + $fingerlängd;
        //vi plussade talen
        echo $summa;
        echo "<br>";
        //talen skrevs ut.
        $ord1 = "Du är otroligt dum ";
        $ord2 = "Du är okej ";
        $ord3 = "Smart ass";
        
        if($summa==30){
            echo $ord2;
           
        }elseif ($summa<30) {
            echo $ord1;
            
        }  else {
            echo $ord3;
        }
        echo '<br>';
        switch ($summa){
            case 1:
                echo "Bananer";
                break;
            case 3:
                echo 'Äta glass';
                break;
            case 43: 
                echo 'Du kan flyga';
                break;
        }
        ?>
    </body>
</html>