# CPU, RAM e Ordem de Volatilidade

## 1. CPU

A CPU é o processador responsável por executar instruções.
Seu ciclo básico de instrução pode ser descrito como:
- Fetch: busca a instrução.
- Decode: interpreta a instrução.
- Execute: executa a instrução.

## 2. RAM

A RAM armazena temporariamente dados e instruções usados pelos programas.
Ela é volátil: os dados que existem somente nela normalmente são
perdidos quando o computador perde a alimentação elétrica.

## 3. Cache e registradores

- Cache: memória rápida que mantém dados e instruções que a CPU pode
  precisar em breve.
- Registradores: pequenas áreas de armazenamento dentro da CPU,
  utilizadas diretamente durante o processamento.

## 4. Armazenamento e paginação

- RAM: memória de trabalho volátil.
- SSD: dispositivo de armazenamento persistente.
- Swap: mecanismo de paginação comum em sistemas Linux.
- Pagefile: arquivo de paginação do Windows.

## 5. Ordem de volatilidade

É o princípio de priorizar a coleta de dados que podem desaparecer
mais rapidamente, considerando as condições da investigação.

A ordem exata depende do cenário e dos procedimentos adotados.

## 6. Importância para a perícia digital

Desligar um computador ligado sem avaliar o cenário pode causar a
perda de evidências voláteis. A coleta deve ser autorizada,
documentada e adequada à situação.

## 7. O que eu aprendi

A CPU executa instruções e a RAM guarda temporariamente os dados
utilizados pelos programas. Como os dados da RAM podem desaparecer
quando a alimentação é perdida, é importante considerar a volatilidade
ao planejar a preservação de evidências digitais.

## 8. Fontes

- RFC 3227: https://www.rfc-editor.org/rfc/rfc3227
- CS50: https://cs50.harvard.edu/x/
