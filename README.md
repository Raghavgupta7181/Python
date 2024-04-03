# Python
Programming in Python
Write python program to print first letter of your name 
a) Example: Peter
               *      *
               *             *
               *              *
               *      *
               *
               *
               *
Answer a)first_letter = name[0].upper()
    if first_letter in initials:
        for line in initials[first_letter]:
            print(line)

# Test the function
name = input("Enter your name: ")
print("Printing the first letter of your name:")
print_initial(name
b) Print your name by using for loop

c) check the user name is palindrome or not
Answer b)
name = "raghavgupta"

for letter in name:
    print(letter)
    Answer c) 
    def is_palindrome(word):
    word = word.lower()
    reversed_word = word[::-1]
    if word == reversed_word:
        return True
    else:
        return False
username = input("Enter the username: ")
if is_palindrome(username):
    print("The username '{}' is a palindrome.".format(username))
else:
    print("The username '{}' is not a palindrome.".format(username))
