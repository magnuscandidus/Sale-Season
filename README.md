# Sale-Season
# cook your dish here
disc = int(input())
for d in range(disc):
  P = int(input())
  if P<=100:print(P-0)
  elif 100<P<=1000:print(P-25)
  elif 1000<P<=5000: print(P-100)
  else: print(P-500)
