# 99-Bottles-Song
99 Bottles Song code 
#CODE Begins Here

for beer in range(99, 0, -1):
   if beer > 1:
      print(beer, "bottles of beer on the wall,", beer, " bottles of beer,\n" + "Take one down and pass it around,", beer -1, "bottles of beer on the wall")
     
   elif beer == 1:
      print ("1 bottle of beer on the wall" + "" + " 1 bottle of beer.")
      print ("Take one down pass it around," + "" + " no more bottles of beer.")
      print ("No more bottles of beer on the wall," + "" + " no more bottles of beer," + "" + " go to the store and buy some more" + "" + " 99 bottles of beer on the wall.")


