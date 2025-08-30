# ALPHABET SOUP PROBLEM
``` python
z = input("Enter a string: ")
#asking input from the user and storing in z
alphabet = list(z)
#list alphabet was made containing the data in z
alphabet.sort()
#sort function was called to arrange the letters in the string in alphabetical order
print(alphabet)
#output was printed
```

# EMOTICON PROBLEM
``` python
def replacement(text):
#function named replacement was created
    emoticons = {"smile":":)", "grin": ":D", "sad": ":((", "mad": ">:("}
    #dictionary named emoticons was created
    #the appropriate value (emoticons) for each element (words) were assigned
    for y in emoticons:
        text = text.replace(y, emoticons[y])
   #the for loop will go through the entered string, find the key words and replace them with appropriate emoticons
    return text
    #the new string will be returned
x = input("How are you feeling today?: ")
#the user was asked for string input
print(replacement(x))
#the function was called and printed
```

# UNPACKING LIST PROBLEM
``` python
writeyourcodehere = [1,2,3,4,5,6]
#list named writeyourcodehere was created

first = writeyourcodehere[0]
#the index of the first element [0] was assigned to "first"
middle = writeyourcodehere[1:5]
#using slice, get the index of the second element (where the slice should start) and the index of the last element (where it should stop) was stored in "middle"
last = writeyourcodehere[5]
#the index of the last element in the list [5] was assigned to "last"

print("First = [", first, "]")
print("Middle =", middle,)
print("Last = [",last,"]")
#print the outputs
```
