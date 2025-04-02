# The-thing-def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32

def fahrenheit_to_celsius(fahrenheit):
    return (fahrenheit - 32) * 5/9

def main():
    print("Temperature Converter")
    choice = input("Convert from (C)elsius or (F)ahrenheit? ").strip().lower()

    if choice == "c":
        celsius = float(input("Enter temperature in Celsius: "))
        print(f"{celsius}°C is {celsius_to_fahrenheit(celsius):.2f}°F")
    
    elif choice == "f":
        fahrenheit = float(input("Enter temperature in Fahrenheit: "))
        print(f"{fahrenheit}°F is {fahrenheit_to_celsius(fahrenheit):.2f}°C")
    
    else:
        print("Invalid choice. Please enter 'C' or 'F'.")

main(celsius_to_fahrenheit)

if choice == "p"
celsius_to_fahrenheit = float(input)"enter tempreture in celsiue")

elif choice == "C"
fahrenheit_to_celsius = flast(flaat(input) 

def main()
   Print("temperature converter"
   choice = input("cpnvert form (c)elsius or (f)ahrenhit").strip().lower()
