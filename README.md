# Automorphic-Number
Printing Automorhic Number using pyhton
def automorphic(n):
    if ((n**2)%10 == n):
        return "AutoMorphic Number"
    else:
        return "Not Automorphic number"
n=int(input())
print(automorphic(n))
