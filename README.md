 Implementação do algoritmo de ordenação Bubble Sort:

def bubble_sort(arr):
    n = len(arr)
    # Percorre todos os elementos do array
    for i in range(n):
        # Últimos i elementos já estão ordenados
        for j in range(0, n-i-1):
            # Troca se o elemento encontrado for maior que o próximo
            if arr[j] > arr[j+1]:
                arr[j], arr[j+1] = arr[j+1], arr[j]
    return arr

# Exemplo de uso:
arr = [64, 34, 25, 12, 22, 11, 90]
sorted_arr = bubble_sort(arr)
print("Array ordenado:", sorted_arr)

2. Algoritmo para imprimir apenas as vogais de uma frase:
3. def imprime_vogais(frase):
    vogais = "aeiouAEIOU"
    resultado = ""
    for char in frase:
        if char in vogais:
            resultado += char
    return resultado

# Exemplo de uso:
frase = "Exemplo de frase com vogais."
vogais = imprime_vogais(frase)
print("Vogais encontradas:", vogais)

sses códigos fazem o seguinte:

O Bubble Sort ordena uma lista de números.
A função de impressão de vogais extrai e exibe apenas as vogais de uma frase fornecida.
