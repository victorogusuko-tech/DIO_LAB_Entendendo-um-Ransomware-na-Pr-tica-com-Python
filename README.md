# Desafio: Implementando um Ransomware em Python

## Descrição do Projeto
Este projeto é resultado do desafio prático da plataforma DIO (Digital Innovation One). O objetivo educacional é compreender a mecânica por trás de um ataque de Ransomware, implementando scripts em Python para criptografar e descriptografar arquivos locais.

**Aviso Legal:** Este projeto tem fins estritamente educacionais. O código foi desenvolvido e testado em ambiente de laboratório isolado. O uso indevido dessas informações e scripts é de inteira responsabilidade do usuário.

## Ferramentas e Bibliotecas Utilizadas
- **Linguagem:** Python 3
- **Biblioteca de Criptografia:** `pyaes` (ou a biblioteca utilizada no seu código)
- **Conceitos Abordados:** Manipulação de arquivos no sistema operacional, Criptografia Simétrica (AES), Malwares.

## Estrutura do Projeto
O repositório contém dois scripts principais:
1. `encrypter.py`: Script responsável por localizar um arquivo alvo (ex: `teste.txt`), ler seu conteúdo, aplicar a criptografia usando uma chave predefinida, salvar o novo arquivo criptografado (ex: `teste.txt.ransomwareLAB`) e remover o arquivo original.
2. `decrypter.py`: Script responsável por localizar o arquivo criptografado, ler seu conteúdo, aplicar a chave de descriptografia para reverter o processo, salvar o arquivo original e remover a versão criptografada.
