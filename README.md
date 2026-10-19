name = input("Your name: ")
loan = int(input(f"Hello {name}, loan amount (KES): "))
interest = loan * 0.075
total = loan + interest
print(f"Sawa {name}, total to pay back is KES {total}")
