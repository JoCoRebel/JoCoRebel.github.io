## Number Guessing Game

```mermaid
flowchart TD
Start([Start])
  randomNum(1,100)
  askGuess(Enter your guess from 1 to 100)
  if (guess < randomNum)
    then(Too Low! Try Again!)
    jump askGuess
  else if (guess > randomNum)
    then(Too High! Try Again!)
    jump askGuess
  else
    then(Correct)
    End([You Win!])
End
```
