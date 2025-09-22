n = 21

while n > 0:
    p = int(input(f"Restam {n}. Introduza um número de 1 a 4: "))
    if not 1 <= p <= 4:
        print("Número inválido.")
        continue
    n -= p
    if n <= 0:
        print("Perdeste! Eu ganhei.")
        break
    
    # Jogada do computador
    comp = (n - 1) % 5
    if comp == 0:
        comp = 1
    print(f"O computador joga {comp}")
    n -= comp

    if n <= 0:
        print("Ganhaste! O computador perdeu.")
        break
