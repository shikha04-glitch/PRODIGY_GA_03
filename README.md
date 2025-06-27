# PRODIGY_GA_03
🔁 Markov Chain Text Generator

This script builds a simple Markov chain from a given text and uses it to generate new, random-like text that mimics the style of the input.


---

🧠 What the Code Does

1. build_markov_chain():

Takes an input text and splits it into words.

Builds a Markov chain (a dictionary) where each key is a word or pair of words, and the value is a list of possible next words that follow in the original text.



2. generate_text():

Starts from a random word (or given seed).

Picks the next word based on the current state, using the Markov chain.

Repeats this for a fixed number of words (default is 20).

The result is a new sentence that feels like the original, but is randomly generated.



3. Example Input:

> A short snippet from Shakespeare's Hamlet is used as the source text.




4. Example Output: The script prints a randomly generated sentence like:

🔮 Generated Text:
To be, that is the question. Wheather 'tis nobler in the mind to suffer
