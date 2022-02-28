# 28-02-2022-assignment-1
x=[1,2,3,2,1,3,2,1,2,3]
l1=[]
l2=[]
for i in x:
    if i%2==1:
        if i not in l1:
            l1.append(i)
            l2.append(x.count(i))
print(l1)
print(l2)


output:
======================== RESTART: C:/Python37/list.py ========================
[1, 3]
[3, 3]
>>> 
