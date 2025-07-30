# pattern3
PYRAMID WITH "*"
rows=int(input("enter rows: "))
pattern=[(" "*(rows-i)+ '*' *(2*i-1))for i in range(1,rows+1)]
for p in pattern:
    print(p)
