
# 📝 Contador de Palavras em Java

Este é um projeto simples em Java que permite contar quantas palavras existem em uma frase digitada pelo usuário. O programa é interativo e permite repetir o processo quantas vezes o usuário quiser.

---

## 📌 Funcionalidades

- Contagem automática de palavras em uma frase
- Permite múltiplas interações com o usuário
- Interface simples via terminal
- Código limpo, comentado e didático

---

## 💻 Pré-requisitos

- [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html) 8 ou superior
- Terminal ou uma IDE de sua preferência

---

## 🚀 Como executar

Clone o repositório e execute o arquivo `ContadorDePalavras.java`:

```bash
git clone https://github.com/DevRafaSantos/contadorDePalavras.git
cd contadorDePalavras/src/secao10
javac ContadorDePalavras.java
java ContadorDePalavras
```

---

## 🎮 Exemplo de uso

```
Digite uma frase:
Hoje o céu está limpo
A frase contém 5 palavras.
Deseja continuar? (s/n)
s
Digite uma frase:
Aprender Java é divertido!
A frase contém 4 palavras.
Deseja continuar? (s/n)
n
Sistema encerrado!
```

---

## 🔍 Como funciona o código

📌 Etapas:
1. Solicita uma frase do usuário  
2. Conta o número de palavras com base nos espaços  
3. Exibe o resultado  
4. Pergunta se o usuário deseja repetir o processo  
5. Encerra o programa caso o usuário não deseje continuar

🧠 Lógica de contagem:
- A frase é dividida usando `.split("\\s+")` que ignora múltiplos espaços consecutivos
- O tamanho do array resultante é o número de palavras

---

## 🤝 Contribuições

Sinta-se à vontade para contribuir com sugestões, melhorias ou correções. Forks e pull requests são muito bem-vindos!

---

## 📄 Licença

Este projeto está sob a licença de Rafael Santos.
