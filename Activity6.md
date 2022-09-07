SEND 'Please enter the first number' To DISPLAY
RECEIVE firstNumber FROM KEYBOARD
SEND 'Please enter the second number' To DISPLAY
RECEIVE secondNumber FROM KEYBOARD
SEND 'Please enter the third number' To DISPLAY
RECEIVE thirdNumber FROM KEYBOARD
SET total TO (firstNumber + secondNumber + thirdNumber) / 3
SEND total TO DISPLAY
