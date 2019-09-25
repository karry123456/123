# 123
256
 1 #!/usr/bin/python 
 2 #-*- coding:utf-8 -*- 
 3 #there is no ++ operator in Python 
 4 import string 
 5 def main(): 
 6     s = raw_input('input a string:') 
 7     letter = 0 
 8     space = 0 
 9     digit = 0
 10     other = 0
 11     for c in s:
 12         if c.isalpha():
 13             letter+=1
 14         elif c.isspace(): 
 15             space+=1
 16         elif c.isdigit(): 
 17             digit+=1
 18         else:
 19             other+=1
 20     print 'There are %d letters,%d spaces,%d digits and %d other characters in your string.'%(letter,space,digit,other)
 21 
 22 if __name__ == '__main__':
 23     main()
