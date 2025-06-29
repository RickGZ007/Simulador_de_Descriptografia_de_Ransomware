# 🛡️ Simulador de Descriptografia de Ransomware

Este projeto simula a **descriptografia de arquivos afetados por ransomware**, utilizando o algoritmo **AES (modo CTR)** com a biblioteca `pyaes`. O objetivo é **educacional**, com foco em aprendizado sobre criptografia, segurança de dados e recuperação de arquivos em ambientes controlados.

## 📌 Objetivo

Demonstrar, de forma prática, como um arquivo criptografado por um ransomware pode ser revertido para sua forma original, desde que a chave e o algoritmo corretos sejam conhecidos.

---

## ⚙️ Como funciona

O script realiza as seguintes etapas:

1. Abre e lê um arquivo criptografado (`.ransomwaretroll`);
2. Usa uma chave fixa para descriptografar o conteúdo com `AESModeOfOperationCTR`;
3. Remove o arquivo criptografado;
4. Cria um novo arquivo restaurado com o conteúdo original.

---

## 🧪 Exemplo de uso

Nome do arquivo criptografado: `teste.txt.ransomwaretroll`  
Chave usada para descriptografia: `testeransomwares`  

Ao executar o script, será gerado um novo arquivo chamado `teste.txt` com o conteúdo restaurado.

---

## 📂 Requisitos

- Python 3.x
- Biblioteca `pyaes`

Instale com:
```bash
pip install pyaes
