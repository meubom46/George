def calcular_imc(peso, altura):
    imc = peso / (altura ** 2)
    return imc

def interpretar_imc(imc):
    if imc < 18.5:
        return "Abaixo do peso"
    elif imc < 24.9:
        return "Peso normal"
    elif imc < 29.9:
        return "Sobrepeso"
    else:
        return "Obeso"

def main():
    print("Calculadora de IMC")
    print("------------------")

    # Entrada do usuário
    try:
        peso = float(input("Digite o seu peso em kg: ").replace(',', '.'))
        altura = float(input("Digite a sua altura em metros: ").replace(',', '.'))
    except ValueError:
        print("Erro: Certifique-se de usar um formato numérico válido.")
        return

    # Cálculo do IMC
    imc = calcular_imc(peso, altura)

    # Interpretação do IMC
    classificacao = interpretar_imc(imc)

    # Exibir resultado
    print("\nResultados")
    print(f"Seu IMC é: {imc:.2f}")
    print(f"Classificação: {classificacao}")

if __name__ == "__main__":
    main()
