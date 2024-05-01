# 
a, b, c = input(), input(), input()
# 
length1, length2, length3 = len(a), len(b), len(c)
# 
if len(c) > len(b) > len(a):
    print(a, c, sep='\n')
# 
elif len(a) > len(b) > len(c):
    print(c, a, sep='\n')
# 
elif len(c) > len(a) > len(b):
    print(b, c, sep='\n')
# 
elif len(a) > len(c) > len(b):
    print(b, a, sep='\n')
# 
elif len(b) > len(c) > len(a):
    print(a, b, sep='\n')
# 
elif len(b) > len(a) > len(c):
    print(c, b, sep='\n')
