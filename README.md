# unstructured_data_university_towns

This code Returns a DataFrame of towns and the states they are in from the university_towns.txt list. The format of the DataFrame should be:DataFrame( [ ["Michigan", "Ann Arbor"], ["Michigan", "Yipsilanti"] ], columns=["State", "RegionName"] )

The following cleaning needs to be done:

a) For "State", it removes characters from "[" to the end.

b) For "RegionName", when applicable, it removes every character from " (" to the end.

Dataset: 'university_towns.txt'

Source of Dataset: https://en.wikipedia.org/wiki/List_of_college_towns#College_towns_in_the_United_States
