# unstructured_data_university_towns

This code Returns a DataFrame of towns and the states they are in from the unstructured university_towns.txt dataset. The format of the final cleaned dataFrame is in the form:

DataFrame( [ ["Michigan", "Ann Arbor"], ["Michigan", "Yipsilanti"] ], columns=["State", "RegionName"] )

The following cleaning is performed by the code:

a) For "State", it removes characters from "[" to the end.

b) For "RegionName", when applicable, it removes every character from " (" to the end.

Dataset: 'university_towns.txt'

Source of Dataset: https://en.wikipedia.org/wiki/List_of_college_towns#College_towns_in_the_United_States

analysis.ipynb: Jupiter notebook that imports the raw unstructured dataset, performs cleaning, and structuring of the data
