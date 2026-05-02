import sys

def electrical_conversions():
    print("\n--- Electrical Engineering Converter ---")
    print("1. Horsepower (hp) to Watts (W)")
    print("2. Watts (W) to Horsepower (hp)")
    print("3. Resistance (Ohm's Law: R = V/I)")
    
    choice = input("Select conversion (1-3): ")
    
    if choice == '1':
        hp = float(input("Enter Horsepower: "))
        print(f"{hp} hp = {hp * 745.7:.2f} Watts")
    elif choice == '2':
        watts = float(input("Enter Watts: "))
        print(f"{watts} W = {watts / 745.7:.4f} hp")
    elif choice == '3':
        v = float(input("Enter Voltage (V): "))
        i = float(input("Enter Current (I): "))
        print(f"Resistance (R) = {v / i:.2f} Ω")

def physics_conversions():
    print("\n--- Physics & Mechanics ---")
    print("1. Celsius to Fahrenheit")
    print("2. Fahrenheit to Celsius")
    print("3. Kilograms to Pounds")
    
    choice = input("Select conversion (1-3): ")
    
    if choice == '1':
        c = float(input("Enter Celsius: "))
        print(f"{c}°C = {(c * 9/5) + 32:.2f}°F")
    elif choice == '2':
        f = float(input("Enter Fahrenheit: "))
        print(f"{f}°F = {(f - 32) * 5/9:.2f}°C")
    elif choice == '3':
        kg = float(input("Enter Kg: "))
        print(f"{kg} kg = {kg * 2.20462:.2f} lbs")

def main():
    while True:
        print("\n==============================")
        print("  THE ULTIMATE UNIT CONVERTER ")
        print("==============================")
        print("1. Physics & General")
        print("2. Electrical Engineering")
        print("3. Exit")
        
        main_choice = input("\nChoose a category (1-3): ")
        
        try:
            if main_choice == '1':
                physics_conversions()
            elif main_choice == '2':
                electrical_conversions()
            elif main_choice == '3':
                print("Exiting... Happy Engineering!")
                sys.exit()
            else:
                print("Invalid selection. Please try again.")
        except ValueError:
            print("Invalid input! Please enter numeric values.")
        except ZeroDivisionError:
            print("Error: Division by zero is not allowed.")

if __name__ == "__main__":
    main()