n1=int(input())
a1=[]
k1=bin(2**n1-1)[2::]
l1=len(k1)
for i1 in range(0,2**n1):
	s1=bin(i1)[2::]
	if len(s1)<l1:
		a1.append([s1.count("1"),(l1-len(s1))*"0"+s1])
	else:
		a1.append([s1.count("1"),s1])
a1.sort()
for i1 in range(0,len(a1)):
	print(a1[i1][1])
