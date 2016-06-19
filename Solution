#Sample Inputs
input1 = "06ababab"
input2 = "12hello there world"
input3 = "70hello there world"

#Here the comments represent alternative ways to solve the same problem

#'isthere(c, arr)' is a bool function that tracks whether a character was already counted before or not
#'c' is the character that we are searching for in an list 'arr' which records all the characters that are already counted
#'isthere(c, arr)' returns 1 if the the character is found and returns 0 if the character is not found 

def isthere (c, arr):
        #j = 0
        #for j in range(0,(len(arr) -1)):
    for char in arr: #Taking each character 'char' of list 'arr' at a time
        if char == c: #Comparing if it is already already recorded
            #if arr[j] == c:
            return 1 #The character has been found
    return 0 #The character has not been found

def Calculate(inp):

    ##Calculating the Offsets
    i = 0
    j = 0
    charcount = []
    csum = {}
    first = int(inp[0:2])
    #print first
    second = inp[2:]
    cut = second [:first]
    #cut = inp[2:(first+1)]
    #print cut 
    #for i in range(0,(len (cut)- 1)):
    for c in cut:
        #c = cut[i]
        if ( c != " " and isthere (c, charcount) == 0 ):
        #if ( c != " " ):
            index = 0
            tsum = 0
            cut2 = cut [i:]
            #print cut2
            for char in cut2:
            #for char in cut [i:]:
                if char==c:
                    tsum += index
                index += 1
            charcount.append (c)
            csum[c] = tsum
            j += 1
        i += 1
    ## Printing the Offset
    i = 0
    print 'For string "%s": we take "%s" digits and we get "%s"' % (inp, first, cut)
    
    #for i in range (0, (len (charcount)-1)):
    for cr in charcount:
        print '%s = %s' % (cr, csum[cr])
        #print '%s = %s' % (charcount [i], csum[charcount [i]])
    #print charcount
    #print cut
   
##def main():

Calculate(input1)
Calculate(input2)
Calculate(input3)
