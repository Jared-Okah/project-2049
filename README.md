### Problem set [0] : The key must reject duplicate characters regardless of the capitalization status, e.g if key = Aab... (error)
**The attempt:** Used a nested for loop to evaluate every character of the key to prevent duplicates, but couldn't figure out how to store each variable and evaluate which is repeated.
**Logic fix:** Declared a variable which increments if a character matches the key either lowercase or uppercase (by adding or subtracting 32) then returns 1 when its equals to 2.


