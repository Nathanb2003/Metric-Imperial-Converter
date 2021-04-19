# Metric-Imperial-Converter
This is a metric and imperial converter which was marginally wrong which i fixed and made a lot better.


print("Welcome to the Conversion-Calculator") 
metric_length=["'km', 'm' , 'cm'"]
imperial_length=["'mi', 'ft', 'in'"]

def km_mi():
     print(leng1/1.6, "miles")
def m_ft():
     print(leng1*3.26, "feet")
def cm_in():
     print(leng1/2.54, "inches")

def mi_km():
     print(leng2*1.6, "kilometers")
def ft_m():
     print(leng2/3.26, "metres")
def in_cm():
     print(leng2*2.54, "centimetres")

metric_mass=["'t','kg', 'g'"]
imperial_mass=["'stone', 'lb', 'oz'"]

def t_st():
     print(mass1*157.47, "stone")
def kg_lb():
     print(mass1*2.2, "pounds")
def g_oz():
     print(mass1*0.035, "ounces")

def st_t():
     print(mass2*0.00635, "tones")
def lb_kg():
     print(mass2*0.4536, "kilograms")
def oz_g():
     print(mass2*28.35, "grams")

menu_type=["Length - 1, Weight - 2"]

print(menu_type)
measure=int(input("Please select what you would like to convert by typing a number: "))


if measure==1:
     print ("")
     print("Metric-Imperial - 1\n")
     print("Imperial-Metric - 2\n")
     choice=int(input("Choose a conversion by typing a number: "))
     if choice== 1:
         print("Please choose the measurement you want to use.\n")
         print(metric_length)
         distance =input("Type an option from the menu: ")
         if distance=="km":
             leng1=int(input("Please enter a number to convert: "))
             print=(km_mi())
         elif distance=="m":
             leng1=int(input("Please enter a number to convert: "))
             print=(m_ft())
         elif distance=="cm":
             leng1=int(input("Please enter a number to convert: "))
             print=(cm_in())
         else:
             print("Invalid Entry")
     if choice== 2:
         print("Please choose the measurement you want to use.\n")
         print(imperial_length)
         distance2 =input("Type an option from the menu: ")
         if distance2=="mi":
             leng2=int(input("Please enter a number to convert: "))
             print=(mi_km())
         elif distance2=="ft":
             leng2=int(input("Please enter a number to convert: "))
             print=(ft_m())
         elif distance2=="in":
             leng2=int(input("Please enter a number to convert: "))
             print=(in_cm())
         else:
             print("Invalid Entry")

if measure==2:
     print ("")
     print("Metric-Imperial - 1\n")
     print("Imperial-Metric - 2\n")
     choice2=int(input("Choose a conversion by typing a number: "))
     if choice2== 1:
         print("Please choose the measurement you want to use.\n")
         print(metric_mass)
         weight =input("Type an option from the menu: ")
         if weight=="t":
             mass1=int(input("Please enter a number to convert: "))
             print=(t_st())
         elif weight=="kg":
             mass1=int(input("Please enter a number to convert: "))
             print=(kg_lb())
         elif weight=="g":
             mass1=int(input("Please enter a number to convert: "))
             print=(g_oz())
         else:
             print("Invalid Entry")

     if choice2== 2:
         print("Please choose the measurement you want to use.\n")
         print(imperial_mass)
         weight2 =input("Type an option from the menu: ")
         if weight2=="stone":
             mass2=int(input("Please enter a number to convert: "))
             print=(st_t())
         elif weight2=="lb":
             mass2=int(input("Please enter a number to convert: "))
             print=(lb_kg())
         elif weight2=="oz":
             mass2=int(input("Please enter a number to convert: "))
             print=(oz_g())
         else:
             print("Invalid Entry")
