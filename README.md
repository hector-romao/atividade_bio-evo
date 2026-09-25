# Atividade de Biologia Evolutiva

Este repositório reúne os dados utilizados em uma atividade assíncrona da disciplina de Biologia Evolutiva. Os arquivos estão no formato FASTA e contêm sequências associadas a diferentes personagens de Pokemon, incluindo Vulpix, Vulpix de Alola, Sandshrew, Sandshrew de Alola e Pikachu.

## Arquivos

- `cds_only.fasta`: sequências correspondentes às regiões codificantes (CDS).
- `genoma_completo.fasta`: sequências dos genomas completos.
- `golpe_1.fasta` a `golpe_4.fasta`: quatro conjuntos de sequências relacionados aos golpes analisados na atividade.
- `vulpix_dados.fasta`: conjunto de sequências utilizado especificamente para a análise de Vulpix e suas variações.

Cada arquivo FASTA contém os identificadores das sequências no cabeçalho, precedidos pelo caractere `>`.

## Organização dos dados

| Arquivo | Número de sequências | Total de bases |
| --- | ---: | ---: |
| `cds_only.fasta` | 12 | 8.640 |
| `genoma_completo.fasta` | 12 | 25.296 |
| `golpe_1.fasta` | 12 | 2.160 |
| `golpe_2.fasta` | 12 | 2.160 |
| `golpe_3.fasta` | 12 | 2.160 |
| `golpe_4.fasta` | 12 | 2.160 |
| `vulpix_dados.fasta` | 7 | 1.282 |

## Como utilizar

Os arquivos podem ser analisados com ferramentas de bioinformática que aceitem o formato FASTA, como alinhadores de sequências, programas de construção de árvores filogenéticas e scripts em Python ou R.

Antes de iniciar uma análise, confira os cabeçalhos e a natureza de cada conjunto para garantir que as sequências comparadas sejam biologicamente compatíveis com a pergunta da atividade.

## Objetivo didático

Os dados servem como material de apoio para estudar comparação de sequências, conservação e divergência, alinhamento e possíveis relações evolutivas entre os grupos analisados.