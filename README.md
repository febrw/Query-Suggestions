# Query Suggestion module for Stack Overflow Search


A module for generating query suggestions based on the user's current input. This module was integrated into our Stack Overflow search engine, 'www.sosearch.ninja' (now defunct).
Inspired by "Query Suggestions in the Absence of Query Logs". We train an N-gram language model (n<=3) on a dataset containing Stack Overflow's entire dataset of question and answer posts, using Bayesian Estimation.

Implemented in Python with Jupyter Notebooks.
