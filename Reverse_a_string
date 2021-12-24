from string import punctuation
special_character = set(punctuation)
name=input("Enter the input String: ")
lists = []
for letter in name.split(' '):
    letters = [i for i in letter if i not in special_character]
    for i in letter:
        if i not in special_character:
            lists.append(letters.pop())
            continue
        else:
            lists.append(i)
    lists.append(' ')
print("".join(lists))
