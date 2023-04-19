# PLAGiARISM-CHEKER

from difflib import SequenceMatcher

string1 = 'I am man'
string2 = 'I am manss'


match = SequenceMatcher(None,
						string1, string2)


result = match.ratio() * 100


print(int(result), "%")
