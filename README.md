# LoopsHW.py
input_list = ["Hello",8.8,6,"Goodbye"]

int_list = []

for e in input_list:
  print (e)
  if e >= 0:
      int_list.append(e)
      print int_list
  if e is (""):
      int_list.remove(e)
