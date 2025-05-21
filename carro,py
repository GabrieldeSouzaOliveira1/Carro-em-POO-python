class Carro:
    def __init__(self, marca, modelo, ano, velocidade=0):
        self.marca = marca
        self.modelo = modelo
        self.ano = ano
        self.velocidade = int(velocidade)

    def acelerar(self):
        self.velocidade += 10
        print(f"O carro acelerou para {self.velocidade} km/h")

    def frear(self):
        if self.velocidade >= 10:
            self.velocidade -= 10
        elif 0 < self.velocidade < 10:
            self.velocidade = 0
        else:
            print("O carro já está parado!!")
            return
        print(f"O carro freiou e está na velocidade {self.velocidade} km/h")

    def exibir_informacoes(self):
        print(f"INFORMAÇÕES DO CARRO:\n"
              f"Marca: {self.marca}\n"
              f"Modelo: {self.modelo}\n"
              f"Ano: {self.ano}\n"
              f"Velocidade: {self.velocidade} km/h")

    def __str__(self):
        return f"{self.marca} {self.modelo} ({self.ano}) - Velocidade: {self.velocidade} km/h"


# Criando o carro
celta = Carro('Celta', '1.0', 1999, 2)

# Usando os métodos
celta.acelerar()
celta.acelerar()
celta.frear()
celta.frear()
celta.frear()
celta.exibir_informacoes()

# Usando o __str__ automaticamente
print(celta)
