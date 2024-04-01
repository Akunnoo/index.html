# Guessing Game
# By: Ernest Sanders 
# CTI-110 Section 0002

Declare Integer targetNumber, guessedNumber

# Test Case 1: Quit functionality
Set targetNumber = 42
Display "Test Case 1: Quit functionality"
Set guessedNumber = 100
While guessedNumber != targetNumber AND guessedNumber != -999
    Input "Enter your guess (-999 to quit): ", guessedNumber
End While
If guessedNumber = -999
    Display "You quit the game."
Else
    Display "You won! The correct number was ", targetNumber
End If

# Test Case 2: Correct guess functionality
Set targetNumber = 73
Display "Test Case 2: Correct guess functionality"
Set guessedNumber = 0
While guessedNumber != targetNumber AND guessedNumber != -999
    Input "Enter your guess (-999 to quit): ", guessedNumber
End While
If guessedNumber = -999
    Display "You quit the game."
Else
    Display "You won! The correct number was ", targetNumber
End If
