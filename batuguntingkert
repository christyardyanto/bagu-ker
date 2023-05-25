import random   #fungsi random agar option terpilih acak

while True:
    #membuat list pilihan
    option = ["Batu", "Kertas", "Gunting"]
    #var computer acak
    computer = random.choice(option)

    player = input("Batu, Kertas, Gunting?")
    if player == computer:
        print("Imbang")
    elif player == "Batu":
        if computer == "Kertas":
            print("Kalah!", computer, "membungkus", player)
        else:
            print("Menang!", player, "menghancurkan", computer)
    elif player == "Kertas":
        if computer == "Gunting":
            print("Kalah!", computer, "memotong", player)
        else:
            print("Menang!", player, "membungkus", computer)
    elif player == "Gunting":
        if computer == "Batu":
            print("Kalah!", computer, "menghancurkan", player)
        else:
            print("Menang!", player, "memotong", computer)
    else:
        print("Error, silahkan cek inputan!")
    
    main_lagi = input("Apakah ingin bermain lagi?(Y?N)")
    if main_lagi == "N" or main_lagi == "n":
        break
