# 1337-Leet-Speak
#Just learned a very basic code for Leet speak and I wanted to add it as my first project here
# basic leet speak exercice 
phrase = input('Input phrase: ')
phrase = phrase.upper()

lookup = {
    'A': '4',
    'E': '3',
    'I': '1',
    'L': '1',
    'O': '0',
    'T': '7',
    'N': '11'
}
leet = ''
for char in phrase:
    leet += lookup.get(char, char)
print(leet)
