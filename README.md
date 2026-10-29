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
1. `encrypter.py`: Script responsável por localizar um arquivo alvo (ex: `teste.txt`), ler seu conteúdo, aplicar a criptografia usando uma chave predefinida, salvar o novo arquivo criptografado (ex: `teste.txt.ransomwaretroll`) e remover o arquivo original.
2. `decrypter.py`: Script responsável por localizar o arquivo criptografado, ler seu conteúdo, aplicar a chave de descriptografia para reverter o processo, salvar o arquivo original e remover a versão criptografada.

## Mitigação e Defesa
Para proteger sistemas contra ataques reais de ransomware, as seguintes práticas são essenciais:
- **Rotina de Backups (Regra 3-2-1):** Manter três cópias dos dados, em duas mídias diferentes, com uma cópia off-site ou offline.
- **Atualização de Sistemas (Patching):** Manter o sistema operacional e os softwares atualizados para corrigir vulnerabilidades conhecidas (como no caso do WannaCry).
- **Proteção de Endpoint (EDR/Antivírus):** Utilizar soluções de segurança que identifiquem comportamentos anômalos, como a criptografia em massa de arquivos.
- **Princípio do Menor Privilégio:** Limitar o acesso de usuários e processos apenas ao necessário, dificultando a propagação do malware na rede.
