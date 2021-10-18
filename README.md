# query-suggestion



A module for generating query suggestions based on the user's current input. This module was integrated into our Stack Overflow search engine, 'www.sosearch.ninja' (now defunct).
Inspired by "Query Suggestions in the Absence of Query Logs". We train a N-gram language model (n<=3) on a dataset containing Stack Overflow's question and answer posts, using Bayesian Estimation.

My thanks to the authors for their communication, willingness to assist, and the insights provided to us.
