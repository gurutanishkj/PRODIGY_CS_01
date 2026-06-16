def ce(x, y):
    r = ""

    for c in x:
        if c.isalpha():
            a = 65 if c.isupper() else 97
            r += chr((ord(c) - a + y) % 26 + a)

        else:
            r += c

    return r

def cd(x, y):
    return ce(x, -y)

m = input("Enter message: ")
y = int(input("Enter shift value: "))

e = ce(m, y)
print("Encrypted Text:", e)

d = cd(e, y)
print("Decrypted Text:", d)
