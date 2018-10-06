# my-first
def minion_game(string):

    vowels =['A','E','I','O','U']
    
    s=0
    
    k=0
    
    for i in range(len(string)):
    
        if string[i] in vowels:
        
            k= k+len(string)-i
            
        else:
        
            s=s+len(string)-i
            
    if s>k:
    
        print "Stuart", s
        
    elif k>s:
    
        print "Kevin", k
        
    else:
    
        print("Draw")
       
