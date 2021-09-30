Score1 = int(input("Enter your score!"))
print("you entered:", Score1)

Score2 = int(input("Enter Another score!"))
print("you entered:", Score2)

Score3 = int(input("Enter last score!"))
print("you entered:", Score3)

scores = []
scores.extend([Score1, Score2, Score3])
list.sort(scores)

for x in scores:
    print(x)
