# Attention-Based Neural Machine Translation

Here I trained an attention-based neural machine  translation model to translate words from English to Pig Latin.

# Pig Latin Explanation
Pig Latin is a transformation of English based on the following rules 
(applied on a per-word basis):
* If the first letter of a word is a consonant, then the letter is moved to the 
end of the word, and the letters “ay” are added to the end: team eamtay.
* If the first letter is a vowel, then the word is left unchanged and the 
letters “way” are added to the end: impress impressway.
* In addition, some consonant pairs, such as “sh”, are treated as a block 
and are moved to the end of the string together: shopping oppingshay.

To translate a whole sentence from English to Pig Latin, we simply apply 
these rules to each word independently:
i went shopping iway entway oppingshay


Further details are provided in the Assignemnt Details pdf


Assignemnt is adapted from COSI 114b at Brandeis University
