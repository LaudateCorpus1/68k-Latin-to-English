# 68k-Latin-to-English
This program translates any string of Ciceronian Latin into modern English on a Voyage 200 graphing calculator (or other 68k TI device if you reformat the source), granted that the words used in the sentence are contained within the Latin word library used by the program, which will soon encompass every word in the Ecce Romani II textbook. Sending each of these files to your calculator and running identify("Latin word") is all that is needed to demonstrate word translation, while lateng("Latin sentence") will translate any length of Latin passages.

Below are the different files in this repository and their uses:

## adje

  This function returns a Latin adjective ending of a given declension, case, gender, and number.
  
## base

  This function returns the nth word of a substring starting at the fifth character. Returns "" if n is too large. This function is primarily used to find the bases of latin words in wrda
  
## decl

  This function returns the expression of the second character in a string. This function is promarily used to find declension/conjugation of words in wrda.
  
## identify

  This function houses the brunt of the translation, and returns verbose data about any latin word. This function relies on most other functions here to operate, and frequently queries the word index and the dictionary.
  
## lateng

  This function takes a Latin sentence and returns an English sentence.
  
## length

  This function finds the length of a string or number in characters.
  
## noune

  This function returns a Latin noun ending of a given declension, case, gender, and number.
  
## romnum

  This function returns the the roman numeral of any number.
  
## temp

  We don't talk about temp.
  
## verbe

  This function returns a verb ending of a given conjugation, tense, person, and number.
  
## vocorg

  This program facilitates adding words to the library and organizing them alphabetically once you're done, then updating wrdindex.
  
## wlist

  This function returns a list of words within a sentence. No translation, just string to list.
  
## wrda

  This list holds the Latin translations of words.
  
## wrdb

  This list holds the English translation of words.
  
## wrdindex

  This string functions as an index for wrda, holding every base and data pointing those bases to various wrda elements.
