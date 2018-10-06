# coding-taks-lists
N= int(raw_input()) 
mylist=[] 
for i in range(N):     
    x=raw_input().split()     
    if x[0]== "insert":        
        mylist.insert(int(x[1]),int(x[2]))     
    if x[0]=="remove":        
        mylist.remove(int(x[1]))     
    if x[0]=="append":        
        mylist.append(int(x[1]))    
    if x[0]=="print":         
        print mylist     
    if x[0]=="sort":         
        mylist.sort()     
    if x[0] =="pop":        
        mylist.pop()    
    if x[0]=="reverse":       
        mylist.reverse()     
