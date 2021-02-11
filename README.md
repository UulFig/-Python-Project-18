# -Python-Project-18
#18 Sum till a number (input)

while True:
    user_num = input("Please put an number:")
    if not user_num.isdigit():
        print("You should use numbers.\n")
    else:
        break

total = 0
for number in range(1, int(user_num)):
    total += number
print(total)
