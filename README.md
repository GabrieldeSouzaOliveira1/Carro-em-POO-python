#  Classe Carro em Python — Exercício de POO

Este repositório contém um exercício simples de **Programação Orientada a Objetos (POO)** em Python. O objetivo é criar uma classe `Carro` com atributos e comportamentos básicos, como acelerar, frear e exibir informações.

---

## 📚 Conceitos praticados

- Criação de classes e objetos
- Uso do método `__init__`
- Métodos de instância
- Condicionais (`if/elif/else`)
- Encapsulamento de comportamento
- Método especial `__str__`

---

## 🧱 Estrutura da Classe

### Atributos:
- `marca` → Marca do carro (ex: Celta)
- `modelo` → Modelo ou versão (ex: 1.0)
- `ano` → Ano de fabricação
- `velocidade` → Velocidade atual do carro (começa em 0 por padrão)

### Métodos:
- `acelerar()` → Aumenta a velocidade em 10 km/h
- `frear()` → Diminui a velocidade em 10 km/h ou zera se estiver abaixo de 10
- `exibir_informacoes()` → Exibe todos os dados do carro formatados
- `__str__()` → Permite imprimir o carro com `print(objeto)` de forma amigável

---

## Exemplo de uso
python
Copiar
Editar
celta = Carro('Celta', '1.0', 1999, 2)
celta.acelerar()
celta.frear()
celta.exibir_informacoes()
print(celta)

## Autor
Feito por *Gabriel de Souza Oliveira*
