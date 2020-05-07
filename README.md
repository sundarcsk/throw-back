# throw-back
simple but yet complex python code!!!!!!!

def liv(lis):
 
    a=[(str(t[0])+" lives in " +str(t[2]) + " and "+ (" his "if t[3]=="M" else " her ") + " age is "+ str(t[1])) for t in lis if str(t[2])!="USA" ]
    print (a)
      
liv([('john',25,"USA","M"),("Seetha",30,"UK","F"),("preethi",35,"India","F")]) 
