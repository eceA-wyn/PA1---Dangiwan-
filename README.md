# PA1---Dangiwan-

#ALPHABET PROBLEM
z = input("Enter a string: ")
alphabet = list(z)
alphabet.sort()
print(alphabet)

#EMOTICON PROBLEM
def replacement(text):
    emoticons = {"smile":":)", "grin": ":D", "sad": ":((", "mad": ">:("}
    for y in emoticons:
        text = text.replace(y, emoticons[y])
    return text
x = input("How are you feeling today?: ")
print(replacement(x))

#UNPACKING LIST PROBLEM
writeyourcodehere = [1,2,3,4,5,6]

first = writeyourcodehere[0]
middle = writeyourcodehere[1:5]
last = writeyourcodehere[5]

print("First = [", first, "]")
print("Middle =", middle,)
print("Last = [",last,"]")
