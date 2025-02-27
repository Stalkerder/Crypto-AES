﻿# Crypto-AES

Este é um código de exemplo de como criptografar e descriptografar texto usando a biblioteca AES do OpenSSL.

Requisitos:

Instalação do OpenSSL (https://slproweb.com/products/Win32OpenSSL.html)
Visual Studio (https://code.visualstudio.com/download)

Instalação:

1. Baixe e instale a última versão do OpenSSL para Windows seguindo as instruções fornecidas no instalador.
2. Adicione as variáveis de ambiente Caminho, LIB e INCLUDE para o OpenSSL.
3. Adicione o caminho do OpenSSL aos Diretórios de Inclusão e Diretórios de Biblioteca no Visual Studio.
4. Adicione as bibliotecas libeay32.lib e ssleay32.lib ao seu projeto.

Uso:

- As funções encryptAES e decryptAES podem ser usadas para criptografar e descriptografar texto respectivamente.
- A função encryptAES recebe como parâmetros o texto a ser criptografado e a chave de criptografia.
- A função decryptAES recebe como parâmetros o texto criptografado e a chave de criptografia utilizada para criptografar o texto.
- Certifique-se de usar a mesma chave para criptografar e descriptografar o texto.
- Use essas funções com cuidado, pois o uso de chaves fracas ou textos não seguros podem comprometer a segurança da sua aplicação.
- Espero que isso ajude. Se você tiver alguma dúvida adicional, não hesite em perguntar.
