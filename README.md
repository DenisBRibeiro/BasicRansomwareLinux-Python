
# 🛡️ Projeto: Ransomware Básico em Python (Linux)

## Descrição

Este é um projeto didático que demonstra um ransomware básico desenvolvido em Python, utilizando as bibliotecas `os` e `pyaes`. O exemplo foi criado para ambientes Linux e inclui dois scripts principais: um para criptografar arquivos (`encrypter.py`) e outro para descriptografá-los (`decrypter.py`). 

Além disso, o repositório contém um arquivo de texto de exemplo (`teste.txt`), que é usado para demonstrar o funcionamento do projeto.

> ⚠️ **Aviso Legal**: Este projeto é **somente para aprendizado**. Usar este código para fins maliciosos ou prejudicar terceiros é ilegal. O autor não se responsabiliza por ações que violem a lei ou a ética.

## Funcionalidades

- **Criptografia de Arquivos:** O script `encrypter.py` criptografa o conteúdo de arquivos em uma pasta usando AES.
- **Descriptografia de Arquivos:** O script `decrypter.py` descriptografa os arquivos usando a mesma chave.
- **Demonstração Simples:** O arquivo `teste.txt` serve como exemplo para testar a funcionalidade dos scripts.

## Tecnologias Utilizadas

- **Python 3.x**
- **os:** Para navegação em diretórios e manipulação de arquivos.
- **pyaes:** Para implementação de criptografia AES.

## Como Funciona

### Criptografia
1. O script `encrypter.py` percorre os arquivos da pasta onde está sendo executado.
2. Ele criptografa o conteúdo do arquivo `teste.txt` usando AES e salva o arquivo criptografado no lugar do original.

### Descriptografia
1. O script `decrypter.py` utiliza a mesma chave para reverter o processo de criptografia.
2. Ele restaura o arquivo `teste.txt` ao seu estado original.

## Estrutura do Repositório

- `encrypter.py`: Script que criptografa os arquivos.
- `decrypter.py`: Script que descriptografa os arquivos.
- `teste.txt`: Arquivo de texto usado como exemplo para os testes.
  
