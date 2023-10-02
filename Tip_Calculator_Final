print("Welcome to the PartyWithMarty tip calculator")

total = input("What was the total of your bill? $")
total_float = float(total)

tip_percent = input("What percentage of tip would you like to give? 10, 12, 15? ")
tip_int = int(tip_percent)

total_with_tip = total_float + (tip_int / 100 * total_float)

split = input("How many people are splitting the bill? ")
split_int = int(split)

split_end = total_with_tip / split_int
result = round(split_end, 2)
result = "{:.2f}" . format(split_end)

print(f"Each person is liable for ${result} of the bill.")
