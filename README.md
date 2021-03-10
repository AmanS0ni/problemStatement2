def fun(N,X,Y,T):

  a=[]
  
  b=[]
  
  c=[]
  
  for i in range(1,N):
  
    if i%X==0:
    
      a.append(i)
      
    if i%Y==0:
    
      b.append(i)
      
  for i in a:
  
    for j in b:
    
      if i+j==T:
      
        c.append((i,j))
        
  print(c)
