<h1>Pseudocode for <b>ARMSTRONG NUMBER</b></h1>

* BEGIN
* INPUT A NUMBER A
* DECLARE SUM AND DIGITS AS 0 AND C=A
* FOR A=A TO 1 DECREASING BY 1 FOLLOW THE BELOW STEPS
  * DIGITS=DIGITS+1
  * A=A/10
  * A=A+1
* ENDFOR
* ASSIGN DIGIT=DIGITS AND A=C
* FOR A=A TO 1 DECREASING BY 1 FOLLOW THE BELOW STEPS
    * B=A%10
    * ASSIGN PROD=1
    * DIGITS=DIGIT
    * FOR DIGITS =DIGITS TO 1 DECREASING BY 1 FOLLOW THE BELOW STEP
        * PROD=PROD*B
    * SUM=SUM+PROD
    * A=A/10
    * A=A+1
* ENDFOR
* IF SUM IS SAME AS C
    * DISPLAY "ARMSTRONG NUMBER!!!"
* ELSE
  * DISPLAY "NO"
* ENDIF
* TERMINATE THE PROGRAM
