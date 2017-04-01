# Serbian Stemmer

Stemmer for Serbian language, built on Croatian stemmer from <a href="http://nlp.ffzg.hr/">Natural Language Processing group</a> of 
Faculty of Humanities and Social Sciences, University of Zagreb.

Stemmer works for Serbian Latin Alphabet, replaces special characters (č -> c, ć -> c, dž -> dz, đ -> dj, š -> s, ž -> z),
and returns lowercase characters.

In general, stemmer works best on adjectives and nouns.

## Usage

Download <b>rules.txt</b>, <b>transformations.txt</b> and <b>serbian_stemmer.py</b> files and put them in same directory.

```
from serbian_stemmer import stem

output_text = stem(input_text)
```

Stemmer is written in Python 3.4.
