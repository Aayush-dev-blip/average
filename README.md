#Write a program to check alphabet “A” is present in the given string or not. And terminate the loop after finding the alphabet “A.”

a = input("enter a word:")    

for i in a:
  if (i == 'A'):
    print("A is found")
    break
else:
    print("A is not found")
        

