# Hey-Jude---Algorithm-PHP

###### Created on : 10-Oct-2018, 04:02:26 PM
###### Author     : Marc Freir
###### License    : This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License.

##### CODE PREVIEW

```php
    <?php
        $titlevalue = 1;
        function writeTitle() {
            $title = "Hey Jude";
            echo $title;
        }

        function writeDont() {
            $statementDont = ", don't ";
            echo $statementDont;
        }
        
        function writeRememberto() {
            $statementRememberto = "remember to ";
            echo $statementRememberto;
        }

        function writeThenYou() {
            $statementThenYou = "then you ";
            echo $statementThenYou;
        }

        function writeToMakeItBetter() {
            $statementToMakeItBetter = " to make it better ";
            echo $statementToMakeItBetter;
        }

        function writeWaaaaa() {
            $statementWaaaaa = " waaaaa ";
            echo $statementWaaaaa;
        }

        //calling the function writeTitle
        writeTitle();
        echo "<br>";
        echo "<br>";

        for ($titlevalue = 1; $titlevalue == 1; $titlevalue ++) {           

            $verseP3 = array(" make it bad", " be afraid", " let me down");
            $verseP4 = array(" take a sad song and make it better", " you were made to go out and get her", " you have found her, now go and get her");
            $verseP5 = array(" let her into your heart", " let her under your skin");
            $verseP6 = array(" can start", " begin");

            foreach ($verseP3 as $va) {
                writeTitle();
                writeDont();
                echo "$va";
                echo "<br>";
                
                if ($va == " make it bad") {
                    echo $verseP4[0];
                }
                elseif ($va == " be afraid") {
                    echo $verseP4[1];
                }
                elseif ($va == " let me down") {
                    echo $verseP4[2];
                }
                
                echo "<br>";
                writeRememberto();

                if ($va == " make it bad") {
                    echo $verseP5[0];
                    echo "<br>";
                    writeThenYou();
                    echo $verseP6[0];
                    writeToMakeItBetter();
                    echo "<br>";
                    for ($bt = 1; $bt < 6; $bt++) {
                        echo "better ";
                    }
                    writeWaaaaa();
                    echo "<br>";
                    for ($na = 1; $na < 9; $na++) {
                        echo "na ";
                    }
                    writeTitle();
                }
                elseif ($va == " be afraid") {
                    echo $verseP5[1];
                    echo "<br>";
                    writeThenYou();
                    echo $verseP6[1];
                    writeToMakeItBetter();
                    echo "<br>";
                    for ($bt = 1; $bt < 6; $bt++) {
                        echo "better ";
                    }
                    writeWaaaaa();
                    echo "<br>";
                    for ($na = 1; $na < 9; $na++) {
                        echo "na ";
                    }
                    writeTitle();
                }
                elseif ($va == " let me down") {
                    echo $verseP5[0];
                    echo "<br>";
                    writeThenYou();
                    echo $verseP6[0];
                    writeToMakeItBetter();
                    echo "<br>";
                    for ($bt = 1; $bt < 6; $bt++) {
                        echo "better ";
                    }
                    writeWaaaaa();
                    echo "<br>";
                    for ($na = 1; $na < 9; $na++) {
                        echo "na ";
                    }
                    writeTitle();
                }
                echo "<br>";
                echo "<br>";
            }
            echo "<br>";

        }

    ?>

```
##### IMAGE PREVIEW
![alt text](https://github.com/marcfreir/Hey-Jude---Algorithm-PHP/blob/master/_PREVIEW/preview.png)
