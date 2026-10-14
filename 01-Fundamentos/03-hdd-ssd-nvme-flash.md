# Aula 002 — HDD, SSD, NVMe e Mídia Flash

## 1. HDD — Hard Disk Drive

O HDD armazena dados em pratos magnéticos que giram. As trilhas são caminhos circulares nas superfícies, e os setores são divisões utilizadas para armazenar dados.

Quando um arquivo é apagado, o sistema de arquivos normalmente marca o espaço como disponível. O conteúdo pode permanecer no disco até ser sobrescrito.

## 2. SSD — Solid State Drive

O SSD utiliza memória flash NAND para armazenar dados, sem pratos magnéticos giratórios.

A recuperação de arquivos apagados depende de vários fatores, como o funcionamento do controlador, o uso do TRIM e as operações realizadas após a exclusão.

## 3. NVMe

NVMe é um protocolo de comunicação usado normalmente por SSDs conectados por PCIe. Ele permite que o sistema operacional se comunique com o dispositivo de armazenamento.

## 4. TRIM

TRIM permite que o sistema operacional informe ao SSD quais blocos lógicos não precisam mais preservar os dados.

O controlador pode processar esses blocos para reutilização, o que pode dificultar ou impossibilitar a recuperação de dados apagados.

## 5. Garbage collection

É um processo interno do controlador do SSD que reorganiza dados válidos e libera blocos para novas gravações.

## 6. Wear leveling

É uma técnica que distribui as gravações entre as células de memória para reduzir o desgaste excessivo de determinadas regiões.

## 7. Importância para a perícia digital

Um arquivo apagado de um HDD pode continuar recuperável enquanto seus dados não forem sobrescritos.

Em um SSD com TRIM, os dados podem se tornar inacessíveis devido ao processamento interno do dispositivo. Por isso, o perito deve preservar a evidência, documentar os procedimentos e evitar conclusões absolutas sem suporte técnico.

## O que aprendi

- Diferenciar HDD de SSD.
- Explicar o que são trilhas e setores.
- Entender o papel da memória NAND e do protocolo NVMe.
- Explicar TRIM, garbage collection e wear leveling.
- Compreender por que a recuperação de arquivos apagados depende do dispositivo e de seu estado.