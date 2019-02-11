line 45, changing let to const breaks i the iterator, it cant change value which is what a for loop depends on, so must change away from const, let sounds good. 

totalCLicks is firt assigned to zero on line 15, then is being incremented on line 57 which isnt allowed with const. should be letted.

all products on line 9 is consted  to an array. but on line 130 is being reassinged with some JSON parsing which isnt allowed with const. should be letted. 



finally another two breaking for loops with using const on lines 64, 76, and 133, they should be should be letted.