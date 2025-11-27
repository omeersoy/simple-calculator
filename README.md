# simple-calculator
Python ile yazılmış dört işlemli basit bir hesap makinesi uygulaması.
# Basit Hesap Makinesi Uygulaması (calculator.py)

def topla(a, b):
    return a + b

def cikar(a, b):
    return a - b

def carp(a, b):
    return a * b

def bol(a, b):
    if b == 0:
        return "Sıfıra bölme hatası!"
    return a / b

print("Toplama sonucu:", topla(10, 5))
print("Çıkarma sonucu:", cikar(10, 5))
