SET myNumb TO 2
SEND "please enter guess number" TO DISPLAY
RECIEVE guess FROM KEYBOARD
IF guess >10 THEN
SEND "Too high! Your guess must be between 1 and 10" TO DISPLAY
ELSE
IF guess = myNumb THEN
SEND "Well done! You guessed correctly." TO DISPLAY
ELSE 
SEND "Bad luck! The correct number is" = myNumb TO DISPLAY
IF END
IF END
IF END
END
