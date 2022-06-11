#  Desafio de projeto sobre Git/GitHub
**Repositório criado para o desafio de projeto**

Vou apresentar um código básico de uma uma calculadora  feita no Pycharm

```
class Calculadora:
    def __init__(self, num1, num2):
        self.valor_a = num1
        self.valor_b = num2
    def soma(self):
        return self.valor_a + self.valor_b
    def subtracao(self):
        return self.valor_a-self.valor_b
    def mutiplicacao(self):
        return self.valor_a*self.valor_b
    def divisao(self):
        return self.valor_a/self.valor_b

calculadora= Calculadora(10, 2)
print(calculadora.valor_a)
print(calculadora.soma())
print(calculadora.subtracao())
print(calculadora.mutiplicacao())
print(calculadora.divisao())
```
