def sub_lists(l):
    lists = [[]]  
    for i in range(len(l) + 1):  
        for j in range(i):  
            lists.append(l[j: i])  
    return lists  
l2 = input("enter elements")  
l1 = l2.split()  
print(sub_lists(l1))

import matplotlib.pyplot as pt
num=len(l1)
nums=2**num
pt.plot(range(num+1),[2**i for i in range(num + 1)],marker='o',color='red')
pt.title("subset vs elements")
pt.xlabel("subset")
pt.grid(color='black')
pt.ylabel("elements")
pt.show()
