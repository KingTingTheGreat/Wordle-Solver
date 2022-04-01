# Wordle-Solver
Position-based Wordle Solver

User inputs feedback from the game via a 5-number String of 0s, 1s, and 2s
0s represent gray letters (not in the word)
1s represent green letters (correct letters in the correct position)
2s represent yellow letters (correct letters in the wrong position)

if the only possible answers left are similar, will guess a word using the letters they don't have in common
for example, if the words left are 'bound', 'found', 'wound', 'sound', it will guess 'brash'

