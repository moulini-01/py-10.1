# py-10.1
reverse hill printing using python
n=5
for i in range(n):
    for j in range(n-i):
	 	  print("  ", end="")
    for k in range(2*i+1):
  	 	  print("*",end=" ")
    print( " ")
