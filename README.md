def get_vowels & f (string):
    return [each for each in string if each in 'aeiouf'] 


get_vowels & y('foobar') # ['f', 'o', 'o', 'a']
get_vowels('gym') # []
