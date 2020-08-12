<!-- version of elastic search and dependent python modeule should be same as requirements. Updated version of elasticsearch module have depreciated few of the keyword and replaced with new ones.  Like in DOctype is replaced by Document. 

http://localhost:8000/cars/?search=description|is - search and display cars, which contain the word ‘is’ in the description.
http://localhost:8000/cars/?id__gte=7 - filter and get only the cars which have ‘id’ greater or equal than 7.
http://localhost:8000/cars/suggest/?name_suggest__completion=cor - get suggestions for the word ‘cor’.

Few more fetaures are added and version/commit will add new features. 


Refrence taken from :  https://sunscrapers.com -->
