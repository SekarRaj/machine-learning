https://eng.uber.com/lsh/

**Stemming** - Stemming is the process of reducing inflection in words (e.g. troubled, troubles) to their root form (e.g. trouble). The “root” in this case may not be a real root word, but just a canonical form of the original word.

The most common algorithm, which is also known to be empirically effective for English, is (Porters Algorithm)[https://tartarus.org/martin/PorterStemmer/]

better alternative - embeddings

**Lemmatization**
Lemmatization on the surface is very similar to stemming, where the goal is to remove inflections and map a word to its root form. The only difference is that, lemmatization tries to do it the proper way. It doesn’t just chop things off, it actually transforms words to the actual root. For example, the word “better” would map to “good”. 

https://www.kdnuggets.com/2019/04/text-preprocessing-nlp-machine-learning.html