# meduda 

Sigo me aprofundando nos estudos de Python, hoje tive o conhecimento do módulo `random´, para realizar comportamentos aleatórios no código. A função `cara_ou_coroa´,  foi usada para simular um sorteio entre 'cara' e 'coroa'

```python
import random

def cara_ou_coroa():
    return random.choice(['cara','coroa'])

while True:
    jogo = input('Escolha: "cara" ou "coroa"').lower()

    if jogo not in ['cara','coroa']:
       print ('Por favor, digite "cara" ou"coroa"')
       continue #volta para a escolha, caso o usuario não digite cara ou coroa

    resultado = cara_ou_coroa()
    print(f'Deu: {resultado}')

    if jogo == resultado:
       print('Você acertou!')
    else:
       print('Você errou!')

    print() #separa as rodadas.
```







