Prefix tree



Prefix tree (depicted in the figure that is attached to this project ) is a very efficient data structure that its main advantage is that search(word) 
and startwith(prefix) operations are always in the same complexity and not depend in the words quantity!  
We implemented this strucutre by making a class.

The class contain 3 arguments:
letter = # the node’s letter
children_list = [] # list with all the children’s Trienode objects.
is_last_letter = True/False # indicate if it is the last letter in a word.

and 2 methods:
Insert(“word”) and 
isExit(“word”)
