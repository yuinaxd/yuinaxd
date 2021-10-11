while True:
    not1=int(input("Birinci Sınav Notunu Giriniz: "))
    if(not1<0 or not1>100):
       print("Sınav Notunuz 0 ile 100 arasında olmalıdır. ")
    else:
           break
while True:
    not2=int(input("İkinci Sınav Notunu Giriniz: "))
    if(not2<0 or not2>100):
         print("Sınav Notunuz 0 ile 100 Arasında olmalıdır.")
    else:
        break
ortalama=(not1+not2)/2
print("\n")
print("*"*50)
print("Birinci sınav notunuz: ",not1)
print("İkinci sınav notunuz: ",not2)
print("Ortalamanız: ",ortalama)
print("\n")
print("*"*50)
