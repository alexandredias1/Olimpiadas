# Olimpíadas - Lançamento de Atletas

Este é um script em Python que simula uma competição de lançamentos de atletas. O script permite ao usuário inserir os lançamentos dos atletas em três rodadas e exibe os melhores lançamentos de cada rodada.

## Descrição

O script solicita ao usuário para inserir as distâncias dos lançamentos de 10 atletas na primeira rodada, 6 atletas na segunda rodada e 4 atletas na rodada final. Após cada rodada, o script ordena e exibe os lançamentos em ordem decrescente, mostrando os melhores lançamentos de cada rodada.

## Funcionalidades

- Inserir distâncias dos lançamentos para 10 atletas na primeira rodada.
- Inserir distâncias dos lançamentos para 6 atletas na segunda rodada.
- Inserir distâncias dos lançamentos para 4 atletas na rodada final.
- Ordenar e exibir os lançamentos em ordem decrescente para cada rodada.

## Como usar

1. Certifique-se de ter o Python instalado em seu sistema.
2. Salve o script em um arquivo com a extensão `.py` (por exemplo, `olimpiadas.py`).
3. Abra um terminal ou prompt de comando.
4. Navegue até o diretório onde o script foi salvo.
5. Execute o script com o comando `python olimpiadas.py`.
6. Insira as distâncias dos lançamentos conforme solicitado pelo script.

## Exemplo de uso

```python
lista = []
lista2 = []
lista3 = []

for i in range(10):
    atletas = float(input(f"Lançamento do atleta {i + 1}: "))
    lista.append(atletas)

print(f"Ordem de lançamento dos atletas: {lista}")
lista.sort()
lista.reverse()
print(f"Os melhores lançamentos da primeira rodada: {lista}")

for i in range(6):
    atletas = float(input(f"Lançamento do atleta {i + 1}: "))
    lista2.append(atletas)

print(f"Ordem de lançamento dos atletas: {lista2}")
lista2.sort()
lista2.reverse()
print(f"Os melhores lançamentos da segunda rodada: {lista2}")

for i in range(4):
    atletas = float(input(f"Lançamento do atleta {i + 1}: "))
    lista3.append(atletas)

print(f"Ordem de lançamento dos atletas: {lista3}")
lista3.sort()
lista3.reverse()
print(f"Os melhores lançamentos da rodada final: {lista3}")
