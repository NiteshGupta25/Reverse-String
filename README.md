# Reverse-String
print(s[::-1])

# 2nd WAY -------------------------------->

s=input("Enter some String------>")
print(''.join(reversed(s)))

# 3rd WAY -------------------------------->

s = input("Enter some Reversed String------>")
i=len(s)-1
target= ''
while i>=0:
    target=target+s[i]
    i=i-1
    print(target)

Output:
       C:\Python\python.exe C:/Users/Superuser/PycharmProjects/pythonStringimpqus/reverseGivenString.py
       
Enter some  String----->Durga soft salution
noitulas tfos agruD

Enter some String------>Durgasoft
tfosagruD

Enter some Reversed String------>niteshgupta
a
at
atp
atpu
atpug
atpugh
atpughs
atpughse
atpughset
atpughseti
atpughsetin
