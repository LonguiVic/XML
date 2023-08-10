# Processamento de Notas Fiscais em Python

Este é um script em Python que processa arquivos XML de notas fiscais, extrai informações relevantes e cria um arquivo Excel com os dados extraídos.

## Descrição

O script lê arquivos XML de notas fiscais localizados na pasta 'nfs', extrai informações como número da nota, empresa emissora, nome do cliente, endereço e peso (quando disponível) e armazena esses dados em um arquivo Excel chamado 'NotasFiscais.xlsx'.

## Pré-requisitos

Certifique-se de ter o Python instalado em seu sistema. Além disso, instale as bibliotecas necessárias executando o seguinte comando:

    pip install xmltodict pandas

## Como usar

1. Coloque os arquivos XML de notas fiscais na pasta 'nfs'.
2. Execute o script usando o seguinte comando:

    python nome_do_script.py

3. O script processará os arquivos XML, extrairá as informações e criará o arquivo 'NotasFiscais.xlsx'.

## Notas

- Certifique-se de que as bibliotecas 'xmltodict' e 'pandas' estão instaladas (veja os pré-requisitos acima).
- O script assume que os arquivos XML de notas fiscais estão na pasta 'nfs' no mesmo diretório que o script.
- Caso haja alguma variação na estrutura dos arquivos XML, pode ser necessário ajustar o código para lidar com essas variações.

## Autor
 - Desenvolvido por Hashtag Programação (https://www.youtube.com/watch?v=KmrNYmv6GHU)
 - Código usado para fins de aprendizado
