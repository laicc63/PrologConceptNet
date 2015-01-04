PrologConceptNet
================

a prolog version of conceptNet

======================

Only necesary data is preserved in the prolog version

  *for now, it is including only relations in English language

  *it is ignoring additional information that has irregular formats
  
  *it contains only relation between two English words/phrases, other data like source is filtered out

The Prolog version of ConceptNet is parsed from the .csv format of the database

======================

Format of the Prolog version:

a(name_of_relation, English_word_1, English_word_2).

read as: English_word_1       name_of_relation         English_word_2

example:
a('DefinedAs', 'baby', 'very_young_child').

======================
note

single quotes(') in a constant (an English word/phrase) is represented as an asterisk(*)

