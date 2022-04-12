import csv;
a=[];
with open('/content/sample_data/data-2.csv') as csvfile:
  for x in csv.reader(csvfile):
    a.append(x)
# print(a)'
msh=['0'] * (len(a[0])-1)
a.remove(a[0])
for x in a:
  if x[len(x)-1]=='yes':
    for i in range(0,len(msh)):
      if msh[i]=='0' or x[i]==msh[i]:
        msh[i]=x[i]
      else:
        msh[i]='?'

print(msh)
