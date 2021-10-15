# Tracking-envestments
def invest():
    amount = float(input("Enter the amount: "))
    rate = float(input("Enter the rate: "))
    year = int(input("enter the year: "))
    num = 1
    for amounts in range(year):
        print(f"year {num} : ${amount + (amount * rate/100):.2f}")
        num += 1
        amount = amount + (amount * rate/100)
invest()
