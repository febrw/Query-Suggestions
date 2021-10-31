# Query Suggestion module for Stack Overflow Search


A module for generating query suggestions based on the user's current input. This module was integrated into our Stack Overflow search engine, 'www.sosearch.ninja' (now defunct).
Inspired by "Query Suggestions in the Absence of Query Logs". We train an N-gram language model (n<=3) on a dataset containing Stack Overflow's entire dataset of question and answer posts, using Bayesian Estimation.

Implemented in Python with Jupyter Notebooks.

File Descriptions:

englishST.txt : A list of English stop words, retained, but skipped in the count towards an N-gram.

100k.pickle : A reduced dataset of 100,000 question posts for testing and mini-model building (full dataset too large to host here)
