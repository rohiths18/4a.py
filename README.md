# 4a.py
Given a listofnumbers,write a Python program to countEven and Odd numbers in a List.   Input:list1 = [2,7,5,64,14]  Output:Even = 3,odd = 2 

list1 = [2, 7, 5, 64, 14]  - This is the input

only_odd = [num for num in list1 if num % 2 == 1]  - for sepearation of odd numbers

odd_count = len(only_odd) - for counting of odd numbers 

print("Even numbers in the list: ", len(list1) - odd_count)  - for counting even numbers

print("Odd numbers in the list: ", odd_count) - for displaying number of odd and even numbers
