# My-Project : Rock-Paper-Scissors Game
kullanici=input("Oyuna hoş geldiniz. Taş için 't', kağıt için 'k', makas için 'm' harfine basınız. Çıkmak için 'c' tuşuna basınız.")
bilgisayar=random.choice(["t","k","m"])
if kullanici==bilgisayar:
    print ("Bilgisayarın da seçimi aynıydı. Berabere!")
elif kullanici=="t":
    if bilgisayar=="k":
        print("Bilgisayarın seçimi: Kağıt idi. \n YENİLDİNİZ!")
    elif bilgisayar=="m":
        print("Bilgisayarın seçimi: Makas idi. \n KAZANDINIZ!")
elif kullanici=="k":
    if bilgisayar=="m":
        print("Bilgisayarın seçimi: Makas idi. \n YENİLDİNİZ!")
    elif bilgisayar=="t":
        print("Bilgisayarın seçimi: Taş idi. \n KAZANDINIZ!")
elif kullanici=="m":
    if bilgisayar=="k":
        print("Bilgisayarın seçimi: Kağıt idi. \n KAZANDINIZ!")
    elif bilgisayar=="t":
        print("Bilgisayarın seçimi: Taş idi. \n YENİLDİNİZ!")
elif kullanici=="c":
    print("Çıkılıyor...")
