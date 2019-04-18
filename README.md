# Boolean-Space-Model
Boolean Space Model is a Information Retrieval Model.The Boolean retrieval model views each document as just a set of words (Multi-set).
The Boolean retrieval model is a model for information retrieval in which we can pose any query which is in the form of a Boolean expression of terms, that is, in which terms
are combined with the operators AND ,OR, and NOT.
To answer the query Brutus AND Caesar AND
NOT Calpurnia, we take the vectors for
Brutus, Caesar and Calpurnia, complement
the last, and then do a bitwise AND:
110100 AND 110111 AND 101111 = 100100
