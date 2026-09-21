num_students = int(input("how many student?: "))

def status(avg):
    if avg >= 90:
        return "Excellent"
    elif avg >= 80:
        return "Very Good"
    elif avg >= 75:
        return "Passed"
    else:
        return "Failed"

for i in range(1, num_students + 1):
    print("Student")

    name = input("Enter name: ")

    activity1 = float(input("Activity 1: "))
    activity2 = float(input("Activity 2: "))
    activity3 = float(input("Activity 3: "))

    total = activity1 + activity2 + activity3
    average = total / 3

    print("_____student result____")
    print("Name:", name)
    print("Activity 1:", activity1)
    print("Activity 2:", activity2)
    print("Activity 3:", activity3)
    print("Average:", round(average, 2))
    print("Status:", status (average))

print("All 3 students have been processed")