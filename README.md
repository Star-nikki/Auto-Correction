# Auto-Correction

We will start with one of the primary applications of NLP that is autocorrection. This is like a hello world problem in NLP. So the question is as follows: we should develop an algorithm that auto-corrects the wrong words and suggests the correct ones.

For example: if the input is given as “alphabat,” the algorithm should return “alphabet”. Now let us understand the algorithm. Basically, it involves four steps.

1. To identify the misspelled word.
2. To find all the words which are n distance away.
3. Filter them.
4. Calculate word probabilities.
