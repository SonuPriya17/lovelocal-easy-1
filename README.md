# lovelocal-easy-1
Given a string s consisting of words and spaces, return the length of the last word in the string. A word is a maximal  substring consisting of non-space characters only.
<br>
Author-Sonupriya N C 
<br>
def length_of_last_word(s):
    # Split the string into words using spaces as separators
    words = s.split()
    # Check if there are any words in the string
    if not words:
        return 0
    # Return the length of the last word
    return len(words[-1])
s1 = "Hello World"
print(length_of_last_word(s1))  # Output: 5

s2 = "fly me to the moon"
print(length_of_last_word(s2))  # Output: 4
<br>
#explination
#1. Function Definition:
    #Defines a function named length_of_last_word that takes a string s as input.
  #  words = s.split()
#2. Splitting into Words:
   # s.split() separates the input string s into a list of words using spaces as separators.
    #For example, if s is "Hello World," then words becomes ["Hello", "World"].
   # if not words:
      #  return 0
#3. Checking for Words:
    #The if not words: checks if the list of words is empty. If it's empty, it means there are no words in the string.
   # If there are no words, the function returns 0 because there is no last word to measure.
   # return len(words[-1])
#4. Returning Length of Last Word:
#If there are words in the list, the function returns the length of the last word.
   # words[-1] accesses the last element in the list, which is the last word in the string.
   #len(words[-1]) then calculates the length of that last word.
# This function takes a string, splits it into words, checks if there are any words, and if there are, it returns the length of the last word. It's a simple way to find the length of the last word in a given string.

