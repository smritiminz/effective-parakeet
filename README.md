# effective-parakeet
names = []
phone_numbers = []
num = 3

for i in range(num):
    name = input("Name: ")
    phone_number = input("Phone Number: ")
    
    names.append(name)
    phone_numbers.append(phone_number)

print("\nName\t\t\tPhone Number\n")

for i in range(num):
    print("{}\t\t\t{}".format(name[i], phone_number[i]))

search_term = input("\nEnter Search Terms: ")
print("Search Result")
if search_term in names:
    index = names.index(search_terms)
    phone_number = phone_number[index]
    print("Name{}, Phone Number:{}".format(search_term, phone_number))
else:
    print("Name not found")
