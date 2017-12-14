# temp


#!/usr/bin/python


a = {"1":{"2":{"3":{"4":{"5":"result"}}}}}


b = ["5","4","3","2","1"]
b.reverse()
print b
print "=" * 100
print a

for k in b:
    if a.has_key(k):
        a = a[k]
        print a
        continue

print "=" * 100
print a
