
print("=== Tala Mock Kenya ===")
name = input("Enter your name: ")
loan = int(input(f"Hey {name}, how much loan you want (KES): "))

interest = loan * 0.075
total = loan + interest

print(f"\nOkay {name}, you asked for KES {loan}")
print(f"Interest (7.5%): KES {interest}")
print(f"Total to pay: KES {total}")
print(f"Pay in 30 days. Sawa?")
