# Define your functions
#Coffee bot defined
def coffee_bot():
  print("Welcome to the cafe!")
  size = get_size()
  drink_type = get_drink_type()
  print("Alright, that's a", size, drink_type,"!")
  name = input("Can I get your name please? \n>")
  print("Thanks,", name,"! You drink will be ready shortly.")

#Get size defined prompt  
def get_size():
  res = input("What size drink can I get for you? \n[a] Small \n[b] Medium \n[c] Large \n> ")
  if res == "a":
    return "Small"
  elif res == "b":
    return "Medium"
  elif res == "c":
    return "Large"  
  else:
    print_message()
    return get_size()  
#Message to be printed defined
def print_message():
  print("I'm sorry, I did not understand your selection. Please enter the corresponding letter for your response.")
#Type of drink wanted prompt
def get_drink_type():
  kop = input("What type of drink would you like? \n[a] Brewed Coffee \n[b] Mocha \n[c] Latte \n>")  
  if kop == "a":
    return "Brewed Coffee"
  elif kop == "b":
    return "Mocha"
  elif kop == "c":
    return order_latte()  
  else:
    print_message()
    return get_drink_type()
 #Type of milk
def order_latte():

  res = input("What kind of milk for your latter? \n[a] 2% milk \n[b] Non-fat milk \n[c] Soy milk \n>")
  if res == "a":
    return "Latte"
  elif res == "b":
    return "Non-fat Latte"
  elif res == "c":
    return "Soy Latte"  
  else:
    print_message()
    return order_latte()  
# Call coffee_bot()!
coffee_bot()
