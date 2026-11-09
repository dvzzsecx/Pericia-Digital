# Fase 2 — Discos: HDD, SSD, NVMe e Mídia Flash

## 1. HDD

O HDD é um disco rígido mecânico que utiliza magnetismo para armazenar dados.

- Pratos: superfícies magnéticas.
- Trilhas: círculos concêntricos.
- Setores: divisões utilizadas para organizar os dados.
- Cabeça de leitura e escrita: lê e grava informações.

Quando um ficheiro é apagado, os dados podem permanecer nos setores até serem sobrescritos.

## 2. SSD e NAND

O SSD utiliza memória flash NAND e não possui partes mecânicas.

- Lê e grava dados em páginas.
- Apaga dados em blocos.
- Mantém informações sem energia elétrica.

As células NAND podem ser SLC, MLC, TLC ou QLC, conforme a quantidade de bits armazenados por célula.

## 3. NVMe

NVMe é um protocolo de comunicação utilizado principalmente por SSDs ligados através de PCIe.

Não é sinónimo de SSD. Existem também SSDs SATA.

## 4. TRIM

É uma notificação enviada pelo sistema operativo ao SSD, indicando que determinados blocos lógicos já não contêm dados necessários.

Isso permite ao dispositivo tratar essas áreas como disponíveis para reutilização.

## 5. Wear leveling

Técnica utilizada para distribuir operações de escrita e apagamento entre os blocos NAND, evitando desgaste excessivo de determinadas células.

## 6. Garbage collection

Processo interno do SSD que reorganiza páginas válidas e prepara blocos para futuras gravações.

## 7. Pendrives e cartões SD

Utilizam memória flash não volátil. Podem conter documentos, fotografias, vídeos e outros vestígios digitais.

## 8. Importância para a perícia digital

Num HDD, os dados apagados podem permanecer até serem sobrescritos.

Num SSD com TRIM, os dados podem ser descartados pelo controlador e posteriormente apagados fisicamente durante a gestão interna da memória.

Por isso, um ficheiro apagado pode tornar-se irrecuperável.

## 9. Ferramentas

Linux:
- lsblk
- fdisk -l
- lsblk -o NAME,SIZE,TYPE,FSTYPE,PTTYPE,START,MOUNTPOINTS

Windows:
- fsutil behavior query DisableDeleteNotify

## 10. Conclusão

O perito digital precisa compreender como cada tecnologia armazena, apaga e reutiliza dados.

A recuperação de ficheiros apagados depende da tecnologia, do estado do dispositivo, do sistema de ficheiros e das operações realizadas após a eliminação.

**Critério de domínio:** explicar por que um ficheiro apagado num SSD com TRIM pode tornar-se irrecuperável, mesmo sem uma sobrescrita convencional pelo utilizador.
