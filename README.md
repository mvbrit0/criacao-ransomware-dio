# 📘 Desafio DIO: Implementação de um Ransomware para criptografar arquivos
 ## 🚀  Tecnologias Utilizadas
- Python: `3.13.14`
- Biblioteca: *pyaes*
- Ambiente: `Kali Linux`
- Editor: `nano`
## 🔐 Criptografia e Descriptografia
### Arquivos do projeto
- **encrypter.py** ➡️ criptografa arquivos usando chave simétrica.  
- **decrypter.py** ➡️ descriptografa arquivos previamente criptografados
- **teste.txt** ➡️ mensagem usada para criptografar e descriptografar
## 🔄 Fluxo de Criptografia e Descriptografia
1. 📂 Criação arquivos teste.txt ➡️ encrpyter.py ➡️ decrypert.py

   ![Clique para ver a execução](images/criacao-kali-arquivos-teste-encrypter-decrypter.PNG)

2. 📂 Código encrypter.py ↔️ Código decrypter.py ↔️ Cria teste.txt

   ![Clique para ver a execução](images/kali-nano-codigo-encrypter-decrypter-py.PNG) ![Clique para ver a execução](images/kali-teste-txt.PNG) 

3. 🔐 Executar encrypter.py ↔️ Gera teste.txt.ransomwaretroll

   ![Clique para ver a execução](images/comando-kali-nano-encrypter-py.PNG)

4. 📂 Arquivos criptografados

   ![Clique para ver a execução](images/kali-nano-teste-encrypter-txt-ransomwaretroll.PNG) 

5. 🔓 Executar decrypter.py ↔️ Gera teste.txt

   ![Clique para ver a execução](images/comando-kali-nano-decrypter-py.PNG) 

6. 📂 Arquivos restaurados

   ![Clique para ver a execução](images/kali-nano-teste-txt-decrypter.PNG) 

⚠️ **Atenção**: O desafio é estritamente educacional e não deve ser utilizado para fins maliciosos.
