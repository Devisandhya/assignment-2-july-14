# assignment-2-july-14
n=int(input())
l=list(map(int,input().split()))
print(max(set(l),key=l.count))
