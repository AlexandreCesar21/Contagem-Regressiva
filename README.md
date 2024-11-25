# ⏱️ Contagem Regressiva

Um programa simples em Python que realiza uma contagem regressiva baseada no número de segundos especificado pelo usuário. O código utiliza a função `sleep` da biblioteca `time` para adicionar um intervalo de 1 segundo entre cada número.

---

## 💡 Sobre o Projeto

O script permite que o usuário defina o tempo (em segundos) de duração de uma contagem regressiva. À medida que os números são exibidos, há uma pausa de 1 segundo entre cada contagem, criando o efeito de uma contagem real.

---

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para desenvolver o programa.
- **Biblioteca `time`**: Utilizada para criar pausas entre as contagens com a função `sleep`.

---

## 🚀 Como Executar o Código

1. Certifique-se de que você tem o **Python** instalado no seu computador.
2. Copie o código para um arquivo chamado `contagem_regressiva.py`:
   ```python
   from time import sleep
   print(" CONTAGEM REGRESSIVA ")
   numero = int(input("Digite quantos segundos quer durar: "))
   for a in range(1, numero+1):
       print(a)
       sleep(1)
   print('FIM!')

<h1>📝 Como Funciona</h1>
<h2>1. Entrada do Usuário:</h2>

<p>• O programa solicita que o usuário informe a quantidade de segundos para a contagem regressiva.</p>

<h2>2. Laço de Repetição:</h2>

<p>• Utiliza um loop for para percorrer os números de 1 até o valor especificado.</p>

<h2>3. Intervalo de 1 Segundo:</h2>

<p>• A função sleep(1) pausa o programa por 1 segundo a cada iteração, criando o efeito de contagem regressiva.</p>

<h2>4. Finalização:</h2>
<p>• Após completar a contagem, o programa exibe a mensagem FIM!.</p>

<h1>📚 Aprendizados e Recursos</h1>
<p>Este projeto é ideal para quem está aprendendo:</p>

<p>• Laços de repetição (for).</p>
<p>• Uso de funções de tempo com time.sleep.</p>
<p>• Manipulação de entrada do usuário com input.</p>
