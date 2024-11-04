# quantex
This respository contains practice data sets for use in module SET013

Description of data sets
------------------------
this file may be updated from time to time, so it may look different if you re-download at a later stage of the semester



#### *questionnaire_simple.csv*

file location: on Learning Central (in the materials of the relevant weeks); also https://bit.ly/3Y9TWWZ
contains the data we gathered in week 2

- AGE: years completed since birth
- GENDER: f = female, m = male
- ATT1 = 'Using abbreviations in text messages is acceptable'; Likert scale 1-5; the lower the value, the more positive
- ATT2 = 'The following sentence uses bad grammar: "I have less books than my friend."'; Likert scale 1-5; the higher the value, the more positive


#### *questionnaire.csv*

file location: on Learning Central (in the materials of the relevant weeks)
Contains the data we gathered in week 2, with subsequent combination and adjustment of ATT1/ATT2 and the addition of AGE.GRP
Variables:

- AGE: years completed since birth
- GEN: f = female, m = male, o = other/don't want to say
- CHANGE: values from 1 to 10 indicating the attitude to linguistic change, where 10 = very positive and 1 = very negative
- AGE.GRP: mature = aged between 30 and infinite, young = aged between 0 and 30


#### *phrases.csv*

alternative file location: https://tinyurl.com/48xrdz3x
Contains ratings of 1501 word sequences with regard to whether they are set phrases


#### *test_scores.txt*

alternative file location: https://goo.gl/WJQctc
Contains fictitious scores of 25 students on a language proficiency test and some personal data on the participants

- SP: score for speaking
- LI: score for listening
- RE: score for reading
- WR: score for writing
- ID: student ID
- AGE: age in comleted years since birth
- L1: E = first language is a European language, N = first language is non-european
- OVERALL: The overall score in the proficiency test across reading, writing, speaking, listening
- GENDER: M = male, F = female


#### *AUGEN.csv*

alternative file location: https://goo.gl/fH1eGC
Contains relative frequencies of the word sequence 'blaue[n] Augen' (i.e. blue eyes) in German books over the 20th century.
Source: Google Books (https://books.google.com/ngrams/)
Variables: 
- YEAR: the year
- AUGEN: the relative frequency (relative to corpus size for the year) of 'blaue[n] Augen'


#### *CLsurvey.csv*

alternative file location: https://goo.gl/FmocIb
Contains data on article types that have appeared in the Journal of Cognitive Linguistics over the years 1990 to 2012. The data are from Janda (2013), kindly supplied by the author.
Variables:

- YEAR: year of publication
- QUANT.ART: number of articles employing quantitative methods
- TOTAL.ART: total number of articles that have appeared


#### *Texts.csv*

alternative file location: https://goo.gl/WKviKl
Contains data on the length of 16 texts and their translations. The data are adapted from Gries (2013)
Variables:

- CASE: case numbering
- LENGTH: length in words of the text
- TEXT: the text-ID number, where the original and translation each have the same text ID
- TEXTSOURCE: whether the case is 'Original' or 'Translation'
- LANGUAGE: the language in which the text is written


#### *RASINGER201.CSV*

alternative file location: https://goo.gl/1hRXvS
Contains data set discussed in Rasinger (2013) p. 201. Those are listening test scores for people before and after receiving certain treatment.


#### *newTS.csv*

alternative file location: https://goo.gl/DqkL65
structure similar to test_scores, but with age groups added and some of the values adjusted

#### *newTS2.csv*
alternative https://goo.gl/bn2TXp


#### *F1.csv*

alternative file location: https://goo.gl/KK4qQ4
Contains the measured frequency of the first formant in test vowels for a set of participants, both males and females
Variables:

- Hz_F1: frequency in Hertz of the first formant
- SEX: gender of the participant


#### *reaction_times.csv*

alternative file location: https://goo.gl/NwHsMf
Contains fictitious data on a reaction time experiment. 4 subjects were shown 4 collocations (one per trial) and had to decide whether they were seeing real actual words or made-up words. 2 trials were under neutral condition, and 2 trials while playing music in the background. Reaction times were measured between subjects being shown the collocation and their hitting either the 'word' or 'non-word' button. Whether their choice was correct was also recorded.
Variables:

- SUBJ: subject ID
- TRIAL: number of the trial, trials were conducted in the order indicated
- COND: 1 = with music, 0 = without music
- RT: reaction time in milliseconds
- CORRECT: 1 = correct response, 0 = incorrect response 


#### *Reaction.csv*

alternative file location: https://goo.gl/Srpb9J
Contains data taken from Gries (2013) on a reaction time experiment where participants were shown words on a screen and they had to press one button or the other to indicate whether these are real words of English. Scores for frequency and familiarity of each of the words is also included.


#### *RT2.csv*

alternative file location: https://goo.gl/zPFaI1
Contains ficitious data on reaction times in a word recognition tasks. The task was to press the YES button if a real word is shown, or the NO button if a nonsense word is shown (data adapted from Gries 2013).
Variables:

- WORD_L: length of the word in letters
- RT_MS: reaction time in milliseconds


#### *synonyms.csv*

alternative file location: https://goo.gl/zfK9Pj
This is a data set from Gries (2013) and contains ficticious data from an experiment where 5 subjects were asked to
write down as many synonyms as they could in 30 seconds for 8 words (different 8 words for each subject). This was used
to measure how good subjects were at finding synonyms, depending on whether the words given had a positive or negative
connotation and also whether the words were adjectives, adverbs, nouns or verbs.

- CASE: just indicating the case number (there are 40 cases in total)
- SUBJECT: which of the five subjects produced the scores (the values are a, b, c, d, e)
- MEANING: the words given to subjects had either positive or negative connotations
- POS: the parts of speech of the words given to subjects (adjectives, adverbs, nouns and verbs)
- SYNONYMS: how good subjects were in producing synonyms (on a scale from 1 to 20)


#### *CoLA_judgements1.csv*

alternative file location: https://tinyurl.com/mrb4kv87
This is a data set adapted from https://nyu-mll.github.io/CoLA/ and it shows grammaticality judgements of two raters
