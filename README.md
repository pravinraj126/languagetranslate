# languagetranslate
This repository is Language Translate in Python

# - *- coding: utf- 8 - *-

from textblob import TextBlob
word10 = TextBlob(u'தமிழ்')
z = word10.translate(from_lang='ta', to ='en')
print(z)
