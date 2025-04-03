def calculate_discount(price, discount_percent):
    if discount >= 20:
        new_price = in_price - discount_percent
        print(f"The discounted price is Ksh {new_price}")
    else:
        new_price = price
        print(f"The price is Ksh {new_price}")


in_price = int(input("What is the price of the item? "))
discount = int(input("What is the percentage discount? "))
calculate_discount(price=in_price, discount_percent=discount)
