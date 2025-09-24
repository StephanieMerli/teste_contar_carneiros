# teste_contar_carneiros

relogio = "contar_carneiros"
carneiros = 0
while True:
    resposta = input("Você já adormeceu? (s/n): ").lower()
    if resposta == 's':
        break
    else:
        carneiros += 1
        print(f"Carneiros: {carneiros - 1}")

print(f"Contou {carneiros} carneiros. Boa noite.")
