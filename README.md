# 15janvaris
Pārbaudes darbs/Madona

Uzmanīgi lasīt uzdevumus un pildīt! Nepieciešamie faili ir jāveido pašiem, kā arī saturs. IEVĒRO – mainīgo un failu nosaukumus jāizdomā Tev!
1.import os

file_path = 'example.txt'

with open(file_path, 'r') as file:
    print(file.read())
    
3.	import csv

file_path = 'example.txt'

with open(file_path, 'r') as txtfile:
    for line in txtfile:
        print(line.strip())
4.	def read_and_print_file(file_path):
    with open(file_path, 'r') as file:
        for line in file:
            print(line.strip())

if __name__ == "__main__":
    file_path = input("Enter the file path: ")
    file_extension = input("Enter the file extension (e.g., .txt, .csv): ")

    if file_extension.lower() == ".txt":
        read_and_print_file(file_path)
    elif file_extension.lower() == ".csv":
        pass
    else:
        print("Unsupported file extension. Only .txt and .csv are currently supported.")
5.	Izveidot Python programmu, kas ļauj lietotājam ievadīt savu vārdu terminālī. Ievadīto vārdu pēc tam ierakstīt teksta failā (piemēram, "lietotajs.txt"). Programmai jābūt spējīgai apstrādāt kļūdas, piemēram, faila nepieejamību vai rakstīšanas problēmas. Pēc ierakstīšanas izvadīt paziņojumu par veiksmīgu darbību vai kļūdu gadījumā attiecīgu kļūdas ziņojumu. (8 punkti)
