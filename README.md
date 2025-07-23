# meduda 
Desenvolver


```python
funções = input('Escolha uma das opções:\n-Soma\n-subtração\n-Divisão\n-Multiplicação: ' ).lower()
print(f'a calculadora irá produzir {funções}')

numero1 = float(input(' '))
numero2 = float(input(' '))

if funções == 'soma':
   resultado_soma = numero1 + numero2
   print(f'Resultado {resultado_soma}')

elif funções == 'subtração':
     resultado_sub = numero1 - numero2
     print(f'{resultado_sub}')

elif funções == 'divisão':
     if numero2 == 0:
      print(' 0 ')
     else:
         resultado = numero1 / numero2
         print(f'{resultado}')

elif funções == 'multiplicação':
    resultado_multi = numero1 * numero2
    print(f'{resultado_multi}')

```







