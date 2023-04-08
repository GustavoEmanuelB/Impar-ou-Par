# Projeto: Verificar se o número é Ímpar ou Par

def verificar_par_impar(numero):

    if numero % 2 == 0:
        return "par"
    else:
        return "ímpar"

numero = int(input("Digite um número: "))
resultado = verificar_par_impar(numero)


print("O número", numero, "é", resultado)  
