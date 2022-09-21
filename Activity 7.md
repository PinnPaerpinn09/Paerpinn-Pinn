SET number TO 3
SEND "Please enter guess number"
To DISPLAY RECIEVE guess FROM keyboard 
IF guess > 10 THEN 
SEND "To high" TO DISPLAY
ELSE IF guess = number THEN
SEND "Well done" TO DISPLAY
ELSE SEND "Bad luck" 
END IF
END IF
