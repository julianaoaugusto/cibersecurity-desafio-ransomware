# Projeto Ransomware

### Ferramentas

- Kali Linux
- Python
- Nano

### Passo a passo

- Criar pasta do projeto: ``` mkdir projeto-ransomware ```
  - Abrir pasta do projeto: ``` cd projeto_ransomware ```
  - Criar arquivos: ``` touch teste.txt```, ```touch encrypter.py```, ```touch decrypter.py```
  - Listar arquivos da pasta: ```ls```

![Alt text](./01.png)

- Abrir o arquivo teste.txt: ``` nano teste.txt ```

![Alt text](./02.png)

  - Digitar mensagem no arquivo, salvar ( ```Ctrl + O```) e fechar o nano (```Ctrl + X```)

![Alt text](./03.png)

- Abrir o encrypter: ``` nano encrypter.py ```
 
![Alt text](./04.png)

  - Digitar o código para criptografar o arquivo teste.txt, salvar ( ```Ctrl + O```) e fechar o nano (```Ctrl + X```)
   
![Alt text](./05.png)

- Rodar o encrypter: ``` python encrypter.py`
  - Listar arquivos da pasta: ``` ls ```

![Alt text](./06.png)

  - Abrir o arquivo criptografado: ``` nano teste.txt.projetoransomware ```

![Alt text](./07.png)

![Alt text](./08.png)

- Abrir o decrypter: ``` nano decrypter.py ```
 
![Alt text](./09.png)

  - Digitar o código para descriptografar o arquivo teste.txt.projetoransomware, salvar ( ```Ctrl + O```) e fechar o nano (```Ctrl + X```)
   
![Alt text](./10.png)

- Rodar o decrypter: ``` python decrypter.py```
  - Listar arquivos da pasta: ``` ls ```

![Alt text](./11.png)

  - Abrir o arquivo descriptografado: ``` nano teste.txt ```

![Alt text](./12.png)

![Alt text](./13.png)

### Resultados

- Arquivo criptografado

![Alt text](./08.png)

- Arquivo descriptografado

![Alt text](./13.png)
