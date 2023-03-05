# Cesar-encryptor-in-python-
python code from a simple python encryptor I'm a beginner so there may be a lot of errors.


def criptografar_cesar(texto, deslocamento):
    alfabeto = string.ascii_uppercase + string.ascii_lowercase
    deslocado = alfabeto[deslocamento:] + alfabeto[:deslocamento]
    tabela = str.maketrans(alfabeto, deslocado)
    return texto.translate(tabela)

frase = input("Qual frase você quer criptografar? ")
deslocamento = int(input("Qual o deslocamento? "))
print("Frase criptografada:", criptografar_cesar(frase, deslocamento))

the questions that will be asked by the terminal are in Portuguese but can be easily changed.
